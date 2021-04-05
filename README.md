# Задача №1 - "Радиоман"

## Легенда

В рамках проекта по созданию "Умного дома" у нас появился очень важный клиент, которых хочет кастомную доработку: он очень любит радио, поэтому нам нужно научиться управлять радио.

*Что нужно сделать:

* по аналогии с кондиционером создайте класс Radio, в котором храните следующие поля:

Номер текущей (прослушиваемой) радиостанции

Громкость звука

*Требования к работе с радиостанциями:*

Номер текущей радиостанции изменяется в пределах от 0 до 9

Если текущая радиостанция - 9 и клиент нажал на кнопку next (следующая) на пульте, то текущей должна стать 0-ая

Если текущая радиостанция - 0 и клиент нажал на кнопку prev (предыдущая) на пульте, то текущей должна стать 9-ая

Клиент должен иметь возможность выставлять номер радиостанции с цифрового пульта (вводя числа 0 - 9)

Требования к работе с уровнем громкости звука:

Клиент должен иметь возможность увеличивать и уменьшать уровень громкости звука (в пределах от 0 до 10)*

Если уровень громкости звука достиг максимального значения, то дальнейшее нажатие на + не должно ни к чему приводить

Если уровень громкости звука достиг минимального значения, то дальнейшее нажатие на - не должно ни к чему приводить

Примечание*: на следующей паре мы поговорим, почему здесь 10

*Важно:* один вызов метода должен приводить к переключению на одну радиостанцию!

*Создайте на базе проекта с лекции собственный проект (вы можете использовать проект из предыдущей задачи), в котором:

*Подключите плагин Surefire так, чтобы сборка падала в случае отсутсвия тестов

*Подключите плагин JaCoCo в режиме генерации отчётов (обрушать сборку по покрытию не нужно)

*Реализуйте нужные классы и методы

*Напишите автотесты на методы, содержащие логику, добившись 100% покрытия по branch'ам

*Подключите CI на базе Github Actions и выложите всё на Github

*Итого:* у вас должен быть репозиторий на GitHub, в котором расположен ваш Java-код.