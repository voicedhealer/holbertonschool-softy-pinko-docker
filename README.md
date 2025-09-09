# holbertonschool-softy-pinko-docker

**Projet éducatif Holberton School - Conteneurisation Docker d'une application Softy Pinko**

## 📋 Description

Ce projet est conçu pour offrir une expérience pratique avec Docker et Docker Compose. Il se concentre sur la création, le déploiement et la mise à l'échelle d'une application full-stack en utilisant des technologies de conteneurisation.[1]

L'application **Softy Pinko** est une application web complète qui permet d'apprendre les concepts fondamentaux de Docker dans un environnement réaliste.

## 🎯 Objectifs d'apprentissage

- **Maîtriser Docker** : Comprendre la création et la gestion des conteneurs
- **Docker Compose** : Orchestrer des services multi-conteneurs
- **Déploiement d'applications** : Mettre en production une stack complète
- **Scaling** : Gérer la montée en charge des applications conteneurisées
- **Bonnes pratiques** : Optimisation et sécurisation des conteneurs

## 🛠️ Technologies utilisées

- **Docker** - Conteneurisation
- **Docker Compose** - Orchestration multi-services
- **Application Softy Pinko** - Application web de démonstration

## 📁 Structure du projet

```
holbertonschool-softy-pinko-docker/
├── Dockerfile
├── docker-compose.yml
├── src/
│   └── [fichiers de l'application]
└── README.md
```

## 🚀 Installation et utilisation

### Prérequis

- Docker installé sur votre système
- Docker Compose installé

### Étapes de lancement

1. **Cloner le repository**
   ```bash
   git clone https://github.com/ZeroDayPoke/holbertonschool-softy-pinko-docker.git
   cd holbertonschool-softy-pinko-docker
   ```

2. **Construire les conteneurs**
   ```bash
   docker-compose build
   ```

3. **Lancer l'application**
   ```bash
   docker-compose up -d
   ```

4. **Accéder à l'application**
   - Ouvrez votre navigateur à l'adresse indiquée dans la configuration

## 🔧 Commandes utiles

### Gestion des conteneurs
```bash
# Voir les conteneurs en cours d'exécution
docker-compose ps

# Arrêter les services
docker-compose down

# Voir les logs
docker-compose logs

# Redémarrer un service spécifique
docker-compose restart [service-name]
```

### Développement
```bash
# Reconstruire après des modifications
docker-compose up --build

# Accéder au shell d'un conteneur
docker-compose exec [service-name] /bin/bash
```

## 📚 Concepts Docker abordés

- **Images et conteneurs** : Construction et gestion
- **Volumes** : Persistance des données
- **Réseaux** : Communication inter-conteneurs
- **Variables d'environnement** : Configuration flexible
- **Multi-stage builds** : Optimisation des images

## 🎓 Contexte Holberton School

Ce projet fait partie du curriculum DevOps de Holberton School et vise à :
- Comprendre les enjeux de la conteneurisation
- Maîtriser les outils Docker en situation réelle
- Préparer aux environnements de production modernes

## 📝 Notes de développement

**Historique des commits** :
- `readme update` (Nov 15, 2023)
- `gg` (Jul 7, 2023)
- `yay docker` (Jul 7, 2023)
- `docker test` (Jul 7, 2023)

## 🤝 Contribution

Ce projet est à des fins éducatives dans le cadre du cursus Holberton School. Les contributions sont les bienvenues pour améliorer la documentation et les exemples.

## 📞 Support

Pour toute question relative à ce projet :
- Consultez la documentation Docker officielle
- Référez-vous aux ressources pédagogiques Holberton School
- Échangez avec vos pairs étudiants

***
