Отчёт о тестировании OpenJDK11, KeyValidator

Краткое описание

04.03.2021 - 04.03.2021 было проведено функциональное тестирование KeyValidator, тестирование установки приложения OpenJDK11.

На тестирование затрачено: 3

В результате тестирования выявлены следующие дефекты:

[Версия OpenJDK11 не соответствует заявленной](https://github.com/eilinwis/java_1.1/issues/1)

[Невалидный ключ проходит валидацию](https://github.com/eilinwis/java_1.1/issues/3#issue-822010170)

[Валидные ключи не проходят валидацию](https://github.com/eilinwis/java_1.1/issues/2#issue-822006391)


Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:

[Инструкция по установке OpenJDK 11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)

[Руководство использования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)



В качестве тестовых данных использовались данные <указать источник, откуда брались тестовые данные:

[Руководство использования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)  (поле "Ключи для проверки")


Тестирование производилось в следующем окружении:

ПК Windows 10 64 bit

Java 11.0.10" 2021-01-19 LTS

Git for Windows 2.30.1