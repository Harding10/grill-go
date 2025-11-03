
```bash
src
├── App.css                        # Styles globaux pour le composant App
├── App.jsx                        # Composant racine de l'application (souvent contient les layouts ou routes)
├── assets                         # Dossier contenant les ressources de l'application
│   ├── api
│   │   └── axiosClient.js         # Configuration Axios pour les appels API (baseURL, headers, etc.)
│   ├── components                 # Composants réutilisables dans toute l'application
│   │   ├── Footer.jsx             # Pied de page commun
│   │   ├── Navbar.jsx             # Barre de navigation principale
│   │   └──      
│   ├── layouts                    # Gabarits de mise en page
│   │   ├── DashboardLayout.jsx    # Layout pour les pages du tableau de bord (avec sidebar, header, etc.)
│   │   └── PublicLayout.jsx       # Layout pour les pages publiques (landing, login, etc.)
│   ├── pages                      # Pages principales de l'application
│   │   ├── Auth                   # Pages liées à l'authentification
│   │   │   ├── LoginPage.jsx      # Page de connexion
│   │   │   └── RegisterPage.jsx   # Page d'inscription
│   │   ├── Dashboard              # Pages internes du tableau de bord
│   │   │   ├── Menus.jsx          # Page de gestion des menus (plats, catégories, etc.)
│   │   │   ├── Orders.jsx         # Page de gestion des commandes
│   │   │   ├── Settings.jsx       # Page de configuration du compte ou de l'app
│   │   │   └── Tables.jsx         # Page de gestion des tables (restaurant)
│   │   ├── LandingPage.jsx        # Page d'accueil publique
│   │   └── MenuPage.jsx           # Page publique affichant les menus/plats
│   ├── react.svg                  # Logo React (souvent utilisé dans la landing page)
│   └── router
│       └── index.jsx              # Fichier de configuration des routes avec React Router
├── index.css                      # Fichier de styles globaux (souvent importé dans main.jsx)
└── main.jsx                       # Point d'entrée de l'application, monte <App /> dans le DOM





