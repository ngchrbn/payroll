# Payroll

A REST API built with Spring Boot

## Usage

## Launch the application

- Spring initializr uses maven wrapper so type this:
```shell
$ ./mvnw clean spring-boot:run
```
- Alternatively using your installed maven version type this:
```shell
$ mvn clean spring-boot:run
```
- When the app starts, we immediately interrogate it.
```shell
$ curl -v localhost:8080/employees
```
- Other endpoints can be found in [Employee endpoints](/src/main/java/payroll/EmployeeController.java) or [Order endpoints](/src/main/java/payroll/OrderController.java)

## Resource

- [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)