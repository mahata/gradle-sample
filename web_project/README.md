## How I started this project:

```
gradle init --type java-library
```

## How you run Tomcat:

```
gradle tomcatRunWar  # or gradle tRW
```

It'll do followings:

* Download dependent libraries
* Build and packaging (create the war file)
* Run Tomcat
* Deploy the war file to the Tomcat

You'll be able to access the application with:

* http://localhost:8080/web_project/
* http://localhost:8080/web_project/hello

## How to create the war file

Following command will create the war file under `build/libs`.

```
gradle war
```
