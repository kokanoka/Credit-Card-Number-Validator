# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

06.08.21 - 06.08.21 было проведено ручное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час.

В результате тестирования выявлены следующие дефекты:
* https://github.com/kokanoka/Credit-Card-Number-Validator/issues/1
* https://github.com/kokanoka/Credit-Card-Number-Validator/issues/2
* https://github.com/kokanoka/Credit-Card-Number-Validator/issues/3

В качестве тестовых данных использовались данные https://www.freeformatter.com/credit-card-number-generator-validator.html:
* 4917266763167237 
* 4929671314800499
* 6011986632383729
* 30446199745125 fail
* 5346917618100777
* 3537571898605254
* 36606829379587 fail
* 6371376596206526
* 340144774279389 fail
* 5453359993921833 
* 5018236677893488

Тестирование производилось в следующем окружении:
* Windows 10, 64 bit
* Java 11
