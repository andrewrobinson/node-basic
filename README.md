

## Node starter project

### Based on https://nodejs.org/fr/docs/guides/nodejs-docker-webapp/

Now it runs with

docker run -p 49160:8080 -d andrewmcrobinson/node-basic
curl http://localhost:49160/

### but what about a docker-compose.yml?

Added one, now instead of docker run you can go:

docker-compose up api

### ok but now I want node to restart as I edit the files in vscode

https://code.visualstudio.com/docs/remote/create-dev-container#_create-a-devcontainerjson-file

https://code.visualstudio.com/docs/remote/create-dev-container#_extend-your-docker-compose-file-for-development


### and debugging would be nice ....


https://code.visualstudio.com/docs/nodejs/nodejs-debugging

