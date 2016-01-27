# SSL
[![Build Status](https://travis-ci.org/KimBoWoon/SSL.svg?branch=master)](https://travis-ci.org/KimBoWoon/SSL)

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
java -Djavax.net.ssl.keyStore=name -Djavax.net.ssl.keyStorePassword=password SSL_EchoServer
java -Djavax.net.ssl.trustStore=name SSL_EchoClient
```
