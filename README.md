# RMI-Calc-ServerandClient
# Server compute the addition, subtraction, multiplication and division Of a two integer and return result to client.

Use javac to compile all the java file i.e.
javac Calculator.java
javac CalculatorImpl.java
javac CalculatorServer.java
javac CalculatorClient.java


Use rmic to create stub and skeleton class file.
rmic CalculatorImpl


Start with RMIregistery 
> rmiregistery

start the server hosting the CalculatorService, and enter the following:
 > java CalculatorServer
It will load the implementation into memory and wait for a client connection.
start the client program.
 > java CalculatorClient

