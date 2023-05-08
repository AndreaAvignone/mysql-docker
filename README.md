# Docker compose con MySQL e *phpmyadmin*

Database: https://www.mysqltutorial.org/mysql-sample-database.aspx

### Clonare il repository
Utilizzare GitHub Desktop o il tasto di download 'code'.

Invece da terminale:
```
git clone https://github.com/AndreaAvignone/mysql-docker.git
```

Per utenti Mac M* togliere il commento a ```platform: linux/amd64```

### IMPORTANTE: Ricordarsi di aggiungere le credenziali nel file .env
```
MYSQL_USER=user
MYSQL_ROOT_PASSWORD=root_password
MYSQL_PASSWORD=user_password
MYSQL_DATABASE=name
```

### Run
Installare Docker https://docs.docker.com/get-docker/ e avviare i container:
```
docker-compose up -d
```

### Setting
**MySQL**: ```localhost:3306```

**phpmyadmin**: ```localhost:8081```