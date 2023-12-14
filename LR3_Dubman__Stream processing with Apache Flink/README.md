# LR3_Dubman__Stream processing with Apache Flink

# Задание и набор данных

Выполнить следующие задания из набора заданий репозитория https://github.com/ververica/flink-training-exercises:
- RideCleanisingExercise;
- RidesAndFaresExercise;
- HourlyTipsExerxise;
- ExpiringStateExercise;

Решения могут быть выполнены на двух языках: Java или Scala. Каждому заданию соответствует .java или .scala файл с шаблоном решения и файл с тестом решения. Тесты расположены в папке test.
Для выполнения заданий вам потребуется датасет с данными о поездках такси в Нью-Йорке https://github.com/apache/flink-training/blob/master/README.md#using-the-taxi-data-streams. Файлы nycTaxiFares.gz и nycTaxiRides.gz вы можете найти в папке data https://gitlab.com/ssau.tk.courses/big_data/-/tree/master/data.

# Реализация: 

Задания были выполнены на языке Scala. Перед выполнением заданий были указаны пути к данным в файле [ExerciseBase.java](https://github.com/Won20/Big-Data/blob/main/LR3_Dubman__Stream%20processing%20with%20Apache%20Flink/flink-training-exercises/src/main/java/com/ververica/flinktraining/exercises/datastream_java/utils/ExerciseBase.java):
![image](https://github.com/Won20/Big-Data/assets/102918065/9ee2c94e-2d84-48fe-a6fe-9d1d1fef5755)

## RideCleanisingExercise
В [файл с заданием](https://github.com/Won20/Big-Data/blob/main/LR3_Dubman__Stream%20processing%20with%20Apache%20Flink/flink-training-exercises/src/main/scala/com/ververica/flinktraining/exercises/datastream_scala/basics/RideCleansingExercise.scala) было добавлено следующее решение: 
![image](https://github.com/Won20/Big-Data/assets/102918065/408f33cb-4bb7-47ab-8680-c19d85e06591)

## RidesAndFaresExercise
В [файл с заданием](https://github.com/Won20/Big-Data/blob/main/LR3_Dubman__Stream%20processing%20with%20Apache%20Flink/flink-training-exercises/src/main/scala/com/ververica/flinktraining/exercises/datastream_scala/state/RidesAndFaresExercise.scala) было добавлено следующее решение:
![image](https://github.com/Won20/Big-Data/assets/102918065/1ca8b338-7f45-4c0b-b81e-4c7023b4ad9e)
![image](https://github.com/Won20/Big-Data/assets/102918065/9ff77ef5-8c3c-4740-8b2d-2419ed8f17e8)

## HourlyTipsExerxise
В [файл с заданием](https://github.com/Won20/Big-Data/blob/main/LR3_Dubman__Stream%20processing%20with%20Apache%20Flink/flink-training-exercises/src/main/scala/com/ververica/flinktraining/exercises/datastream_scala/windows/HourlyTipsExercise.scala) был написан класс:
![image](https://github.com/Won20/Big-Data/assets/102918065/fccba133-278a-40f7-ad8d-e269c4fc1086)

В метод main был добавлен следующий код решения:
![image](https://github.com/Won20/Big-Data/assets/102918065/2cbbfb33-ab52-4305-a805-310936bcc85b)

## ExpiringStateExercise
В [файл с заданием](https://github.com/Won20/Big-Data/blob/main/LR3_Dubman__Stream%20processing%20with%20Apache%20Flink/flink-training-exercises/src/main/scala/com/ververica/flinktraining/exercises/datastream_scala/process/ExpiringStateExercise.scala) был написан класс:
![image](https://github.com/Won20/Big-Data/assets/102918065/8898d5d7-dace-42cd-a8af-9625afcf5769)

# Тесты:

## RideCleanisingScalaTest
![image](https://github.com/Won20/Big-Data/assets/102918065/43f34e38-93fb-4edd-8d42-65fef93493a0)

## RidesAndFaresScalaTest
![image](https://github.com/Won20/Big-Data/assets/102918065/77c4712b-d9a5-4646-8ec9-1f0dc2f687c9)

## HourlyTipsScalaTest
![image](https://github.com/Won20/Big-Data/assets/102918065/fd8e22cb-5b88-44c4-a0a8-ce33c7c62dbc)

## ExpiringStateScalaTest
![image](https://github.com/Won20/Big-Data/assets/102918065/e5af600f-1d05-4ee2-9ee1-011f1cff5c2c)





