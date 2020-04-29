# Отчёт о тестировании CardNumValid.class

## Краткое описание

29/04/2020 - было проведено функциональное тестирование класса CardNumValid.class

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Номера карт менее 16 символов](https://github.com/agasferon/JQA_task1.1/issues/1#issue-608693640)
* [Номера карт более 16 символов](https://github.com/agasferon/JQA_task1.1/issues/2#issue-608694538)

## Описание процесса тестирования

1. В IntelliJ IDEA был создан новый java.class
1. Вставлен исходный код
1. В 4 строке ```String number = "X";``` вместо "X" - подставлялись номера карт из списка
1. Код запускался на исполнение

## В процессе тестирования использовались следующие артефакты:
* [Исходный код CardNauValid.class](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)
* [Список номеров карт для проверки](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

Тестирование производилось в следующем окружении:
* Windows 10 1903 18362.778
* openjdk version "11.0.7" 2020-04-14
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.7+10)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.7+10, mixed mode)