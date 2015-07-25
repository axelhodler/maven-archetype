# Personalized maven archetype
Includes some testing libraries (hamcrest, junit) and an initial gitignore

Taken from [maven-archetype-quickstart](http://svn.apache.org/viewvc/maven/archetypes/trunk/maven-archetype-quickstart/)

## Install to your local maven archetype catalog
    mvn install

## Usage
    mvn archetype:generate \
    -DarchetypeGroupId=co.hodler \
    -DarchetypeArtifactId=maven-archetype-quickstart-xor

## Naming
* Unit test files have to end with `Test`
* Integration test files have to end with `IT`

## Run unit tests
    mvn test

## Run all tests
    mvn verify
