
.PHONY: build

all: build

build:
	mvn clean install -DminimalBuild -Dlicensing.skip=true
	cp target/neo4j-cypher-compiler-2.1-2.1.6-SNAPSHOT.jar /home/developer/Downloads/neo4j-community-2.1.5/lib/neo4j-cypher-compiler-2.1-2.1.5.jar