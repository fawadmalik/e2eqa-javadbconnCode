# e2eqa-javadbconnCode
How to run from command-line using maven:
```
C:\dev\eclipse-workspace\e2eqa-javadbconnCode>mvn exec:java -Dexec.mainClass="com.e2eqa.javadbconnCode.Main"

[INFO] Scanning for projects...
[INFO]
[INFO] -----------< com.e2eqa.javadbconnCode:e2eqa-javadbconnCode >------------
[INFO] Building e2eqa-javadbconnCode 1.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO]
[INFO] --- exec-maven-plugin:1.6.0:java (default-cli) @ e2eqa-javadbconnCode ---

Loading class `com.mysql.jdbc.Driver`. This is deprecated. The new driver class is `com.mysql.cj.jdbc.Driver'. The driver is automatically registered via the SPI and manual loading of the driver class is generally unnecessary.
Connection successful

C:\dev\eclipse-workspace\e2eqa-javadbconnCode>
```