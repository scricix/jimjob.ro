# 🎥 JimJob - Platformă de Recrutare Video

JimJob este o platformă inovatoare de recrutare care schimbă modul în care angajatorii interacționează cu candidații, punând accent pe **aplicațiile video**. Proiectul oferă un ecosistem complet pentru publicarea anunțurilor, gestionarea candidaturilor și statistici detaliate.

![JimJob Banner](https://via.placeholder.com/1200x400.png?text=JimJob+Platforma+Video+Recrutare "JimJob Preview")

## ✨ Funcționalități Principale

### 🏢 Pentru Angajatori (PRO)
*   **Dashboard Avansat (CMS)**: Panou de administrare modern pentru gestionarea anunțurilor.
*   **Aplicații Video**: Vizualizarea candidaților direct în platformă prin player-ul integrat.
*   **Statistici Live**: Monitorizare în timp real pentru:
    *   👁️ Vizualizări anunț
    *   💾 Salvări
    *   🎥 Număr de aplicanți
*   **Management Anunțuri**: Adăugare, editare, ștergere și vizualizare anunțuri.
*   **Contact Rapid**: Butoane directe pentru apel telefonic și WhatsApp către candidați.

### 👨‍💼 Pentru Candidați
*   **Aplicare prin Video**: Posibilitatea de a se prezenta printr-un scurt video în loc de CV-ul tradițional.
*   **Player Video Dedicat**: Interfață modernă de încărcare și vizualizare a video-ului înainte de trimitere.
*   **Profil Utilizator**: Gestionarea datelor personale și a istoricului.

## 🛠️ Tehnologii Utilizate

Proiectul este construit folosind tehnologii web standard, optimizate pentru performanță și compatibilitate maximă:

*   **Frontend**:
    *   HTML5 & CSS3 (Design personalizat, Glassmorphism, Responsive)
    *   JavaScript (ES6+, Fetch API pentru operațiuni asincrone)
    *   Lucide Icons (pentru iconițe vectoriale moderne)
*   **Backend**:
    *   PHP (Arhitectură nativă, sesiuni securizate)
    *   MySQL (Bază de date relațională optimizată)
*   **Securitate**:
    *   Protecție împotriva CSRF și XSS
    *   Sesiuni persistente
    *   Validare date input

## 📁 Structură Proiect

```
/
├── index.php                  # Pagina principală
├── user_pro/                  # Modulul pentru utilizatori PRO
│   ├── cms_anunturi_pro.html  # Interfața CMS
│   ├── player_app_pro.php     # Player-ul de aplicare
│   ├── get_anunturi_pro.php   # API Backend
│   └── ...
├── promovare_anunturi/        # Modulul standard de anunțuri
├── assets/                    # Resurse statice (imagini, css, js)
└── github/                    # Documentație proiect
```

## 🚀 Cum să începi

1.  **Clonează repository-ul**
    ```bash
    git clone https://github.com/username/jimjob.git
    ```
2.  **Configurează baza de date**
    *   Importă structura SQL din `database/schema.sql`.
    *   Configurează conexiunea în `db.php`.
3.  **Pornește serverul**
    *   Rulează pe un server Apache/Nginx cu suport PHP.

## 📝 Licență

Acest proiect este proprietate privată JimJob. Toate drepturile rezervate.
