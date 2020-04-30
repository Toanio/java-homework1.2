# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

30.04.2020  - 30.04.2020 было проведено ручное, исследовательское и функциональное тестирование  приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Credit Card Number Validator не распознает карты американских банков](https://github.com/Toanio/java-homework1.2/issues/1)
* [Credit Card Number Validator не распознала длинный номер карты Visa](https://github.com/Toanio/java-homework1.2/issues/2)


## Описание процесса тестирования

В качестве тестовых данных использовались данные [c сайта генератора банковских карт](https://www.freeformatter.com/credit-card-number-generator-validator.html):

* 4381081226860089 Result is OK
* 4058980490748072 Result is OK
* 4532860420487495639 Result is OK
* 6011059775540230 Result is OK
* 5203825999429644 Result is OK
* 345173215603118 Result is OK
* 3545428701001074 Result is OK
* 5440871173387094 Result is OK
* 0604299960450904 Result is OK
* 4026817926778738 Result is OK

Тестирование производилось в следующем окружении:
* Windows 10 x64
* openjdk version "11.0.7"

