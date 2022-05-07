# docker_customer_catalog

Exemple d'application Docker pour PHP Web avec MySQL.

L'application utilise un conteneur pour Apache/PHP et un pour MySQL avec stockage d'applications et de données sur des volumes externes

- Ce référentiel est un fork de : https://github.com/ualmtorres/docker_customer_catalog

## Instructions pour lancer l'application

- Vérifiez si docker compose est installé :
```shell
docker-composer --version
```

- Cloner le référentiel :
 ```shell
git clone git@github.com:juanluck/docker_customer_catalog.git
```

- Aller au référentiel :
```shell
cd docker_customer_catalog
```

- Construisez et lancez l'environnement en mode détaché avec : 
```shell
docker-compose up -d
```

- Arrêtez l'environnement avec :
```shell
docker-compose down
```

- **(facultatif)** Supprimer les conteneurs arrêtés. Avec -fs, il les arrête et force leur suppression :
```shell
docker-compose rm [-fs]
```
