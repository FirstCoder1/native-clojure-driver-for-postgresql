native-clojure-driver-for-postgresql


Clojure-native async non-jdbc driver for postgresql - no middleware abstractions

* async (netty)
* support all datatypes (arrays, custom types)
* connection pool
* data dsl for queries (aka honeysql)
* logical replication / notifications
* jsonb as first class (jsquery/json-knife)
* extensibility
* rest api (aka postgrest?)


## Dev

```sh

docker run --name pg10 -p 5555:5432 -e POSTGRES_PASSWORD=pass -d postgres:10

lein repl

```