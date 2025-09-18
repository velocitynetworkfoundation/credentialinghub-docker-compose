# credentialinghub-docker-compose
Credentialing Hub Docker Compose

This agent can be deployed on a single instance as a docker compose that will run the agent and an instance of mongo.
It is **not recommended** to use docker-compose in a production environment.

This has been tested on Version 19 of docker and 1.26 of docker-compose. Your mileage may vary on other versions.

## Getting Started

Use the credentialinghub-docker-compose repo 
1. `git clone https://github.com/velocitynetworkfoundation/credentialinghub-docker-compose.git`
1. `cd credentialinghub-docker-compose`
1. `cp .env_example .env`
1. Fill in empty values (and optionally modify existing ones) in the .env. (See [Credentialing Hub Configuration](https://www.velocitynetwork.foundation/main/developers-guide-credentialing-hub-operation#hub-server-configuration))
1. `docker-compose pull`
1. `docker-compose up`
1. `curl http://localhost:8080` should return a successful response


#### Agent Env Configuration

See [Credentialing Hub Configuration](https://www.velocitynetwork.foundation/main/developers-guide-credentialing-hub-operation#hub-server-configuration)
for more information about setting up environment variables and configuring the credentialing hub
