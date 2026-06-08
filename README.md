# PharmaSys Docker Ready

Version Docker prête à lancer de **PharmaSys**.

Ce dépôt contient une archive ZIP avec le frontend, le backend, PostgreSQL et une configuration Docker complète.

Pour exécuter le projet, il faut télécharger puis extraire le fichier :

```text
pharmasys-docker-ready.zip
```

## Étapes de lancement

1. Extraire le fichier ZIP.
2. Ouvrir un terminal dans le dossier extrait :

```text
pharmasys-docker-ready
```

3. Lancer la commande suivante :

```bash
docker compose up --build
```

4. Ouvrir l'application dans le navigateur :

```text
http://localhost:8088
```

## Identifiants de test

```text
Login : admin
Mot de passe : admin
```

## Services lancés par Docker

* Frontend React
* Backend Spring Boot
* Base de données PostgreSQL

## Réinitialisation de la base de données

Si la base contient d’anciennes données Docker, relancer le projet avec les commandes suivantes :

```bash
docker compose down -v
docker compose up --build
```

