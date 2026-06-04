# GreenOps Platform - Projet Infrastructure Containerisée

Ce dépôt contient l'architecture complète de la plateforme **GrEENOPS**, réalisée dans le cadre du module Docker & Kubernetes.

## 📁 Structure du Projet
* `/frontend` : Interface utilisateur (Nginx)
* `/backend-auth` : Microservice d'Authentification (JWT)
* `/backend-metrics` : Microservice de calcul des Métriques Énergétiques
* `/nginx` : Configuration du Reverse Proxy pour l'environnement Docker
* `/k8s` : Manifestes de déploiement Kubernetes (Deployments, Services, ConfigMap, Secrets, Ingress)

## 🚀 Étape 1 : Lancement de l'environnement Docker Compose
Pour démarrer l'infrastructure locale, assurez-vous que Docker Desktop est actif et exécutez la commande suivante à la racine :
```bash
docker compose up -d --build