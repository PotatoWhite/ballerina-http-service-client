# build server
```shell
❯ bal build ./hello_service.bal
Compiling source
        hello_service.bal

Generating executable
        hello_service.jar
```

# build client
```shell
❯ bal build ./hello_client.bal
Compiling source
        hello_client.bal

Generating executable
        hello_client.jar
```

# test - run server
```shell
❯ java -jar hello_service.jar
[ballerina/http] started HTTP/WS listener 0.0.0.0:9090
```

# test - run client
```shell
❯ java -jar hello_client.jar
Hello World!
```