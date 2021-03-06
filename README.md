  
## Servlet & JSP example
This is simple example of servlet & jsp technologies.
If you want to run this example, please perform steps below:

1. Download [demo project](https://github.com/dgroup/Servlets_demo/archive/master.zip);
2. Install [JDK 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html);
2. Install [gradle](https://www.gradle.org/downloads). For **Linux OS** you can use this [guide](https://github.com/dgroup/Servlets_demo/wiki/%5BOS-Linux-Ubuntu%5D-Java-&-Gradle-installation-notes); 
3. Call `run.bat`. The output is:
![alt tag](https://raw.github.com/dgroup/Servlets_demo/master/img/server_out.png)
4. Browser: [http://localhost:8080/Servlets_demo](http://localhost:8080/Servlets_demo)
![alt tag](https://raw.github.com/dgroup/Servlets_demo/master/img/screen_1.png)
![alt tag](https://raw.github.com/dgroup/Servlets_demo/master/img/screen_2.png)

## Quick tech overview
- Pure Servlet 2.5 & JSP;
- Gradle (build system) 
- Jetty (web server). Integrated with `Gradle` via `jetty` plugin;
- H2 (in-memory database). Integrated with `Gradle` via `flyway` plugin;
- PMD (code quality validation). Integrated with `Gradle` via `pmd` plugin;
- Bootstrap (css layouts);
- jQuery ver.`1.11.1`. 

Have a fun.
