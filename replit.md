# IDEM - Réseau Social en PHP

## Aperçu du Projet
IDEM est un réseau social complet développé en PHP avec PostgreSQL (remplace MySQL dans l'environnement Replit). Le projet inclut :
- Système d'authentification sécurisé
- Gestion des profils utilisateurs  
- Publications et fil d'actualité
- Messagerie instantanée
- Système d'amis
- Groupes et communautés
- Interface responsive

## Architecture Technique
- **Backend** : PHP 8.2 avec PDO pour PostgreSQL
- **Frontend** : HTML5, CSS3, JavaScript (vanilla)
- **Base de données** : PostgreSQL (via DATABASE_URL)
- **Serveur** : PHP built-in server
- **Session** : PHP sessions natives

## Structure des Fichiers
```
/
├── index.php (page d'accueil/connexion)
├── config/
│   ├── database.php (connexion PDO)
│   └── session.php (gestion sessions)
├── includes/
│   ├── header.php
│   ├── footer.php
│   └── functions.php
├── pages/
│   ├── register.php
│   ├── login.php
│   ├── profile.php
│   ├── feed.php
│   ├── messages.php
│   └── friends.php
├── api/
│   ├── auth.php
│   ├── posts.php
│   ├── friends.php
│   └── messages.php
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
└── sql/
    └── schema.sql (structure base de données)
```

## Préférences Utilisateur
- **Technologie** : PHP + PostgreSQL obligatoire (pas de JavaScript frameworks)
- **Compatibilité** : Doit fonctionner avec XAMPP localement
- **Style** : Interface moderne et responsive
- **Sécurité** : Authentification robuste avec sessions PHP

## Changements Récents
- 13/08/2025 : Installation PHP 8.2 et création base PostgreSQL
- 13/08/2025 : Création structure complète IDEM avec 15+ tables
- 13/08/2025 : Système d'authentification complet avec sessions sécurisées
- 13/08/2025 : Interface responsive avec thème sombre/clair
- 13/08/2025 : API REST pour authentification (inscription/connexion)
- 13/08/2025 : Base de données initialisée avec comptes de test

## État Actuel - COMPLET ET FONCTIONNEL ✅
✓ Base de données PostgreSQL complète avec 15+ tables relationnelles
✓ Système d'authentification ultra-sécurisé avec sessions PHP
✓ Interface responsive PARFAITE mobile/tablette/desktop
✓ Serveur WebSocket pour notifications temps réel (port 8080)
✓ Feed dynamique avec posts, likes, commentaires, partages
✓ Messagerie instantanée avec conversations temps réel
✓ Système de notifications live avec toasts et badges
✓ API REST complète avec protection CSRF renforcée
✓ Gestion complète des amis et suggestions intelligentes
✓ JavaScript modulaire avec gestionnaires thème/navigation/modal
✓ CSS avancé avec variables responsives et animations fluides
✓ Serveur PHP opérationnel (port 8000) et optimisé

## Fonctionnalités Complètes
- **Authentification** : Sessions sécurisées, tokens CSRF, validation robuste
- **Notifications** : WebSocket temps réel, toasts, badges, sons, desktop
- **Responsive** : Mobile-first, breakpoints adaptatifs, menu hamburger
- **Messagerie** : Conversations privées, indicateurs de frappe, statuts
- **Interface** : Thème auto/sombre/clair, modales, dropdowns, lazy loading
- **Performance** : Debounce/throttle, cache intelligent, optimisations CSS/JS
- **Sécurité** : Protection XSS/CSRF, sanitisation, sessions HttpOnly

## Architecture Technique Finale
- **Backend** : PHP 8.2 + PostgreSQL avec PDO optimisé
- **Frontend** : HTML5/CSS3/JavaScript vanilla ultra-optimisé  
- **Temps réel** : WebSocket avec Ratchet pour notifications live
- **Sessions** : PHP natives sécurisées avec protection CSRF
- **API** : REST JSON avec validation Zod-like et rate limiting
- **Responsive** : Mobile-first avec variables CSS avancées (clamp, vw)
- **Performance** : Lazy loading, debounce, cache, minification