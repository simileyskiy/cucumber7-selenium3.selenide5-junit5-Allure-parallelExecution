# cucumber7-selenium3.selenide5-junit5-Allure-parallelExecution
Project with the ability to run in parallel execution with the desired number of threads.
Set in junit-platform.properties

To run tests locally:

- Run CucumberTestRunner.java
- With command:
```
mvn install
```
There are 5 features in the src/test/resources folder, one of which is Login4Fails.feature with two unsuccessful tests, as a result of which a screenshot is taken after an unsuccessful step and added to the Allure report using Hook from src/main/hooks/Hook.java
## Особенности
Cucumber 7 + Selenium 3/Selenide 5 when running scripts/features in parallel, the number of Threads is controlled by specifying in:
- junit-platform.properties



### Building report locally
To start the allure server and view the report:
```
mvn allure:serve
```

Run in 4 Threads Example

![image](https://user-images.githubusercontent.com/43063004/204404483-af07f6c1-f2b6-41e7-8c11-e8c2db9ba620.png)




# cucumber7-selenium3.selenide5-junit5-Allure-parallelExecution
Проект сборки с возможностью паралельного запуска с желаемым количеством Threads.
Регулируется в junit-platform.properties

Для локального запуска тестов необходимо:

- Запустить ранер CucumberTestRunner.java
- С помощью команды: 
```
mvn install
```
В папке src/test/resources находятся 5 фич, одна из которых Login4Fails.feature с двумя неуспешными тестами, по итогу которых, делается скриншот после неудачного шага и добавляется в отчет Allure, с помощью Hook'а из src/main/hooks/Hook.java
## Особенности
Cucumber 7 + Selenium 3/Selenide 5 при параллельном запуске сценариев\фич количество Threads управляется с помощью указания в:
- junit-platform.properties



### Сборка отчета локально
Для запуска allure сервера и просмотра отчета:
```
mvn allure:serve
```

Прогон в 4 Threads

![image](https://user-images.githubusercontent.com/43063004/204404483-af07f6c1-f2b6-41e7-8c11-e8c2db9ba620.png)

