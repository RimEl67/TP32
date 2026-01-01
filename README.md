# TP 32 – Mise en place d’un pipeline CI/CD Microservices
# Par: Rim EL ABBASSI  

---

## Présentation

Ce travail pratique a pour objectif de mettre en place un **pipeline CI/CD complet** pour une architecture **microservices**, en s’appuyant sur les outils suivants :

- **Jenkins** pour l’intégration et le déploiement continus
- **GitHub** pour la gestion du code source
- **SonarQube** pour l’analyse de la qualité du code
- **Docker Compose** pour le déploiement des services
- **Ngrok** pour exposer Jenkins et configurer les webhooks GitHub

Le pipeline est déclenché automatiquement à chaque **push GitHub** et assure la compilation, l’analyse qualité et le déploiement des microservices.

---

## Objectifs 

- Installer et configurer **Jenkins** (JDK, Maven, SonarScanner)
- Déployer **SonarQube** avec Docker Compose
- Mettre en place des projets SonarQube et des tokens par microservice
- Exposer Jenkins via **Ngrok**
- Configurer les **webhooks GitHub**
- Créer un **job Jenkins Pipeline**
- Implémenter un pipeline multi-stages
- Vérifier l’exécution automatique après chaque push

<img width="1323" height="587" alt="image" src="https://github.com/user-attachments/assets/b9667cb5-2966-44fd-a913-26e5868852a4" />
