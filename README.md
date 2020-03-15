docker-compose up

mvn archetype:generate -DarchetypeGroupId=com.streamsets -DarchetypeArtifactId=streamsets-datacollector-stage-lib-tutorial -DarchetypeVersion=2.1.0.0 -DinteractiveMode=true

groupId: com.example
artifactId: samplestage
version: 1.0-SNAPSHOT
package: com.example


docker exec -it docker-hadoop_streamsets_1 bash

sudo cp -a /data/lib/. /opt/streamsets-datacollector-3.9.0/user-libs


sudo cp -a /data/lib/. /opt/streamsets-datacollector-3.9.0/streamsets-libs-extras

sudo cp -a /data/lib/. /opt/streamsets-datacollector-user-libs



find / -type d -name "user-libs"

docker restart docker-hadoop_streamsets_1