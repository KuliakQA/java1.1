# Отчёт о тестировании  функциональность валидации номера банковской карты.

## Краткое описание

07.05.2021 - 08.05.2021 было проведено smoke test приложения IntelliJ IDEA.

На тестирование затрачено: 8 часов

В результате тестирования выявлены следующие дефекты:
* [ссылка](https://github.com/KuliakQA/java1.1/issues/1#issue-881137434)

## Описание процесса тестирования

*В процессе тестирования использовались следующие артефакты*:

* Код [public class Main](https://raw.githubusercontent.com/KuliakQA/java1.1/master/src/Main.java)
* [Номера банковских карт](https://docs.google.com/spreadsheets/d/1qpbM7qYeS4Uio213CDe7SGpQe2sGu4quToe1_cgVdDA/edit?usp=sharing): Mastercard, Visa, American Express


В качестве тестовых данных использовались данные:
* [Get Credit Card Numbers](https://www.getcreditcardnumbers.com/)

Тестирование производилось в следующем окружении:
* Windows 10 / процессор x64 / Сборка ОС 19041.928
* версия Java: 11.0.10+9