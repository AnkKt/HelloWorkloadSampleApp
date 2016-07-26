# HelloWorkloadApp

Welcome to the Hello Workload application!

This sample application demonstrates how to write a Hello World application leveraging the Workload Scheduler service and deploy it on Bluemix. This sample use our new REST api and it's ready to be deployed to Bluemix cloud platform.

# Application overview:
This application was realized using Maven, so we can find the pom.xml file with all the dependency and the plugin needed.
For this application we use two package:
  - src, which contains the source code of the app and the web content of the app
  - target, which contains the builded war file

# Src:

In src we found two folder: 
  - com 
  - webapp 
The first contains the java source code while the second contains the web resource of the app. Going deeper,  in webapp  we  have 
the page(index.jsp) that will be loaded once that the app will be launched. In the same folder, we have WEB-INF: here we can find 
the external library needed for the project and the web.xml descriptor. 

# Target
Here we found the result of the Maven build and, in particular, the WAR file. This WAR file is actually the application itself. It is the only file that is pushed to and run on the Bluemix cloud. Every time your application code is updated, you need to regenerate this WAR file and push it to Bluemix again

# Deploy to Bluemix

To begin, click Deploy to Bluemix and log in with your Bluemix credentials

[![Deploy to Bluemix](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/WAdev0/HelloWorkloadSampleApp) 

1. Select your region
2. Click Deploy
3. After been deployed, your app is bound to the Workload Scheduler service and ready to run



