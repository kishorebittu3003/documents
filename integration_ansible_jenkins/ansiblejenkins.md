### Integration ansible with jenkins
------------------------------------
#### Deploying Tomcat application and integrating with jenkins
--------------------------------------------------------------
* for Deploying Tomcat application we must install java 11 application 
* Creating Tomcat user as per documentation
* Creating home directory for /opt/Tomcat 
* Taking tar file from Website for wildfly ( 'https://dlcdn.apache.org/Tomcat/Tomcat-10/v10.1.5/bin/apache-Tomcat-10.1.5.tar.gz')
* Extracting Tarfile  apache-Tomcat-10.1.5.tar.gz
* Creating a Soft link for Tomcat that means Symbolic link
* Recusrsively Changing Ownership Of the Tomcathome Directory
* giving executable permissions files in shell file by using file globe loops and we can also use command module to creating
* copying tomcat service file as i used jinja2 template
* reloading the daemon to restart service of tomcat
* copying files of users.xml
* copying files of manager.xml
* copying files of host-manager.xml
* 
* 

  


