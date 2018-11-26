# hf-api-test-bdd

### Prerequisites:
> - Java 1.8
> - Maven
> - Git

### Execute hf-api-test-bdd via Commandline:
> - Clone the hf-api-test-bdd project from git. 
>   Command: ```git clone https://github.com/enilanthi/hf-api-test-bdd.git```
> - Move to hf-api-test-bdd root directory. ```cd hf-api-test-bdd```
> - Simply trigger the execution using ```mvn clean verify``` command

#### Additional Information:
> - User friendly output will be generated on the console during the execution
> - A comprehensive html report will be generated under: ```hf-api-test-bdd\target\site\cucumber-reports\cucumber-html-reports```. Note: You can open the report by clicking on "overview-features.html"

### Assignment Criteria and Status
- [x] Get all countries and validate that US, DE and GB were returned in the response
- [x] Get each country (US, DE and GB) individually and validate the response
- [x] Try to get information for inexistent countries and validate the response
- [x] This API has not a POST method at the moment, but it is being developed. Write a test that would validate new country addition using POST

### Third Party Library Usage
- ```Unit test runner - junit 4.12```
- ```Testing and validating REST services -rest-assured 3.0.0```
- ```Easily create matchers - org.hamcrest 2.0.0.0```
- ```BDD support - info.cukes 1.2.5```
- ```JSON extraction - com.google.code.gson 2.8.5```
- ```Generate comprehensive html test report - net.masterthought 3.20.0```
