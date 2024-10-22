# Basic example of Spring Cloud

start - This directory contains basic Boot apps that are modified to use Spring Cloud
config - This is configuration from Eureka, Config Server, and Zipkin used by the Spring Cloud CLI

Prereqs
Before you run the applications in this repository you should install the Spring Cloud CLI.

About The Apps
There are three apps in the start and four apps in the complete directories.

Name App
The name app will return the value of the name property when making an HTTP GET request to /.

Greeting App
The greetingapp returns a greeting. You can make a GET request to / and it will return Hello. You can also make an HTTP GET and pass a language code to return a greeting for that language. For example a GET to /es would return Hola.

Web App
The web app makes a request to both the greeting and name app to construct the proper greeting when you make a GET to /. By changing the Accept-Language header you can change the language of the greeting returned. For example if you set the Accept-Language header to de the greeting returned will be Hallo Javed.
