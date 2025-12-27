
# 💼 JimJob - Platformă de Recrutare Video-First

JimJob este o aplicație web inovatoare dedicată modernizării procesului de recrutare. Prin eliminarea CV-urilor tradiționale și concentrarea pe aplicații video, platforma oferă angajatorilor o perspectivă autentică asupra candidaților, iar acestora din urmă o modalitate dinamică de a se prezenta.

Proiectul a fost dezvoltat de la zero ("from scratch") pentru a demonstra o înțelegere profundă a tehnologiilor web fundamentale, punând accent pe performanță, securitate și experiența utilizatorului (UX).

## ✨ Funcționalități Cheie

### 🎥 Pentru Candidați (Video Application System)
*   **Înregistrare Video Nativă**: Sistem custom de captură video direct în browser, fără plugin-uri externe. Permite înregistrarea, vizualizarea și reînregistrarea aplicației.
*   **Interfață Mobile-First**: Optimizată pentru aplicarea rapidă de pe telefonul mobil.
*   **Profil Simplificat**: Gestionarea ușoară a datelor personale și a istoricului de aplicări.

### 🏢 Pentru Angajatori (PRO Dashboard)
*   **CMS Avansat**: Panou de control complex pentru gestionarea anunțurilor de angajare.
*   **Statistici Live**: Monitorizare în timp real a performanței anunțurilor (👁️ vizualizări, 💾 salvări, 🎥 număr aplicanți).
*   **Management Aplicații**: Vizualizarea candidaților într-un player dedicat, cu acțiuni rapide de contact (apel telefonic, WhatsApp, email) sau ștergere.
*   **Filtrare și Editare**: Unelte complete pentru administrarea conținutului publicat.

## 🛠️ Arhitectură și Tehnologii

Proiectul refuză utilizarea framework-urilor "grele" în favoarea unei arhitecturi curate și performante:

*   **Frontend**: 
    *   **Vanilla JavaScript (ES6+)**: Logică asincronă complexă gestionată prin Fetch API, fără dependențe precum React sau Vue.
    *   **CSS3 Modern**: Design responsiv folosind CSS Grid, Flexbox și variabile CSS pentru tematică (Dark Mode / Light Mode).
*   **Backend**: 
    *   **PHP 8+**: Arhitectură MVC simplificată, securizată împotriva vulnerabilităților comune (SQL Injection, XSS).
    *   **MySQL**: Bază de date relațională optimizată pentru interogări rapide și integritatea datelor.
*   **Infrastructură**:
    *   Gestionare eficientă a fișierelor media (video/foto).
    *   Sistem de autentificare și sesiuni persistente.

## 🎯 Scopul Proiectului

JimJob demonstrează capacitatea de a construi o aplicație "Full Stack" robustă, scalabilă și estetică, stăpânind întregul ciclu de viață al dezvoltării software - de la baza de date până la pixelul de pe ecran.

