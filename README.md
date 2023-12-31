# OOP-Materials
Materials for OOP 2nd semester FMI SU

1. Пространства от имена (Namespace). Енумерации, структури и обединения. Видове енумерации и
разлики
Работа с инстанции: Инициализация, достъп до елементите, влагане, работа с функции, работа с
масиви.
Размер на обекти/инстанции. Подравняване и отместване. Endianness и проверка за big/little endian.
Пример с задачата за N триъгълника.

2. Поток. Стандартни потоци. Текстови файлове. Йерархия на потоците. Интерфейс на потоци.
Потоци за вход/изход от файл. Режими на работа. Флагове на състоянията на потока.
Позициониране във файл.
Пример за функция, която връща големината на файл.
Пример за функция, която връща брой редове в текстов файл.

3. Работа с fstream - особености при отваряне на файл за четене и писане.
Двоични файлове. Запазване на обекти в двоичен файл. Четене на обекти от двоичен файл.
Пример за запазване/четене на масив от обекти(от един тип) във файл.
Пример за заместване на символ с друг символ във файл ( четене и писане с fstream)

4. Указател this. Член-функции. Конструктори и деструктор. Извикване на конструктори и
деструктори. Конвертиращи конструктори. Извикване на конструктори и деструктори при
създаване масиви (статични и динамични). Модификатори за достъп. Абстракция. Капсулация.
Mutable.
Пример за клас Person с име (низ с дължина най-много 20 символа) и години [5...90].

5. Разделна компилация. Препроцесор. Копиращ конструктор и оператор=. Композиция и агрегация.
Пример с клас Event (използваме клас Time и Date на готово).

6. Динамична памет в класовете. Голямата четворка.
Пример за клас студент с име (с произволна дължина) и масив от оценки(с произволна дължина).

7. Предефиниране на оператори. Приятелски класове и функции.
Пример за реализация на комплексно число и Nvector.

8. Статични член-данни. Изключения. Обработка на изключения. Йерархия на изключенията и
примери. Изключения в конструктори и деструктори. Нива на exception safety.
Пример с клас, който брои инстанциите си.

9. Масиви от указатели към обекти. Move семантики - ползи, lvalue, rvalue, move конструктор/оп=,
std::move. Пример за клас стринг с move семантика.

10. Наследяване. Видове наследяване. Параметри на функции (указатели и референции).
Конструктори и деструктори при наследяване. Копиране при наследяване. Move семантики при
наследяване.
Пример с човек, студент и преподавател.

11. Статично и динамично свързване. Виртуални функции. Ключови думи - override, final. Виртуални
таблици. Полиморфизъм. Абстрактни класове.
Пример за фигури.

12. Множествено наследяване. Диамантен проблем.
Колекции от обекти в полиморфна йерархия. Копиране и триене.
Пример с ферма

13. Шаблони. Необходими функции в шаблонен клас/шаблонна функция. Темплейтни специализации.
Примери за шаблонни класове/функции от стандартната библиотека.
Умни указатели. Употреба и идея на shared_ptr, weak_ptr, unique_ptr.
Пример за стек(с шаблонен капацитет) и опашка(с функция resize)

14. Type casting. SOLID principles. Design patterns - типове и примери (singleton, factory, flyweight, iterator,
command).
Пример за използване на singleton + factory.

15. Дървовидна структура от обекти от полиморфна йерархия.
Пример с логически изрази.
