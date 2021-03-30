# Отчёт о тестировании Credit Card Number Validator

Протестировать функциональность валидации номера банковской карты.

<31.03.2020 - <31.03.2020 было проведено функциональное тестирование  приложения CREDIT CARDS 

На тестирование затрачено: 30 минут

В результате тестирования выявлены следующие дефекты:
* <https://github.com/fiolentanna/credit_card_2/issues/1>
* <https://github.com/fiolentanna/credit_card_2/issues/2>
* <https://github.com/fiolentanna/credit_card_2/issues/3>

## Процесс тестирования 

В процессе тестирования использовались следующие артефакты*:
* Cоздать новый проект по тестированию на IntelliJ IDEA 2020.3.3 (Community edition)
* Вставить код для тестирования <https://github.com/netology-code/javaqa-homeworks/tree/master/intro>
* Внести номера банковских карт из тестовых данных, представленных ниже
* Запустить проверку


В качестве тестовых данных использовались данные <https://www.freeformatter.com/credit-card-number-generator-validator.html>:
* номер кредитной карты 4539578977304143 Visa; ожидаемый результат "Result is OK"
* номер кредитной карты 5208702471433086 Master card; ожидаемый результат "Result is OK"
* номер кредитной карты 370165366794959 American Express (AMEX); ожидаемый результат "Result is OK"
* номер кредитной карты 6011046550273387390 Discover; ожидаемый результат "Result is OK"
* номер кредитной карты 3541731826941411 JCB; ожидаемый результат "Result is OK"
* номер кредитной карты 5038742790443123 Maestro; ожидаемый результат "Result is OK"
* номер кредитной карты 30111523711587 Diners Club - Carte Blanche; ожидаемый результат "Result is OK"


Тестирование производилось в следующем окружении:
* macOS BIG Sur 
* версия Java - "11.0.10"
* IntelliJ IDEA 2020.3.3 (Community edition)