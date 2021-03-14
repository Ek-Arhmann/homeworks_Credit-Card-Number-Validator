# Отчет о тестирование Credit Card Number Validator

**Краткое описание**

<07.03.2021> - <07.03.2021> было проведено Функциональное тестирование Credit Card Number Validator  .

На тестирование затрачено 1 час

В результате тестирования выявлены следующие дефекты:

- Валидные номера карт не равные 16 символам не проходят проверку

**баг-репорт:**

1.[программа Credit Card Number Validator не принимает валидацию карт не равную 16](https://github.com/Ek-Arhmann/homeworks_Credit-Card-Number-Validator/issues/2)

**Описание процесса тестирования**

В качестве тестовых данных использовались данные с сервиса : https://www.freeformatter.com/credit-card-number-generator-validator.html

- VISA: 4539889502039231

- MasterCard: 5488880799314799

- American Express (AMEX):371795927974804

- Diners Club - Carte Blanche: 30300409241021

- JCB: 3530014772262967020

**Тестирование производилось в следующем окружении:**

Windows 10, x64

Java 11

intellij idea 2020.3.2
