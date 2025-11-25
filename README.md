[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![Java CI with Maven](https://github.com/alekseyp555/java-playwright-api-testng/actions/workflows/maven.yml/badge.svg)](https://github.com/alekseyp555/java-playwright-api-testng/actions/workflows/maven.yml)

Напишите автотесты для функциональности веб-приложения, которое взаимодействует с удалённым REST API.

1.	Сделать метод generateTokenTest, который возвращает token
2.	Написать е2е с помощью playwright, java 17, testing/junit, gradle/maven

-	Create Booking
-	Get Booking ID
-	Update Booking
-	Partial Update Booking
-	Delete Booking


Обратить внимание для запросов нужна авторизация Update, Partial Update, and Delete Booking CreateToken API.

Документация
https://restful-booker.herokuapp.com/apidoc/index.html#api-Booking-CreateBooking

https://restful-booker.herokuapp.com/apidoc/index.html#api-Auth-CreateToken

Запуск API локально
docker compose -f docker-compose-restfulbooker.yml up





