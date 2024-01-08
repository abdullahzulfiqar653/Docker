# DokcerFileToRunCommonImages

to run the project please follow the instructions given

**Note:** Install Docker on local machine from https://docs.docker.com/engine/install/

**clone the project and open terminal inside Project directory**

**1:** clone the project and open terminal inside Project directory

**2:** setup .env and check .env.example for sample.

**3:** there are three docker files inside it.

**i:** to run mysql image

```
docker compose -f docker-compose-mysql.yml up
```

**ii:** to run broker images

```
docker compose -f docker-compose-broker.yml up
```

**iii:** to run postgres and pgadmin containers

```
docker compose -f docker-compose-postgres.yml up
```

**4: to run images in background just add a flag -d at the end of every command**
