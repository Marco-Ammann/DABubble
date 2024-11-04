
# Da-Bubble

**Da-Bubble** ist ein Showcase-Projekt, das als moderne Webanwendung entwickelt wurde, um als Kommunikationsplattform zu dienen. Dieses Projekt soll meine Fähigkeiten als Frontend-Entwickler in einem realen Anwendungsbeispiel demonstrieren. Es kombiniert moderne Technologien und Best Practices, um eine skalierbare und performante Lösung zu präsentieren.

## 🚀 Features

- **Echtzeit-Kommunikation**: Unterstützung für Nachrichten in Echtzeit, Threads und die Anzeige von Channels.
- **Authentifizierung und Sicherheit**: Implementiert mit Firebase Authentication für sichere und schnelle Anmeldeprozesse.
- **Progressive Web App (PWA)**: Die Anwendung kann als PWA installiert und offline genutzt werden, um die Benutzerfreundlichkeit und Erreichbarkeit zu erhöhen.
- **Responsive Design**: Optimiert für Desktop- und mobile Geräte, um eine nahtlose Benutzererfahrung zu gewährleisten.
- **Modularität und Wartbarkeit**: Basierend auf Angular mit einem komponentenbasierten Architekturansatz und Services, um Wiederverwendbarkeit und Erweiterbarkeit zu fördern.
- **Material Design**: Verwendung von Angular Material für eine ansprechende und benutzerfreundliche UI.
- **SASS (SCSS)**: Strukturierte und erweiterbare Stile für eine moderne und übersichtliche Gestaltung.
- **Caching und Performance**: Nutzung von Services zur Caching-Optimierung und Reduzierung der Datenbankanfragen, was zu einer besseren Performance führt.

## 🛠️ Technologien im Einsatz

- **Angular (Version 17/18)**: Die Haupttechnologie des Projekts, bekannt für ihre modulare Struktur, umfangreichen Tools und robusten Entwicklungspraktiken.
- **Firebase**: Verwendet für das Backend, um die Datenbank, Authentifizierung und Hosting zu unterstützen.
- **Angular Material**: Für das UI-Design, um konsistente und visuell ansprechende Benutzeroberflächen zu erstellen.
- **Progressive Web App (PWA)**: Ermöglicht die Installation der Web-App und die Nutzung im Offline-Modus.
- **SCSS (SASS)**: Für erweiterte Styling-Möglichkeiten, die eine bessere Wartbarkeit und Lesbarkeit bieten.

## 📚 Projektübersicht

### Struktur und Architektur
Die Anwendung folgt dem komponentenbasierten Architekturansatz, um die Wiederverwendbarkeit und Wartbarkeit des Codes zu gewährleisten. Die Hauptkomponenten sind in verschiedene Module wie `main-page`, `main-sign-in`, `thread`, und `shared` unterteilt, die jeweils spezifische Funktionalitäten abdecken.

### Besondere Herausforderungen
- **Datenkonsistenz**: Um sicherzustellen, dass die Daten in Echtzeit synchron sind, wurde Firebase als Datenbanklösung verwendet, was zusätzliche Arbeit bei der Implementierung des Caching-Systems erforderte.
- **State Management**: Die Verwaltung des Zustands über verschiedene Komponenten hinweg stellte eine Herausforderung dar, die durch den Einsatz von Services und Observables in Angular gelöst wurde.
- **Performance-Optimierung**: Um die Lesevorgänge aus der Firebase-Datenbank zu minimieren, wurde ein Caching-System integriert. Dadurch wurden die Latenzzeiten reduziert und die Benutzererfahrung verbessert.
- **Responsive und benutzerfreundliche Oberfläche**: Die Verwendung von Angular Material und benutzerdefinierten Stilelementen (SCSS) hat zu einer ansprechenden, responsiven Benutzeroberfläche geführt.

## 🔧 Installation und Setup

1. **Projekt klonen**:
   ```bash
   git clone https://github.com/Marco-Ammann/Da-Bubble.git
   cd Da-Bubble
   ```

2. **Abhängigkeiten installieren**:
   ```bash
   npm install
   ```

3. **Umgebungsvariablen einrichten**:
   Erstelle eine `src/app/firebase.config.ts`-Datei mit den nötigen Firebase-Konfigurationsdaten.

4. **Lokaler Server starten**:
   ```bash
   ng serve
   ```
   Die Anwendung ist dann standardmäßig unter `http://localhost:4200/` erreichbar.

## 💡 Lernziele und Erfahrung

Dieses Projekt hat es mir ermöglicht, tiefere Einblicke in den Aufbau moderner Webanwendungen zu gewinnen und meine Fähigkeiten in folgenden Bereichen zu erweitern:

- **Arbeiten mit Firebase**: Umgang mit Echtzeitdatenbank, Authentifizierung und Cloud-Speicher.
- **Moderne UI-Gestaltung**: Verwendet Angular Material und SCSS für eine konsistente Benutzeroberfläche.
- **Implementierung einer PWA**: Die App kann als native Anwendung genutzt werden, was eine bessere Nutzerbindung ermöglicht.
- **Optimierung und Debugging**: Behebung von Performance-Problemen und Optimierung der Datenbankzugriffe.

## 📸 Screenshots
Logo:
![Screenshot 2024-08-30 234533](https://github.com/user-attachments/assets/ae825e81-9c79-4375-b5c8-9aa91ef4e629)

Hauptseite:
![image](https://github.com/user-attachments/assets/bc02e527-0b14-468c-a843-be557cb07b0f)



## 📝 Fazit

**Da-Bubble** ist mehr als nur ein Projekt – es ist eine Demonstration meiner Fähigkeit, komplexe Anwendungen mit modernen Webtechnologien zu erstellen. Ich hoffe, es zeigt meine Liebe zur Entwicklung und meinen Fokus auf sauberen, wartbaren Code.
