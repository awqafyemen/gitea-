1. To start this setup based on docker-compose, execute docker-compose up -d, to launch Gitea in the background. 
2. Using docker-compose ps will show if Gitea started properly. Logs can be viewed with docker-compose logs.

3. To shut down the setup, execute docker-compose down. This will stop and kill the containers. The volumes will still exist.

Notice: if using a non-3000 port on http, change app.ini to match LOCAL_ROOT_URL = http://localhost:3000/.
