# SpringBoot-Unit-Integration-Test

mvn clean install

mvn spring-boot:run

to run spring boot- dev from command-line : mvn spring-boot:run -Pdev

Running Unit and Integration Tests through Maven commands
1.Run the spring project fro one command-line : mvn spring-boot:run  or mvn spring-boot:run -Pdev
2. Open another command-line without closing the first one
3. To run unit-tests : mvn test     (Note: not need running server for unit tests)
4. To run integration test : mvn failsafe:integration-test     (failsafe is a plug-in that should be in the pom.xml)
5. To run unit and integration tests with one command : mvn integration-test

