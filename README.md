# javahw9.2
Домашнее задание к занятию «Объектно-ориентированное программирование: ключевые принципы»
## Задача №2 - "Менеджер"*
Важно: это необязательная задача. Её (не)выполнение не влияет на получение зачёта по ДЗ.

### Легенда

Разработайте класс `PostManager` (по аналогии с `MovieManager` с лекции), который хранит в приватном поле массив объектов класса `Post` из предыдущего задания.

Прочитайте описание запросов в вк следующих операций [Wall.search](https://vk.com/dev/wall.search) и [Wall.delete](https://vk.com/dev/wall.delete). Если бы каждая из этих операция имела вид джава-метода, как бы выглядело их объявление? Реализацию писать не нужно, пусть просто возвращают `null` как на лекции, цель верно написать название, тип возвращаемого значения и список параметров. 

Если у вас по каким-то причинам недоступны сервисы Vk, то воспользуйтесь [PDF-версией страниц](assets/manager)

Игнорируйте аргументы `extended` и `fields`.

Изменения по сравнению с описанием:
* `search` должен возвращать массив, а не объект, т.е.: `public Post[] search(список аргументов) { return null; }`
* `delete` ничего не должен возвращать, т.е.: `public void delete(список аргументов) {}`

**Важно**: создавать объекты класса, писать реализацию методов и автотесты на них **не нужно**.

Выполняйте это задание в том же репозитории, что и предыдущее задание. Разработанные классы поместите в `package` `manager`.

Итого: у вас должен быть репозиторий на GitHub, в котором расположен ваш Java-код (автотесты и CI не нужны).
