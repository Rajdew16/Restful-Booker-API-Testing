
# Restful-Booker-API-Testing

This project is Api testing related which is done by me using tools like Rest Assured, Postman and this based on Java programming language.


## How To Run This Project

Step1 -> Clone the repository  
Step2 -> Open the project in Eclipse IDE  
Step3 -> Go to src/test/java/cucumber/options  
Step4 -> Select TestRunner.java file  
Step5 -> Right click -> run as -> JUnit test

## Running Project From Command Line

Open cmd at project level/path,

To run project, run the following command

```bash
  mvn test
```

To run project with tags, run the following command

```bash
  mvn test -Dcucumber.filter.tags="@Regression"
```

For create booking,

```bash
  mvn test -Dcucumber.filter.tags="@CreateBooking"
```

For update booking,

```bash
  mvn test -Dcucumber.filter.tags="@UpdateBooking"
```

For delete booking,

```bash
  mvn test -Dcucumber.filter.tags="@DeleteBooking"
```

## Maven Cucumber Report

For generating maven cucumber report, run following command in terminal at project level/path,

```bash
  mvn test verify
```

## Report

For report you can check on -> target/index.html
