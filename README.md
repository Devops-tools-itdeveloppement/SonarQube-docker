# Install

## Credentiales

modifier le nom du fichier .env_exemple en .env  
Definir au choix des crédentiales  

## Lancement du conteneur

> docker compose up -d            -> demarrer le container

## Acces à l'application

> site accessible sur : http://localhost:9000  

> log / mtp à la premiere connexion : admin admin puis a modifier

## Creer un projet dans sonarqube et le lyer en local avec un token

## Lancer un scan dans le conteneur avec le token

docker run --rm \
  -v "$(pwd):/usr/src" \
  sonarsource/sonar-scanner-cli \               
  -Dsonar.projectKey=newproject \               # nom du projet dans sonarqube
  -Dsonar.sources=code \                    # stockage du code à ananlyser en locale
  -Dsonar.host.url=http://host.docker.internal:9000 \
 -Dsonar.token=sqp_84f1e3278bd5e7975aee0b0df85598395f1d8dbd        # token definit dans sonarqube pour ce projet


## Dossier code source

Mettre le code dans un fichier code à la racine du projet  


## Github

> https://github.com/Devops-tools-itdeveloppement/SonarQube-docker




MSYS_NO_PATHCONV=1 docker run --rm \
docker run --rm \
  -v "$(pwd):/usr/src" \
  sonarsource/sonar-scanner-cli \
  -Dsonar.projectKey=newproject \
  -Dsonar.sources=code \
  -Dsonar.host.url=http://host.docker.internal:9000 \
  -Dsonar.token=sqp_84f1e3278bd5e7975aee0b0df85598395f1d8dbd# Install

## Credentiales

modifier le nom du fichier .env_exemple en .env  
Definir au choix des crédentiales  

## Lancement du conteneur

> docker compose up -d            -> demarrer le container

## Acces à l'application

> site accessible sur : http://localhost:9000  

> log / mtp à la premiere connexion : admin admin puis a modifier

## Creer un projet dans sonarqube et le lyer en local avec un token

## Lancer un scan dans le conteneur avec le token

docker run --rm \
  -v "$(pwd):/usr/src" \
  sonarsource/sonar-scanner-cli \               
  -Dsonar.projectKey=newproject \               # nom du projet dans sonarqube
  -Dsonar.sources=code \                    # stockage du code à ananlyser en locale
  -Dsonar.host.url=http://host.docker.internal:9000 \
 -Dsonar.token=sqp_84f1e3278bd5e7975aee0b0df85598395f1d8dbd        # token definit dans sonarqube pour ce projet


## Dossier code source

Mettre le code dans un fichier code à la racine du projet  


## Github

> https://github.com/Devops-tools-itdeveloppement/SonarQube-docker




MSYS_NO_PATHCONV=1 docker run --rm \
docker run --rm \
  -v "$(pwd):/usr/src" \
  sonarsource/sonar-scanner-cli \
  -Dsonar.projectKey=newproject \
  -Dsonar.sources=code \
  -Dsonar.host.url=http://host.docker.internal:9000 \
  -Dsonar.token=sqp_84f1e3278bd5e7975aee0b0df85598395f1d8dbd