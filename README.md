###### Pact consumer driven contract testing with spring boot

**Docker Setup**
* Run docker-compose up command to get a running Pact Broker and a clean Postgres database.

**Pact Broker Usage**

Consumer
1. Execute `mvn test `for create pack json
2. Execute `mvn pact:publish` for publish to pact broker

Provider
1. Execute `mvn pact:verify` for pact verify

and all after visit to pact broker url. (exmp: localhost:80)