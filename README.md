# Système d'apprentissage API avec Symfony
## 📋 Contexte du projet
Dans le cadre de votre formation de développeur web, vous allez créer une application Symfony permettant d'apprendre à consommer et créer des API REST. Ce projet servira de base d'apprentissage pour comprendre les concepts fondamentaux des API et du framework Symfony.

## 🎯 Objectifs pédagogiques
- Maîtriser les concepts fondamentaux des API REST
- Apprendre à utiliser le framework Symfony
- Implémenter une API REST complète
- Consommer des API externes

## 📝 Consignes
### Fonctionnalités attendues :
- Création d'une API REST respectant les standards
- Validation des données
- Documentation API avec OpenAPI/Swagger
- Tests unitaires et fonctionnels
- Gestion des erreurs HTTP
- Cache HTTP

### Critères de performance
- Architecture respectant les bonnes pratiques Symfony
- Documentation technique complète
- Tests automatisés
- Sécurisation des endpoints
- Optimisation des performances

## 🔧 Technologies utilisées
### Framework et outils :
- Symfony 7.0
- API Platform
- Doctrine ORM
- PHPUnit
- Composer
- Git/GitHub
- Postman/Insomnia/Bruno

### Environnement :
- PHP 8.2+
- MySQL/MariaDB
- Symfony CLI
- Docker (optionnel)

## 💡 Concepts clés abordés
- API REST :
  - Méthodes HTTP
  - Codes de statut
  - Format JSON
  - Authentification/Autorisation
  - CORS

- Symfony :
  - Controllers
  - Entities
  - Services
  - Events
  - Security
  - Cache

## 📦 Installation et configuration
```bash
# Créer un nouveau projet
symfony new api-learning --webapp

# Installer les dépendances
composer install

# Configuration de la base de données dans .env
DATABASE_URL="mysql://root:@127.0.0.1:3306/sfapi_alexandre"

# Créer la base de données
php bin/console doctrine:database:create

# Migrations
php bin/console make:migration
php bin/console doctrine:migrations:migrate
```

## 🚀 Structure du projet
```
en construction
```

## ✨ Fonctionnalités
1. Authentification
   - JWT Token
   - Refresh Token
   - Gestion des rôles

2. Endpoints API
   - CRUD complet
   - Pagination
   - Filtres
   - Tri

3. Documentation
   - OpenAPI/Swagger UI
   - Postman Collection

## 📚 Ressources
- [Documentation Symfony](https://symfony.com/doc/current/index.html)
- [API Platform](https://api-platform.com/docs/)
- [JWT Authentication](https://github.com/lexik/LexikJWTAuthenticationBundle)
- [Best Practices REST](https://swagger.io/resources/articles/best-practices-in-api-design/)

## 🏆 Compétences visées
- Conception d'API REST
- Utilisation avancée de Symfony
- Sécurisation des APIs
- Tests et qualité de code
- Documentation technique
- Bonnes pratiques de développement

___
Exercice réalisé dans le cadre de la formation [Développeur Web et Web Mobile](https://elan-formation.fr/formation/19754) <br>
📅 Date : 10/01/2025 - en cours <br>
✍️ Auteur : [Alexandre Leote](https://github.com/alexandreleote)
