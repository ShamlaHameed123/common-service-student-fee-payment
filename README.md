# common-service-student-fee-payment

1. Navigate to common-services directory. Build the application by running ** mvn clean install** in pom.xml path of common-service
2. Once build is successful and .jar is created, then run **mvn install:install-file -Dfile=./target/common-services-0.0.1-SNAPSHOT.jar -DgroupId=rak.skiply -DartifactId=common-services -Dversion=0.0.1-SNAPSHOT -Dpackaging=jar**

   This service serves as the common-service for both student and fee payment service and is a pre-requisite for running both.
