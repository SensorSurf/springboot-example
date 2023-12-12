# springboot-example

This project exists to demo our product, Technician. Technician can automatically repair your code after a runtime exception is logged to Splunk, New Relic, or even a Slack channel. We are starting with Java projects.

## Running this springboot application

1. Ensure Java 17+ and Maven are installed on your machine.
2. Clone this repository.
3. Run `mvn clean install`.
4. Run `java -jar target/*.jar`.

## Sample requests

* Create Student: `curl --location --request POST 'localhost:8080/students --header 'Content-Type: application/json' --data-raw '{ "name": "Alec", "passportNumber": "US70081" }'`
* Get Student: `curl --location --request GET 'localhost:8080/students/1'`
* List Students: `curl --location --request GET 'localhost:8080/students'`

