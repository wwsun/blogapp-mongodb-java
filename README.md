MongoDB-Java Blog Demo
================

###Prerequisties
To build the MongoDB-Java Blog application, you'll need to have the follingL:

- JDK 1.7 (1.8 is not recommended)
- Maven
- Spark-java
- freemarker

###Download the project

	git clone https://github.com/wwsun/sun-mongodb-blog.git

###Building

To build the MongoDB-Java demo application use Maven:

	$ mvn package

This will build the demo application and place all of the dependencies in `target/lib`. If instead you want to build a single jar with all of the the dependencies, execute the `assembly:single` Maven goal:

	$ mvn compile assembly:single

###Running
	
	$ cd YOUR-PROJECT-FOLDER
	$ mvn compile exec:java -Dexec.mainClass=course.BlogController

###Notes

- Intellij IDEA 14 is recommended as your IDE
- All source codes comes from the course M101J, which is one of the open course of MongoDB University
- For more information: contact me at [this page](http://weibo.com/swwol).