
build jar
```bash
 mvn clean package
```

run jar

```bash
java -jar target/xxvvv-1.0-SNAPSHOT.jar --server.address=127.0.0.1 --server.port=7788 
```

test running
```bash
curl -i 127.0.0.1:7788
```

