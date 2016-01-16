# SSL
SSL HomeWork

# Key Generator
```
keytool -genkey -keystore name -keyalg RSA
Keytool -export -keystore name -file filename
keytool -import -keystore name -file filename
```

# Compile
```
javac SSL_EchoServer
javac SSL_EchoClient
```

# Execution
```
java -Djavax.net.ssl.keyStore=hw2key -Djavax.net.ssl.keyStorePassword=123456 SSL_EchoServer
java -Djavax.net.ssl.trustStore=hw2key SSL_EchoClient
```
