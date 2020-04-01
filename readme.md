### Install HBase

docker run --name=hbase-docker -d -p 8080:8080 dajobe/hbase

### To access the console

docker exec -it hbase-docker sh
... when you get prompted into the container run the following command:
hbase shell
