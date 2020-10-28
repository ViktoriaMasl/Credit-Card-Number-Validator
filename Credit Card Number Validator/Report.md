# Отчёт о тестировании Credit Card Number Validator
## Краткое описание
28.10.2020 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 2 часа

**В результате тестирования выявлены следующие дефекты:**

1. [В коде при проверке валидации номера карт с длиной более 16ти знаков отображаются как невалидные](https://github.com/ViktoriaMasl/Credit-Card-Number-Validator/issues/1)
2. [В коде при проверке валидации номера карт с длиной менее 16ти знаков отображаются как невалидные](https://github.com/ViktoriaMasl/Credit-Card-Number-Validator/issues/2)  

## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:

1. [Баг-репорт 1](https://github.com/ViktoriaMasl/Credit-Card-Number-Validator/issues/1)
2. [Баг-репорт 2](https://github.com/ViktoriaMasl/Credit-Card-Number-Validator/issues/1)  

В качестве тестовых данных использовались валидные номера карт с сайта [www.freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html)

**Тестирование производилось в следующем окружении:**

PC, Windows 10 Pro версия 1903  
IntelliJ IDEA 2020.2.3 (Community Edition)  
Build #IC-202.7660.26, built on October 6, 2020  
Runtime version: 11.0.8+10-b944.34 amd64  
VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o.
