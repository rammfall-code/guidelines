## Найкращі Практики
1. Повернення в Зворотному Виклику Масиву: Переконайтеся, що зворотні виклики, які використовуються в методах масивів (наприклад, `.map`, `.filter`), завжди повертають значення.
2. Напрямок Циклу `for`: Уникайте створення нескінченних циклів, переконавшись у правильному напрямку циклів `for`.
3. Повернення в Геттерах: Переконайтеся, що функції-геттери завжди повертають значення, щоб уникнути несподіваної поведінки.

## Запобігання Помилкам
1. Заборона Асинхронних Виконавців Обіцянок: Не використовуйте асинхронні функції як виконавці обіцянок.
2. Заборона `await` у Циклах: Уникайте використання `await` у циклах, оскільки це може викликати проблеми з продуктивністю та несподівану поведінку.
3. Заборона Присвоєння Класів: Запобігайте повторному присвоєнню класів після їх визначення.
4. Заборона Порівняння з Негативним Нулем: Уникайте порівняння значень з негативним нулем, щоб уникнути логічних помилок.
5. Заборона Присвоєння в Умовних Виразах: Забороняйте присвоєння значень у умовних виразах, щоб уникнути випадкових присвоєнь.
6. Заборона Присвоєння для `const`: Запобігайте повторному присвоєнню змінних, оголошених за допомогою `const`, для підтримки цілісності коду.
7. Заборона Умов із Константними Значеннями: Уникайте використання константних виразів у умовах, що може призвести до несподіваних нескінченних циклів.
8. Заборона Повернення Значення в Конструкторі: Запобігайте поверненню значення з конструктора.
9. Заборона Контрольних Символів у Регулярних Виразах: Забороняйте використання контрольних символів у регулярних виразах для покращення читабельності та зменшення кількості помилок.
10. Заборона Використання `debugger`: Забороняйте використання оператору `debugger` в продуктивному коді.

## Дублювання та Присвоєння
1. Заборона Дубльованих Аргументів Функції: Уникайте використання дубльованих аргументів у функціях, оскільки це може призвести до несподіваних результатів.
2. Заборона Дубльованих Членів Класу: Запобігайте дублюванню членів класу.
3. Заборона Дубльованих Умов `else-if`: Переконайтеся, що блоки `else-if` не містять дубльованих умов.
4. Заборона Дубльованих Ключів в Об'єктах: Забороняйте дублювання ключів в об'єктах, щоб уникнути несподіваної поведінки.
5. Заборона Дубльованих `case` в Конструкціях `switch`: Запобігайте дублюванню `case` в конструкціях `switch`.
6. Заборона Дубльованого Імпорту: Уникайте кількаразового імпорту одного й того ж модуля.

## Порожні Вирази та Непотрібний Код
1. Заборона Порожнього Класу Символів: Забороняйте порожні класи символів у регулярних виразах.
2. Заборона Порожніх Паттернів: Запобігайте використанню порожніх паттернів при деструктуризації.
3. Заборона Присвоєння Значень Виключенням: Уникайте присвоєння значень виключенням у блоках `catch`.
4. Заборона Наскрізного Проходження в `switch`: Запобігайте наскрізному проходженню в `switch`-конструкціях.
5. Заборона Присвоєння Функцій: Забороняйте повторне присвоєння функцій для уникнення плутанини.
6. Заборона Присвоєння Імпортів: Запобігайте повторному присвоєнню імпортованих змінних.
7. Заборона Оголошень Всередині Блоків: Забороняйте оголошення функцій або змінних всередині вкладених блоків.
8. Заборона Неправильних Регулярних Виразів: Запобігайте використанню неправильних регулярних виразів.
9. Заборона Нерегулярних Пробілів: Забороняйте нерегулярні пробіли поза рядками та коментарями.
10. Заборона Втрати Точності: Уникайте втрати точності при представленні чисел.
11. Заборона Оманливих Класів Символів: Запобігайте використанню оманливих класів символів у регулярних виразах.

## Правила для Об'єктів та Класів
1. Заборона Використання `new` для Не-Конструкторів: Забороняйте використання `new` для нативних не-конструкторських функцій.
2. Заборона Викликів Методів Об'єкта: Запобігайте викликам методів `Object` безпосередньо на об'єктах.
3. Заборона Виклику Методів Прототипу: Уникайте безпосереднього виклику методів `Object.prototype` на об'єктах.
4. Заборона Самоприсвоєння: Забороняйте присвоєння, де обидві сторони оператору присвоєння однакові, включаючи властивості.
5. Заборона Самопорівняння: Запобігайте порівнянню змінної з самою собою.
6. Заборона Повернення Значення в Сеттерах: Переконайтеся, що сеттери не повертають значення.
7. Заборона Рідкісних Масивів: Забороняйте використання рідкісних масивів.
8. Заборона Використання Шаблонних Рядків у Звичайних Рядках: Уникайте використання шаблонних рядків у звичайних рядках.
9. Заборона Використання `this` до Виклику `super`: Переконайтеся, що `super()` викликається перед використанням `this` у конструкторах успадкованих класів.

## Змінні та Невикористаний Код
1. Заборона Використання Невизначених Змінних: Запобігайте використанню незадекларованих змінних.
2. Заборона Несподіваних Багаторядкових Виразів: Уникайте можливих проблем із багаторядковими виразами в коді.
3. Заборона Немодифікованих Умов у Циклах: Забороняйте немодифіковані умови у циклах.
4. Заборона Недосяжного Коду: Запобігайте написанню коду, який ніколи не виконається (недосяжний код).
5. Заборона Недосяжних Циклів: Уникайте створення циклів, які ніколи не будуть виконані.
6. Заборона Небезпечного Коду у `finally`: Запобігайте потенційно небезпечній поведінці у блоках `finally`.
7. Заборона Небезпечного Заперечення: Забороняйте використання оператора `!` для заперечення відносних виразів.
8. Заборона Небезпечного Умовного Ланцюжка: Забороняйте умовні ланцюжки, які можуть призвести до несподіваної поведінки.
9. Заборона Невикористаних Приватних Членів Класу: Запобігайте оголошенню приватних членів класу, які ніколи не використовуються.
10. Заборона Невикористаних Змінних: Забороняйте невикористані змінні в коді, щоб тримати його чистим.
11. Заборона Використання До Оголошення: Запобігайте використанню змінних до їх оголошення.

## Надлишковість та Бажаний Синтаксис
1. Заборона Непотрібного Присвоєння: Уникайте непотрібних присвоєнь, які не змінюють значення.
2. Заборона Непотрібних Зворотних Посилань: Забороняйте зворотні посилання у регулярних виразах, які завжди збігаються.
3. Вимагання Атомних Оновлень: Переконайтеся, що оновлення змінних в асинхронному коді є атомними.
4. Використання `isNaN`: Переконайтеся, що `isNaN()` використовується для перевірки на значення `NaN`.

## Стиль Коду
1. Валідні Перевірки `typeof`: Переконайтеся, що перевірки `typeof` є валідними.
2. Пару Аксесорів: Переконайтеся, що коли визначений геттер, є відповідний сеттер.
3. Блоковий Скоп Змінних: Вимагайте використання блокових скоп змінних.
4. CamelCase: Вимагайте дотримання CamelCase у назвах.
5. Коментарі з Великої Літери: Переконайтеся, що коментарі починаються з великої літери.
6. Використання `this` у Методи Класів: Переконайтеся, що методи класів використовують `this`, запобігаючи непотрібним статичним методам.
7. Фігурні Дужки: Завжди використовуйте фігурні дужки в управляючих структурах (наприклад, `if`, `else`, `for`, `while`).
8. Останній `default` у `switch`: Переконайтеся, що `default` завжди знаходиться в кінці у `switch`-конструкціях.
9. Останні Параметри за Замовчуванням: Переконайтеся, що параметри за замовчуванням розміщуються останніми в сигнатурах функцій.
10. Точкова Нотація: Вимагайте використання точкової нотації, де це можливо.
11. Сувора Рівність (`===`): Вимагайте використання суворої рівності (`===`) та нерівності (`!==`).
12. Групування Пар Аксесорів: Переконайтеся, що геттер та сеттер згруповані разом у коді.
13. Довжина Ідентифікаторів: Вимагайте мінімальну та максимальну довжину ідентифікаторів, з винятками для загальноприйнятих коротких імен, таких як `i`, `j`, тощо.
14. Максимальна Глибина Вкладених Зворотних Викликів: Обмежте глибину вкладених зворотних викликів до 3 рівнів.
15. Використання `new` для Конструкторів: Переконайтеся, що функції-конструктори викликаються з `new`.
16. Заборона Оголошень у `case` у `switch`: Забороняйте лексичні оголошення у `case`/`default`.
17. Заборона Порожніх Операторів: Забороняйте порожні оператори, такі як непотрібні крапки з комою.
18. Заборона Порожніх Функцій: Запобігайте визначенню порожніх функцій.
19. Заборона Порожніх Статичних Блоків: Уникайте створення порожніх статичних блоків у класах.
20. Заборона Порівняння з `null`: Уникайте використання `==` або `!=` для порівняння з `null`.
21. Заборона Використання `eval`: Забороняйте використання `eval()` для запобігання загрозам безпеці.
22. Заборона Розширення Нативних Об'єктів: Запобігайте розширенню або зміні нативних об'єктів.
23. Заборона Зайвих Міток: Забороняйте непотрібні мітки у коді.
24. Заборона Присвоєння Глобальних Змінних: Забороняйте присвоєння глобальних змінних або властивостей тільки для читання.
25. Заборона Коментарів в Рядку: Запобігайте використанню коментарів після коду на тій самій лінії.
26. Заборона Одиноких Блоків: Забороняйте непотрібні вкладені блоки.
27. Заборона Одиноких `if` у `else`: Забороняйте `if`, як єдину заяву в блоці `else`.
28. Заборона Функцій в Циклах: Забороняйте функції, оголошені всередині циклів.
29. Заборона Множинних Присвоєнь: Запобігайте кількаразовому присвоєнню змінних в одному виразі.
30. Заборона Вкладених Тернарних Виразів: Забороняйте вкладені тернарні вирази для покращення читабельності.
31. Заборона Використання `new Function`: Запобігайте використанню `new Function()` для створення функцій.
32. Заборона Конструктора `Object`: Уникайте використання конструктора `Object`.
33. Заборона Повторного Присвоєння Параметрів: Забороняйте повторне присвоєння параметрів функцій.
34. Заборона Повторного Оголошення Змінних: Запобігайте повторному оголошенню змінних.
35. Заборона Присвоєння в Поверненні: Забороняйте присвоєння в межах оператору `return`.
36. Заборона Затінення Змінних: Запобігайте затіненню змінних для уникнення плутанини.
37. Заборона Затінення Заборонених Імен: Забороняйте затінення заборонених імен, таких як `undefined`.
38. Заборона Ініціалізації зі Значенням `undefined`: Забороняйте ініціалізацію змінних значенням `undefined`.
39. Заборона Непотрібних Тернарних Виразів: Забороняйте непотрібні тернарні вирази.
40. Заборона Невикористаних Міток: Запобігайте оголошенню міток, які ніколи не використовуються.
41. Заборона Непотрібних Викликів: Забороняйте непотрібні виклики функцій.
42. Заборона Непотрібних `catch`: Запобігайте непотрібним блокам `catch`.
43. Заборона Непотрібних Обчислених Ключів: Уникайте непотрібного використання обчислених ключів у об'єктах.
44. Заборона Непотрібних Конструкторів: Запобігайте визначенню конструкторів, які нічого не роблять.
45. Заборона Непотрібних Символів Екранізації: Забороняйте непотрібні символи екранізації у рядках і регулярних виразах.
46. Заборона Непотрібних `return`: Уникайте непотрібних операторів `return`.
47. Заборона Оголошення `var`: Забороняйте використання `var` і заохочуйте використання `let` або `const`.
