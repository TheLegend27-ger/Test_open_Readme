# KfW DevOps Challenge

## Challenge 3 - Containerize and Run

[Home](../../README.md) - [Next >](../challenge04/README.md)

### Intro

>[...story part
>
>...]

Container sind eine großartige Möglichkeit, Anwendungen zu verpacken und konsistent in verschiedenen Umgebungen einzusetzen. Wenn ihr neu im Umgang mit Containern seid, gibt es 3 wichtige Schritte zum Erstellen und Veröffentlichen eines Images, die im Folgenden beschrieben werden. Da dies ein Hackathon ist, der sich auf DevOps und nicht auf Container konzentriert, haben wir uns bemüht, diese Herausforderung so einfach wie möglich zu gestalten.

1. `docker login` - Ihr müsst euch bei der Container-Registry anmelden, in die ihr euer Image pushen werdet. Wie ihr euch vorstellen könnt, möchten ihr nicht, dass jemand ein Image in eure Registry veröffentlicht, daher ist sie oft als private Registry eingerichtet... und erfordert eine Authentifizierung, um Images zu pushen und zu ziehen.

2. `docker build` - Ihr müsst docker.exe aufrufen (lokal auf eure, Rechner oder auf eurem Build-Server), um das Container-Image zu erstellen. Ein *kritischer* Bestandteil davon ist das `Dockerfile`, das docker.exe Anweisungen gibt, wie das Image zu erstellen ist, die zu kopierenden Dateien, die freizugebenden Ports und Startbefehle.

3. `docker push`- sobald ihr euer Docker-Image erstellt habt, müsst ihr es in der Container-Registry speichern, die unser sicherer und zentraler Speicherort für Docker-Images ist. Docker unterstützt einen Push-Befehl, der das Docker-Image in die Registry in das richtige Repository kopiert. Ein Repository ist eine logische Möglichkeit, Docker-Images zu gruppieren und zu versionieren.

### Tasks

In dieser Aufgabe werdet ihr ein Docker-Image lokal erstellen und ausführen.

1. [Installiert Docker](https://docs.docker.com/get-docker/) auf eurem Rechner.

2. Run the tutorial command `docker run -p 80:80 docker/getting-started` to test if Docker was installed successfully.
   Once it runs you can leave it at that and exit the command (ctrl + c).

3. Geht zum /application Verzeichnis auf eurer lokalen Maschine von eurem geklonten Projekt und führt `docker compose build` aus. Dadurch werden die Docker-Images erstellt. Sobald der Befehl beendet ist, könnt ihr die erstellten Images über `docker images` überprüfen.

4. Verwendet schließlich `docker compose up`, um die Anwendung lokal auszuführen und tippt in euren Browser `localhost:80` um die Applikation aufzurufen, und einen Blick auf die Anwendung zu werfen.

(5. Take a look at the compose file and adapt to update the title, and make a screenshot)

Bei dieser Herausforderung haben wir Docker erfolgreich installiert! Ein Tool, mit dem ihr eure Anwendung in einen Container packen und überall ausführen können.

TODO: [... ecosystem, short explanation of docker usage, short explanation that we are not focusing on docker, but if the participants are interessted to checkout the learning material]

### Checklist

- Ihr habt Docker auf Ihrem Rechner installiert
- Ihr habt die Anwendung containerisiert und lokale Images gebaut
- Überprüft, ob ihr auf die lokal laufende Anwendung zugreifen können.

### Lernmaterial

- [Docker Übersicht](https://docs.docker.com/get-started/overview/)
- [Docker Kommandos](https://docs.docker.com/engine/reference/commandline/cli/)
- [Dockerfile Referenz](https://docs.docker.com/engine/reference/builder/)


[Home](../../README.md) - [Next >](../challenge04/README.md)