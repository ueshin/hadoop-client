Hadoop Client
=============

Maven POM project for developing Hadoop clients.


How to use
----------

Configure `parent` and `repository` in the pom.xml file.

    <parent>
		<groupId>st.happy_camper.hadoop</groupId>
		<artifactId>hadoop-client</artifactId>
		<version>cdh3u3-1</version>
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

- org.apache.hadoop : hadoop-core : 0.20.2-cdh3u3
- org.apache.hadoop : hadoop-test : 0.20.2-cdh3u3
- org.apache.hadoop : hadoop-mrunit : 0.20.2-cdh3u3
- org.apache.zookeeper : zookeeper : 3.3.4-cdh3u3
- org.apache.hbase : hbase : 0.90.4-cdh3u3
- org.apache.mahout : mahout-core : 0.5-cdh3u3
- com.cloudera : flume-core : 0.9.4-cdh3u3


License
-------

Apache License, Version 2.0


Author
------

Takuya UESHIN (ueshin@happy-camper.st) 
