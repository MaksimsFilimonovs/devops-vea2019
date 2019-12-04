#### Commands executed for checkstyle linter: (checkstyle.org)

**Main.java**
`java -jar checkstyle-8.27-all.jar -c google_checks.xml -o ./results/googlechecks_main.log C:\Users\Admistrator\Documents\Eclipse-workspace\DevOpsHW\src\main\java\main\Main.java`

`java -jar checkstyle-8.27-all.jar -c sun_checks.xml -o ./results/sunchecks_main.log C:\Users\Admistrator\Documents\Eclipse-workspace\DevOpsHW\src\main\java\main\Main.java`

**PropertyLoader.java**
`java -jar checkstyle-8.27-all.jar -c google_checks.xml -o ./results/googlechecks_propertyloader.log C:\Users\Admistrator\Documents\Eclipse-workspace\DevOpsHW\src\main\java\utils\PropertyLoader.java`

`java -jar checkstyle-8.27-all.jar -c sun_checks.xml -o ./results/sunchecks_propertyloader.log C:\Users\Admistrator\Documents\Eclipse-workspace\DevOpsHW\src\main\java\utils\PropertyLoader.java`

Result .log files are located in /results folder.

#### Repository for code that was tested & contains .properties file loader:
https://github.com/fuzzysearch404/DevOpsHomeWorkThing

#### The actual commit for .properties file loader:
https://github.com/fuzzysearch404/DevOpsHomeWorkThing/commit/482c3fe7432a0048a427e401fdddd0639d83c21d
