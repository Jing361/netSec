default:all

all:Homework.class

Homework.class:Homework.java ActiveClient.class Server.class
	javac Homework.java

ActiveClient.class:ActiveClient.java MessageParser.class
	javac ActiveClient.java

Server.class:Server.java
	javac Server.java

MessageParser.class:MessageParser.java
	javac MessageParser.java

clean:
	rm *.class

