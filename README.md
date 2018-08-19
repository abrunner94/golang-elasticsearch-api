# Go and Elasticsearch
This project shows how you can run both Go and Elasticsearch in a container using the `docker-compose.yaml` task definitions.
## Running the app
To run the Go and Elasticsearch API together in a container:
1. `$ cd search-api`<br/>`$ dep ensure`<br/><br/>
2. `$ docker-compose up -d --build`<br/><br/>
3. `$ curl -X POST http://localhost:8080/documents -d @data.json -H "Content-Type: application/json"`
