
# in spark-without-hive:
./gradlew publish 

# launch local repo in project root:
php -S 0.0.0.0:7171 -t repo


# test using sample-client
mvn clean dependency:unpack 

# change pom.xml to use localhost:7171 in itests/pom.xml


