
# in spark-without-hive:
gradle publish 

# launch local repo in project root:
php -S 0.0.0.0:7171 -t repo

# change pom.xml to use localhost:7171 in itests/pom.xml

