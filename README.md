# ToDo-Applikation mit Markdown, Git, GitHub und Docker 🐋👨‍💻
## Installation des Projektes  
<br>


### Klonen des Repositories ➿

- SSH-Link aus GitHub kopieren <br>

- Kommandozeile öffne (cmd)<br>

- Auf den richtigen Ordner Navigieren (dort wo du es speichern (hinverschieben)willst).<br>

- Mit befehl ```git clone ssh://username@host.xz/absolute/path/to/repo.git/``` Klonen auf den lokalen Rechner (PC). <br>

### Installation der notwendigen Pakete 📦

Mit dem Befehl ```docker init``` werden automatisch diese Dateien installiert:
- `dockerignore`
- `Dockerfile`
- `compose.yaml`
- `README.Docker.md`
Dazu werden auch zusätzliche Pakete im package.json installiert:
- `express`
- `pg`
- `sqlite3`
- `uuid`
- `wait-port`

### Docker-Konfiguration und -Installation 🌍🐳

- [Docker](https://docs.docker.com/desktop/install/windows-install/) Installieren (Achte darauf dass du die richtige Version installierst)<br>

- Überprüfen mit: ```docker run hello-world```<br>

- Container starten mit: ```docker run -d -p 80:80 nginx```<br>

- Erstellen Dockerfile (Image mit bauen) ```docker build```<br>

#### Beispiel für Intel 📝

- Gib (in der Kommandozeile) ```docker init``` ein um es zu Initialisieren (Achte darauf dass den richtigen Ordner (Speicherort)angegeben hast).
<br>
- Dann kommt eine Umfrage gib folgendes ein (Antwort auf Fragen):
   - What application platform does your project use? ```Node```<br>
   - What version of Node do you want to use? ```18.0.0```<br>
   - Wich package manager do you want to use? ```npm``` <br>
   - What command do you want to use to start the app? ```node src/index.js``` <br>
   - What port does your server listen on? ```3000```
<br>
- Dann musst du nur noch ```docker compose up --build``` eingeben damit du das Dockerfile erstellst und dann anschauen kannst im (Web).

### Starten der Applikation in einem Docker-Container 🚀🏁

- Mit der Adresse [Localhost:3000](http://localhost:3000/) kannst du die ToDo-Applikation starten. 
<br>
<img src="/Screenshot_Erklärung_ToDo-Applikation_ZLI_Dario_Erny_38 2024-09-20 152956.png" alt="ToDo-Liste am Laufen :jogger:" width="750"/>


###### *Von: Dario Erny*
   




