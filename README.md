# PG2-SISOP
PG2 - sistemas operacionais II

alias java8=~/Downloads/openlogic-openjdk-8u262-b10-linux-64/bin/java

alias javac8=~/Downloads/openlogic-openjdk-8u262-b10-linux-64/bin/javac

run servidor: 
javac8 -cp "jersey-bundle-1.19.jar" webservice/*.java
java8 -cp ".:jersey-bundle-1.19.jar" webservice.Servidor
abrir no browser http://127.0.0.1:9000/calculadora/somarInt/2/3


run client:
javac8 -cp "jersey-bundle-1.19.jar" webservice/Cliente.java
java8 -cp ".:jersey-bundle-1.19.jar" webservice.Cliente
