Hadoop Client in Scala
======================

Maven POM project for developing Hadoop clients in Scala.


How to use
----------

POMファイルに`parent`と`repository`を設定する。

    <parent>
		<groupId>st.happy_camper.hadoop</groupId>
		<artifactId>hadoop-client-scala</artifactId>
		<version>cdh3u1-4</version>
	</parent>

	<repositories>
		<repository>
			<id>hadoop-client-releases</id>
			<name>hadoop-client releases</name>
			<url>http://ueshin.github.com/hadoop-client/releases</url>
		</repository>
	</repositories>


License
-------

Apache License, Version 2.0


Author
------

Takuya UESHIN (ueshin@happy-camper.st) 
