Perform the following steps to download and install the latest version of APIman and start the server:

Download WildFly application server.
Patch the application server with a zip file to add modules and web applications which are the UI of APIMan.
Note: If you have already downloaded and installed WildFly 10, download the Apiman overlay zip file: http://downloads.jboss.org/apiman/1.2.6.Final/apiman-distro-wildfly10-1.2.6.Final-overlay.zip.

Use the following command:

$ unzip apiman-distro-wildfly10-1.2.6.Final-overlay.zip -d wildfly-10.0.0.Final

Start APIman using the following commands:
$ cd wildfly-10.0.0.Final/bin

$ ./standalone.sh -c standalone-apiman.xml
