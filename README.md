Create queue using activemq (the jms connector represents the activemq settings).

Install ActiveMQ from http://activemq.apache.org/
goto ${ACTIVEMQ}/bin
activemq start
http://localhost:8161/
login with activemq/activemq

create a test queue with name : TestQueue
Once your queue is created

You are all set to run the mule application, if you are using anypoint studio 7.3
The console will be visible at bottom left. 

However for knowledge purpose the RAML provides you the API lead rules:

This is a simple application which listens to HTTP post with BODY (The API spec can be obtained at http://localhost:8081/console/)
