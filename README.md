Hadoop Client
=============

Maven POM project for developing Hadoop clients.


How to use
----------

Configure `parent` and `repository` in the pom.xml file.

    <parent>
		<groupId>st.happy_camper.hadoop</groupId>
		<artifactId>hadoop-client</artifactId>
		<version>0.1.0</version>
	</parent>

	<repositories>
		<repository>
			<id>hadoop-client-releases</id>
			<name>hadoop-client releases</name>
			<url>http://ueshin.github.com/hadoop-client/releases</url>
		</repository>
	</repositories>

Add needed libraries to `dependencies`.

	<dependencies>
		<dependency>
			<groupId>org.apache.hbase</groupId>
			<artifactId>hbase</artifactId>
		</dependency>
	</dependencies>

Now available libraries are as follows:

- org.apache.hadoop : hadoop-core : 1.0.0
- org.apache.hadoop : hadoop-test : 1.0.0
- org.apache.hbase : hbase : 0.92.0
- org.apache.hbase : hbase : tests : 0.92.0


License
-------

Apache License, Version 2.0


Author
------

Takuya UESHIN (ueshin@happy-camper.st) 
