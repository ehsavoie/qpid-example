**Very simple example of MDB listening on a remote destination hosted in on Apache Qpid.**

**Description**
 - This is a simple example of a MDB that listens on a remote destination hosted by a remote Apache Qpid Broker-J setup. The project uses Artemis Resource Adadapter to connect to remote queues and exteranl JNDI context to lookup all required resource in remote Apache Qpid instance.

**Requirements**

 - Apache Qpid Broker-J 8.0.0
 - WildFly 19.0 or greater

** Configuration **
 - Install the provider module untaring _qpid-provider.tar.gz_
 - Configure WildFly with _qpid.cli_ jboss-cli scipt file
 - Start Apache Qpid broker using the _initial-config.json_
 - Restart WildFly

** Run the example ** 
 - Deploy the MDB
 - Execute the HelloWorld client.