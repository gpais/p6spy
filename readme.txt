https://www.ibm.com/developerworks/cn/java/j-lo-p6spy/index.html#artrelatedtopics

 The following describes the detailed operation of IronTrack SQL installation and use:
Download the IronTrack SQL package for installation;
The irontracksql.jar, p6spy.jar and log4j-1.2.8.jar into CLASSPATH, if the Web application is placed YourWebApp/WEB-INF/lib/in the directory;
Spy.properties into the CLASSPATHdirectory, if it is placed on a Web application YourWebApp/WEB-INF/classess/directory, attention is not lib/a directory;
Modify your program's database driver name driver name P6Spy the com.p6spy.engine.spy.P6SpyDriverother do not change;
Open the configuration file spy.properties file, find it realdriver, change its value to your application's real database driver name;
Set the listening port number monitorport=2000;
First run java -jar irontracksql.jarto start the IronTrack SQL;
Start your application or server again;
You can see