# MercedesBenz
Mercedes Benz online shopping selenium project 

Pre-requisites
Java 8
Maven
Eclipse

Implementation details:

Implemented MercedesBenz Onlineshop automation using selenium webdriver with java on windows(10) platform. Used TestNG framework and 
page object model design patterns. In order to support Page Object model, Page Factory is implemented using @Findby annotation. 

This project can be run in any windows system with out any changes as the build contains even the driver and configuration files.
Drivers for Chrome and IE browser included in build. Script can be run either using chrome or IE (firefox also, but driver is not
packed in the build)browser by updating the configuration file according to our requirement. Project could be imported to eclipse 
and executed by clicking mavan test(ProjectName->POM.xml->Maven Test). Flow of the execution can be checked in log file, 
final result can be seen in emailable testng report.
