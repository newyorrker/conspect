# Конспект по серии книг You don't know JS
---

## Принцип блоков

Блоки действуют подобно строительным блокам. Чтобы построить высокую башню, вы начинаете класть блок на блок, блок на блок. То же самое и в программировании. Вот несколько необходимых строительных блоков в программировании:

* Вам нужны *операции* для выполнения действий над значениями.
* Вам нужны значения и типы для выполнения различного рода действий, например, математических с числом или вывод со строкой.
* Вам нужны *переменные* для хранения данных (т.е. состояния) в процессе выполнения программы.
* Вам нужны условные конструкции, такие как оператор **if**, чтобы принимать решения.
* Вам нужны *циклы*, чтобы повторять действия пока заданное условие не прекратит быть истинным.
* Вам нужны *функции* для организации вашего кода в логические и повторно используемые части программы.

## Область видимости

Область видимости — это набор правил, которые определяют где и как переменная (идентификатор) могут быть найдены. Этот поиск может осуществляться для целей присваивания значения переменной, которая является LHS (left-hand-side) ссылкой, или может осуществляться для целей извлечения ее значения, которое является RHS (right-hand-side) ссылкой.

### Лексическая область видимости

Лексическая область видимости означает, что область видимости определена решениями о том, где объявляются функции на стадии написания кода. Фаза разбиения на лексемы при компиляции фактически способна узнать где и как объявлены все идентификаторы, и таким образом предсказать как их будут искать во время выполнения.

## **this**

Когда функция вызывается, создается запись активации, также известная как контекст вызова. Эта запись содержит информацию о том, откуда функция была вызвана (стэк вызова), как функция была вызвана, какие параметры были в неё переданы и т.д. Одним из свойств этой записи является ссылка this, которая будет использоваться на протяжении выполнения этой функции.
