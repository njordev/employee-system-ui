# Employee Management System: Frontend mit React, Vite und Tailwind CSS

Dieses Repository enthält das Frontend einer Employee Management System-Anwendung, entwickelt mit React, Vite und Tailwind CSS. Es bietet eine benutzerfreundliche und reaktionsfähige Oberfläche für die Verwaltung von Mitarbeiterdaten und ist darauf ausgelegt, nahtlos mit einem separaten Backend zu kommunizieren.

## Funktionen des Frontends

### 1. **Komplette Funktionalität:**
- Benutzeroberfläche zur Erstellung, Bearbeitung, Anzeige und Löschung von Mitarbeitern.
- Reaktionsfähiges Design für Desktop- und Mobilgeräte.
- Nahtlose Integration mit dem Backend über REST-APIs.

### 2. **Technologien:**
- **Frontend:** React mit Vite für eine schnelle Entwicklungsumgebung.
- **Design:** Tailwind CSS für modernes und anpassbares Styling.
- **Datenkommunikation:** Axios für API-Anfragen.

---

## Frontend-Entwicklung mit React, Vite und Tailwind CSS

### a. **Projektsetup**
- Erstellung des Projekts mit Vite:
  ```bash
  npm create vite@latest employee-management-frontend --template react
  ```
- Integration von Tailwind CSS:
  - Installation von Tailwind CSS und seinen Peer-Abhängigkeiten:
    ```bash
    npm install -D tailwindcss postcss autoprefixer
    npx tailwindcss init
    ```
  - Konfiguration von `tailwind.config.js` und `index.css` gemäß der [offiziellen Dokumentation](https://tailwindcss.com/docs/installation).

### b. **Komponentenbasierte Architektur**
- **Navbar-Komponente:** Navigationselement zur Steuerung der Seiten.
- **AddEmployee-Komponente:** Formular zur Erstellung neuer Mitarbeiter mit validierter Eingabe.
- **EmployeeList-Komponente:** Anzeige aller Mitarbeiter in einer übersichtlichen Tabelle.

### c. **Zustandsmanagement und API-Aufrufe**
- **Zustandsmanagement:** Verwendung von `useState` und `useEffect` für dynamische Daten.
- **API-Aufrufe:** Axios zur Kommunikation mit dem Backend. Zentralisierte Service-Klasse zur Verwaltung aller API-Interaktionen.

### d. **Routing und Navigation**
- Integration von React Router für die Navigation zwischen verschiedenen Seiten:
  - Mitarbeiterliste
  - Mitarbeiter hinzufügen
  - Mitarbeiter bearbeiten

### e. **Optimierungen**
- Wiederverwendbare Komponenten für Konsistenz und Effizienz.
- Responsive Design für unterschiedliche Bildschirmgrößen.

---

## Setup und Installation

### Voraussetzungen:
- Node.js und npm
- Vite für die Entwicklungsumgebung

### Schritte:
1. **Repository klonen:**
   ```bash
   git clone
   ```
2. **Abhängigkeiten installieren:**
   ```bash
   npm install
   ```
3. **Entwicklungsserver starten:**
   ```bash
   npm run dev
   ```
4. **Frontend im Browser öffnen:**
   - Der Entwicklungsserver ist standardmäßig unter `http://localhost:5173` erreichbar.
