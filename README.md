# Docker compose con MySQL e *phpmyadmin*

Database: https://www.mysqltutorial.org/mysql-sample-database.aspx

### Clonare il repository
Utilizzare GitHub Desktop o il tasto di download 'code'.

Invece da terminale:
```
git clone https://github.com/AndreaAvignone/mysql-docker.git
```

Per utenti Mac M* togliere il commento a ```platform: linux/amd64``` in ```docker-compose.yml```

### Run
Installare Docker https://docs.docker.com/get-docker/ e avviare i container da dentro la cartella *mysql-docker*:
```
docker-compose up -d
```

Su Linux potrebbe essere richiesto *sudo*

```
sudo docker-compose up -d
```

Per fermarlo:
```
docker-compose down
```
### Setting
**MySQL**: ```localhost:3306```

**phpmyadmin**: ```localhost:8081```

Per verificare il funzionamento accedere a *phpMyAdmin* e verificare la presenza di *classicmodels*.
