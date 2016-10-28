# HelloWorkloadApp

Welcome to the Hello Workload application!

This sample application demonstrates how to write a Hello World application leveraging the Workload Scheduler service and deploy it to Bluemix. This sample uses our new REST APIs and it is ready for deploying to the Bluemix cloud platform.

# Deploy to Bluemix

To begin, click Deploy to Bluemix and log in with your Bluemix credentials

[![Deploy to Bluemix](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/WAdev0/HelloWorkloadSampleApp) 

1. Select your region.
2. Click Deploy.
3. After having been deployed, your app is bound to the Workload Scheduler service and ready to run.


# Application overview:
This application is written in Java using Maven, so you can find the pom.xml file with all the required dependencies and the plugin.
In this application we use two folders:
  - src, which contains the source code of the app and the web content of the app
  - target, which contains the built war file

Src:

In src two folder are available: 
  - com 
  - webapp  
  
The first folder contains the java source code and the second contains the web resource of the app. The lower-level webapp folder contains
the page (index.jsp) that will be loaded when the app is launched. In the same folder is located the WEB-INF folder, containing  
the external library required for the project and the web.xml descriptor. 

Target:

This folder contains the result of the Maven build and, in particular, the WAR file. This WAR file is the application itself. It is the only file that is pushed to and ran on the Bluemix cloud. Every time your application code is updated, regenerate the WAR file and push it to Bluemix again





