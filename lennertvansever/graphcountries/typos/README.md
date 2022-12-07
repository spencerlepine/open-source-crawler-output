## Detected Typos Diff
```diff
--- ./blog/How to transform a rest service to a graph service.md	original
+++ ./blog/How to transform a rest service to a graph service.md	fixed
@@ -187 +187 @@
-On the oposite side, Arab speaking countries always have a bordering country that also have Arab as an official language if you exclude the island nations of Bahrain and the Comores.
+On the opposite side, Arab speaking countries always have a bordering country that also have Arab as an official language if you exclude the island nations of Bahrain and the Comores.
--- ./README.md	original
+++ ./README.md	fixed
@@ -50 +50 @@
-The data from [restcountries.eu](https://restcountries.eu/) is scraped with a JS script and inserted into a Neo4j graph database. Afterwards the GraphQL schema is automagically infered by the awesome [neo4j-graphql-js](https://github.com/neo4j-graphql/neo4j-graphql-js) package. We add some custom cypher queries to the schema to make the shortest path and distance data possible. Finally an Apollo server is used to create the GraphQL endpoint and playground.
+The data from [restcountries.eu](https://restcountries.eu/) is scraped with a JS script and inserted into a Neo4j graph database. Afterwards the GraphQL schema is automagically inferred by the awesome [neo4j-graphql-js](https://github.com/neo4j-graphql/neo4j-graphql-js) package. We add some custom cypher queries to the schema to make the shortest path and distance data possible. Finally an Apollo server is used to create the GraphQL endpoint and playground.
@@ -74 +74 @@
-4. Populate the Neo4j graph database, run `npm run dataScraping`. When this command is done, you will get an infered schema file in the graphql repo, you can use this to optionally change the main schema.graphql file in the same repo
+4. Populate the Neo4j graph database, run `npm run dataScraping`. When this command is done, you will get an inferred schema file in the graphql repo, you can use this to optionally change the main schema.graphql file in the same repo
--- ./scratchBook.cypher	original
+++ ./scratchBook.cypher	fixed
@@ -14 +14 @@
-// languages ordered by prevelance in countries
+// languages ordered by prevalence in countries
