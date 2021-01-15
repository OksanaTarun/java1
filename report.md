# Отчёт о тестировании KeyValidator

## Краткое описание

15.01.2021 было проведено функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
* <a href="https://github.com/OksanaTarun/java1/issues/1">Невалидные ключи в списке валидных</a>
* <a href="https://github.com/OksanaTarun/java1/issues/2">Валидный ключ в списке невалидных</a>


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* <a href="https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md">Инструкция по установке OpenJDK 11</a>
* <a href="https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md">Руководство использования KeyValidator</a>


В качестве тестовых данных использовались данные <a href="https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md">ключей для проверки</a>:
* валидные ключи - ответ ОК
* невалидные ключи - ответ FAIL

Тестирование производилось в следующем окружении:
* macOS Mojave 10.14.6
* openjdk version "11.0.9.1" 2020-11-04
