# Отчёт о тестировании  валидатора кредитных карт

## Краткое описание

14.05.2021 - 14.05.2021 был проведен smoke-test приложения валидатора кредитных карт.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
* [Номера 15-ти значных банковских карт American Express валидатор не принимает](https://github.com/KuliakQA/java1.1/issues/1#issue-881137434)
* [Номера 13-ти значных банковских карт Visa валидатор не принимает](https://github.com/KuliakQA/java1.1/issues/2)

## Описание процесса тестирования

*В процессе тестирования использовались следующие артефакты*:

* Код [public class Main](https://raw.githubusercontent.com/KuliakQA/java1.1/master/src/Main.java)
* [Номера банковских карт](https://docs.google.com/spreadsheets/d/1qpbM7qYeS4Uio213CDe7SGpQe2sGu4quToe1_cgVdDA/edit?usp=sharing): Mastercard, Visa, American Express


В качестве тестовых данных использовались данные:
* [Get Credit Card Numbers](https://www.getcreditcardnumbers.com/)

Тестирование производилось в следующем окружении:
* Windows 10 / процессор x64 / Сборка ОС 19041.928
* версия Java: 11.0.10+9