# MyShoppingList-App-Phonegap


Buy list design with Add / Remove function for mobile devices.

Apache Cordova is an open source mobile development framework. It allows you to use standard web technologies - HTML5, CSS3 and JavaScript for multi-platform development. Applications run within containers targeted to each platform, and rely on compatible standard API connections to access the capabilities of each device, such as sensors, data, network status, and others according to Foundation (2015).

This framework is recommended when a developer has the following goals for their application:

• Create a mobile application compatible with several platforms, without having to create an application coded with the programming language native to each platform, for example: Android, IOs, Windows Phone.

• Make your app available in several application web stores, eg Google Play, Apple Store, etc.

• Use a mix of native platform components with WebView components (browser window), or develop some plug-in for communication of these components.

Applications that use PhoneGap become applications that are compatible with the platform and SDKs you want, and can be made available for store installation of each smartphone. When using the PhoneGap APIs, an application can be built without any native code (Java, Objective-C, C #, among others) of the platform being made available. Instead, Web technologies are used, and they are hosted on the device locally, the code is compiled next to the native code, dispensing with the need for a remote HTTP server to host the web code, according to Júnior, Oliveira and Junior (2015) .

According to Foundation (2015), an application encoded using the Apache Cordova platform will rarely be as fast as a native language encoded application on the mobile device platform, since native code has direct access to device hardware. In addition, a hybrid application or web mobile can not always use all the hardware features of the mobile device, such as: camera, accelerometer, among others, because to use these features you need to use plug-ins Which make the bridge of communication, which may or may not be found depending on its specificity.

In this lab / repository follows the code of a Shopping List with the Add / Remove functions.

This lab is a basic level, integrating the technologies of the Phonegap and AngularJS frameworks.

To install the Phonegap / Apache Cordova framework, follow the command for the Linux terminal:

# NodeJS Installation:

Curl -sL https://deb.nodesource.com/setup_7.x | Sudo -E bash -; Sudo apt-get install -y nodejs;

#Phonegap and libs for Android:

Sudo npm install -g phonegap; Sudo apt-get install ia32-libs;

Follow the commands below to develop the project: Obs1: when running "phonegap serves" the App is already available to access in the browser of the mobile device or notebook. Obs2: After creating the projects, the commands must be executed within the project directory.

Here is the list of commands to run on the Linux terminal:

1- Creating project: phonegap create PhonegapProject io.phonegap.hello PhonegapApp

2 - Adding Platform: phonegap platform add android phonegap platform add ios phonegap platform add windows

3- Provide service: phonegap serves

REFERENCES:

FOUNDATION, T. A. S. Cordova Documentation. 2015. Cordova Documentation. Disponível em: <https://cordova.apache.org/docs/en/latest/guide/overview/index.html>. Acesso em: 13 jul. 2016.


JÚNIOR, G. d. P. S.; OLIVEIRA, A. C.; JÙNIOR, E. A. L. Aplicação multiplataforma da realidade aumentada móvel para geolocalização utilizando o phonegap. Programa de Pós-Graduação em Engenharia Elétrica. Universidade Federal de Uberlância. Uberlândia/MG, sd, 2015. .

