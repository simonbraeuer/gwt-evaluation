# gwt-evaluation

Evaluation of new gwt version 2.8 (SNAPSHOT from 22.10.2015)

This example shows how to evaluate gwt version 2.8.0. 

Technology stack:
- Version: Mars.1 Release (4.5.1) Build id: 20150924-1200
- gwt version 2.8 (SNAPSHOT from 22.10.2015)
- apache-maven-3.1.1

Steps:
- copy folder "eval" (subfolder of maven) into your local maven repository
- use folder "gwt-2.8.0-SNAPSHOT" (subfolder of eclipse)as your local gwt repository in eclipse
- then use following dependencies in pom file

		dependency>
			<groupId>eval.com.google.gwt</groupId>
			<artifactId>gwt-user</artifactId>
			<version>2.8.0</version>
		</dependency>
		<dependency>
			<groupId>eval.com.google.gwt</groupId>
			<artifactId>gwt-dev</artifactId>
			<version>2.8.0</version>
		</dependency>
		<dependency>
			<groupId>eval.com.google.gwt</groupId>
			<artifactId>gwt-codeserver</artifactId>
			<version>2.8.0</version>
		</dependency>
		<dependency>
			<groupId>eval.com.google.gwt</groupId>
			<artifactId>gwt-servlet</artifactId>
			<version>2.8.0</version>
		</dependency>
		<dependency>
			<groupId>eval.com.google.gwt</groupId>
			<artifactId>gwt-elemental</artifactId>
			<version>2.8.0</version>
		</dependency>
