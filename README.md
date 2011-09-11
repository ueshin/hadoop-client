Hadoop Client
=============

Maven POM project for developing Hadoop clients.


How to use
----------

POMファイルに`parent`と`repository`を設定する。

    <parent>
		<groupId>st.happy_camper.hadoop</groupId>
		<artifactId>hadoop-client</artifactId>
		<version>cdh3u1-4</version>
	</parent>

	<repositories>
		<repository>
			<id>hadoop-client-releases</id>
			<name>hadoop-client releases</name>
			<url>http://ueshin.github.com/hadoop-client/releases</url>
		</repository>
	</repositories>

必要なライブラリを`dependencies`に加える。

	<dependencies>
		<dependency>
			<groupId>org.apache.hadoop</groupId>
			<artifactId>hadoop-core</artifactId>
		</dependency>
	</dependencies>

現在利用出来るライブラリは次の通り。

- org.apache.hadoop : hadoop-core : 0.20.2-cdh3u1
- org.apache.hadoop : hadoop-test : 0.20.2-cdh3u1
- org.apache.hadoop : hadoop-mrunit : 0.20.2-cdh3u1
- org.apache.zookeeper : zookeeper : 3.3.3-cdh3u1
- org.apache.hbase : hbase : 0.90.3-cdh3u1
- com.cloudera : flume-core : 0.9.4-cdh3u1


License
-------

Apache License, Version 2.0


Author
------

Takuya UESHIN (ueshin@happy-camper.st) 
