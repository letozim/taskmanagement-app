# 📋 Taskmanagement-Anwendung

Diese Java-basierte Webanwendung dient zur Organisation und Verwaltung von Aufgaben. Sie wurde entwickelt, um tägliche ToDos effizient zu strukturieren und bietet grundlegende Funktionen wie Aufgabenanlage, Statusänderungen und Gruppierung nach Bearbeitungsstand.

## 🌟 Funktionsübersicht

- Aufgaben anlegen mit:
  - Titel
  - Beschreibung
  - Status (Offen, In Bearbeitung, Erledigt)
  - Fälligkeitsdatum
- Aufgabenstatus ändern
- Aufgaben löschen
- Gruppierte Darstellung der Aufgaben nach Status
- Aufgabenbearbeitung mit Erhalt unveränderter Felder
- Einfache, benutzerfreundliche Weboberfläche

## 🛠️ Verwendete Technologien

- **Java 17**
- **Spring Boot** – zur Umsetzung der Webanwendung
- **HTML + JSP** – zur Darstellung der Oberfläche
- **Maven** – Build-Management und Abhängigkeiten
- **Javadoc** – zur technischen Dokumentation
- **Lokale Dateispeicherung** – zur persistente Speicherung der Aufgaben (keine externe Datenbank)

## 📁 Projektstruktur

- **src/main/java** – Anwendungslogik  
  Beinhaltet den gesamten Java-Code, aufgeteilt in verschiedene Schichten:  
  `src/main/java/com/example/taskmanager/`  
  ├── **controller/** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Steuert die HTTP-Anfragen (z. B. HomeController, TaskController)  
  ├── **model/** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Datenmodell (z. B. Task.java)  
  ├── **repository/** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Schnittstelle zur Datenbank (z. B. TaskRepository)  
  └── **service/** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Geschäftslogik (z. B. TaskManagerApplication)  

- **src/main/resources** – Konfigurationen  
  Beinhaltet Konfigurationsdateien und Templates:  
  `src/main/resources/`  
  ├── **templates/**  
  │   ├── index.html  
  │   └── new-task.html  
  └── **application.properties**  

- **src/test** – Tests  

- **pom.xml** – Maven-Konfigurationsdatei  
  Enthält Projektabhängigkeiten, Plugins und Build-Konfiguration.  

- **.gitignore** – Git-Konfiguration  
  Legt fest, welche Dateien nicht versioniert werden sollen.  

- **README.md** – Projektdokumentation  


## 📄 Dokumentation

Das Projekt enthält:
- Ein **Lastenheft**, das die Anforderungen systematisch beschreibt
- Eine **vollständige Javadoc-Dokumentation**, generiert mit IntelliJ

## 🚀 Anwendung starten

 1. git clone https://github.com/letozim/taskmanagement-app.git
- Lädt das Projekt von GitHub auf deinen Computer herunter.
 2. cd taskmanagement-app
- Wechselt in den Ordner, in dem das Projekt gespeichert ist.
 3. git checkout main
- Stellt sicher, dass du auf dem Hauptzweig (main) bist.
 4. npm install
- Installiert benötigte Node.js-Bibliotheken.
 5. javac *.java
- Kompiliert alle Java-Quellcode-Dateien im aktuellen Ordner.
 6. java TaskManagerApplication.java
- Startet die Java-Anwendung.
 7. mvn clean install
- Baut das Projekt mit Maven, kompiliert den Code und führt Tests aus.
 8. mvn spring-boot:run
- Startet die Anwendung mit Spring Boot.
 9. Öffne im Browser die Adresse: http://localhost:8080/
- Zeigt die laufende Anwendung an.

## 📌 Hinweis

Dieses Projekt wurde im Rahmen eines privaten Studienprojekts zur Aufgabenverwaltung entwickelt und dient als Referenz für Java-Webentwicklung mit Spring Boot.

---

Falls du zusätzlich noch eine englische Version brauchst oder dein GitHub-Profil damit aufwerten willst, helfe ich dir gern weiter.
