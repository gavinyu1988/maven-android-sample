maven-android-sample
====================

This is an android HelloWorld project created by maven

The sample app can be run after the avd is start up by using the commands:
mvn clean package android:deploy android:run

To use Android Lint check the code quality and generate report at sonar, use the following commands:
mvn clean install -Dsonar.profile="Android Lint" sonar:sonar