How to setup ActiveMQ

 Download ActiveMQ from Download ActiveMQ
 Extract the ActiveMQ downloaded zip file to any location in your computer.
 Open command prompt and go to the bin directory of extracted activemq folder.
 Type activemq.bat start, to start activemq.
 
 
 You can also try to open ActiveMQ console using the link “http://localhost:8161/admin/” 
 with ‘admin’/’admin’ as username and password. It should open as below.
 
 
 

How to RUN
 
In the eclipse Right Click on MessageSender.java -> Run As->Java Application to see if our message is sent to the queue.
The Hello message after being successfully sent to the queue gets printed in eclipse output console.
 
We can also check our ActiveMQ console->Queues tab, 
to see the number of pending messages in our queue after running the MessageSender.java


In the eclipse Right Click on MessageReceiver.java -> Run As->Java Application to see if our message is received from the queue.
The hello message after being successfully received gets printed in eclipse output console.