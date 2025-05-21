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

src/main/java – Anwendungslogik
Beinhaltet den gesamten Java-Code, aufgeteilt in verschiedene Schichten:
src/main/java/com/example/taskmanager/
├── controller/     # Steuert die HTTP-Anfragen (HomeController, TaskController)
├── model/          # Datenmodell (Task.java)
├── repository/     # Schnittstelle zur Datenbank (z. B. TaskRepository)
├── service/        # Geschäftslogik (TaskManagerApplication)
src/main/resources – Konfigurationen
Beinhaltet Konfigurationsdateien und Templates:
src/main/resources/
├── templates/
│   ├── index.html
│   └── new-task.html
└── application.properties
src/test – Tests
pom.xml – Maven-Konfigurationsdatei
Enthält Projektabhängigkeiten, Plugins und Build-Konfiguration.
.gitignore – Git-Konfiguration
Legt fest, welche Dateien nicht versioniert werden sollen.
README.md – Projektdokumentation

## 📄 Dokumentation

Das Projekt enthält:
- Ein **Lastenheft**, das die Anforderungen systematisch beschreibt
- Eine **vollständige Javadoc-Dokumentation**, generiert mit IntelliJ

## 🚀 Anwendung starten

1. Projekt mit Maven bauen:  
   `mvn clean install`

2. Anwendung starten:  
   `mvn spring-boot:run`

3. Im Browser öffnen:  
   `http://localhost:8080/`

## 📌 Hinweis

Dieses Projekt wurde im Rahmen eines privaten Studienprojekts zur Aufgabenverwaltung entwickelt und dient als Referenz für Java-Webentwicklung mit Spring Boot.

---

Falls du zusätzlich noch eine englische Version brauchst oder dein GitHub-Profil damit aufwerten willst, helfe ich dir gern weiter.
