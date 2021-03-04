# Отчёт о тестировании OpenJDK11, KeyValidator

## Краткое описание

04.03.2021 - 04.03.2021 было проведено тестирование установки приложения OpenJDK11, тестирование совместимости KeyValidator, функциональное тестирование KeyValidator.

На тестирование затрачено: 3

В результате тестирования выявлены следующие дефекты:

* [Версия OpenJDK11 не соответствует заявленной](https://github.com/eilinwis/java_1.1/issues/1)

* [Невалидный ключ проходит валидацию](https://github.com/eilinwis/java_1.1/issues/3#issue-822010170)

* [Валидные ключи не проходят валидацию](https://github.com/eilinwis/java_1.1/issues/2#issue-822006391)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

* [Инструкция по установке OpenJDK 11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)

* [Руководство использования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)



В качестве тестовых данных использовались данные [Руководства использования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md) 

 
Валидные ключи:

* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 OK

* 80b427f8-92cd-3aae-ba04-3927fbe17c6 OK

* b295bc63-9f03-3b4b-af80-969b39f8c262 OK

* 387eedc6-12e9-3b32-9881-63b6b5e85317 OK

* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180 OK

Невалидные ключи:

* 18252235-78e0-44a5-8720-556f0c7da17a FAIL

* e66075b6-ddad-445e-baf6-161b3289522b FAIL

* b6d53250-f07e-4352-a293-6102ddf7f1ca FAIL

* c2bc778a-1cb9-46c6-b435-0489649d2a42 FAIL

* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 FAIL




Тестирование производилось в следующем окружении:

* ПК Windows 10 64 bit

* Java 11.0.10" 2021-01-19 LTS

* Git for Windows 2.30.1