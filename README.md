# Simple Calculator - Introduction to Behavior Driven Development


This project is a quick start for anyone is interested in learning how to create Specficiation by Example scenarios using the Cucumber framework and a simplar calculator application.

There are two main branches in this git repo that should be used for this workshop.

`Solution:` This branch contains an application that has all steps implemented and tests passing, as well as some additional scenarios for multiplcation and division.

`Stubbed:` This branch will have a few base scenarios for addition and subtraction, but nothing else.

## Set up:

In order to run this codebase, the following must be installed:

- **Java:**
  - This project was built using Java 13.0.2.
  - Confirm that Java is correctly installed by running `java -version`.
  - Set your JAVA_HOME by editing with `vim ~/.bash_profile` and adding `export JAVA_HOME=$(/usr/libexec/java_home)`.

- **Maven:**
  - This project was built using Apache Maven 3.6.3.
  - Confirm that Maven is installed by running `mvn -version`.
    - If not installed, you can install with [Homebrew](https://brew.sh/) using `brew install maven`.
  - Add the Maven bin directory to your path so you can run the "mvn" command.

- **Red Hat Developer Studio (or some Java IDE)**
  - Optional Step: Install the Cucumber Eclipse Plugin: https://cucumber.github.io/cucumber-eclipse/

To confirm that the project builds correctly, navigate to the project and run `mvn clean install`.

If you are in the `Solution` branch: This should display `Build Success` as the final status and show that a total of 24 tests ran, with 0 failures.

If you are in the `Stubbed` branch: You will have build failures. Resolve these failures by running `CalculatorScenarioRunnerTest` as a `JUnit` test and following the stack traces.

For the purposes of learning BDD, start by checking out the Stubbed branch.

**_If you will be attneding this as a workshop, we will walk through how to fix the Stubbed branch.**
