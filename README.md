deploy clair and Scan your local Docker images using below commands.

$ git clone https://github.com/Abhay956/clair-project-2.git

$ cd clair-project-2/clair_local_poc/

$ docker-compose up -d

$ docker-compose exec clairctl clairctl analyze -l (local-docker-image)
