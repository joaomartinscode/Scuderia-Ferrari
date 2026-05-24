# Scuderia Ferrari - Web Programming Project

Welcome to the digital garage of Scuderia Ferrari. This is a premium, multi-page web experience engineered to look as fast, aggressive, and expensive as an actual Formula 1 car—but luckily with 100% fewer engine reliability issues and zero strategy blunders.

---

## Project Overview & Page Anatomy

The entire application adopts a midnight-stint "Dark Mode" aesthetic, leveraging the iconic Ferrari Red (`#EF1A2D`) and Yellow (`#FFEB00`) against carbon-fiber inspired backgrounds.

### 1. Home (`index.html`)
The main launching pad. It features a full-screen, high-impact Bootstrap carousel with smooth cross-fade transitions (`carousel-fade`) showcasing the team dynamic, cutting-edge engineering, and a call-to-action that pulls you straight into the paddock.

### 2. Team & Engineering (`pages/equipa.html`)
The technical core of the project. 
* **The Lineup:** Meet our current driver pairing—the local hero Charles Leclerc and some promising rookie named Lewis Hamilton.
* **The Telemetry:** Contains a full technical breakdown of the SF-26 challenger, utilizing custom-styled structural data rows that act as visual progress bars to display horsepower, weight, and top speed specs.

### 3. History (`pages/historia.html`)
A chronological timeline tracking the legacy of the Cavallino Rampante since 1929. It uses an alternating grid layout that scales beautifully, balancing historical text with high-resolution imagery showcasing decades of winning trophies and breaking hearts.

### 4. Contact (`pages/contactos.html`)
The strategy feedback loop. Features a fully validated, clean dark-mode form designed for users to submit feedback (or complain about pit stop times). It also features an embedded Google Maps module stylized natively via CSS filters (`invert` and `hue-rotate`) to seamlessly match the dark aesthetic of the Maranello headquarters.

---

## Tech Stack & Code Regulations

To keep the FIA stewards happy, this project relies purely on raw mechanical grip—built strictly under "no custom JavaScript" regulations using only HTML5, CSS3, and the native Bootstrap 5 toolkit.

* **HTML5 Semantic Architecture:** Built using clean, modern tags (`<header>`, `<main>`, `<section>`, `<article>`, `<figure>`) to guarantee clean rendering, high accessibility, and perfect structure.
* **Pure CSS3 Styling:** No preprocessors, no bloated shortcuts, and absolutely **no global CSS variables**. Every single hexadecimal color and rule is applied directly and explicitly to keep the stylesheet lightning-fast and highly specific.
* **Bootstrap v5.3.3 Utilities:** Utilized heavily for its mobile-first responsive layout mechanics (`row`, `col-md-*`), navigation triggers, and card components.
* **Bootstrap Icons:** Lightweight vector iconography embedded into social links and interface details to save precious kilobytes on our lap times.

---

## Directory Structure

```text
├── src/
│   ├── index.html         # Main landing page
│   ├── pages/
│   │   ├── equipa.html    # Driver profiles and car specs
│   │   ├── historia.html  # Historical timeline archive
│   │   └── contactos.html # Contact form & map
│   ├── styles/
│   │   └── styles.css     # Central control unit for site aesthetics
│   └── images/            # High-res assets, driver portraits, and SVGs
└── README.md
