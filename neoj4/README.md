# Setting up

 sudo apt-get update && sudo apt-get install -y openjdk-21-jre-headless

 wget https://dist.neo4j.org/neo4j-community-5.26.0-unix.tar.gz
 
 tar xzf neo4j-community-5.26.0-unix.tar.gz && cd neo4j-community-5.26.0

 ./bin/neo4j-admin dbms set-initial-password admin@123
 
 ./bin/neo4j start
 
./bin/cypher-shell -u neo4j -p admin@123 -f ../schema.cypher

./bin/cypher-shell -u neo4j -p admin@123 -f ../graph.cypher
