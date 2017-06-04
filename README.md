



Java Selenium Framework

 Setup
* Java SDK 7
* Eclipse Luna
* Eclipse Plugins
  * Gradle Integration for Eclipse http://dist.springsource.com/milestone/TOOLS/gradle
 
Eclipse Setup
* Open Eclipse Luna 
* Install Plugin - Gradle Integration for Eclipse http://dist.springsource.com/milestone/TOOLS/gradle
* Restart Eclipse
* click on File -> Import -> Gradle Project
* Choose the checkout directory
* Click on "Build Model" then you will see the project in the list below, select that and click "Finish"



## Steps

* Checkout the project
* Close all Browser Windows
* On Linux/Mac run $>./gradlew cucumber
* on Windows run cmd>gradlew.bat cucumber

This should start a new Browser window, shows Google Text Search and Image Search for keyword "facebook".
The Text Search uses Selenium and the Image Search uses Sikuli.

## 