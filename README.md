# Testing
проект с применением тестирования
1. Создан проект и добавлена в него библиотеку JUnit.
2. Создан класс UserTest и класс User с полями логин и email. Класс «User» нужно будет тестировать.
3. В классе UserTest прописаны следующие тесты:
- Создан тест, который выполняет тестирование создания объекта User с передачей в него двух параметров. Такая функция лишь должна проверять устанавливаются ли данные при создании объекта;
- Создан аналогичный тест, который выполняет тестирование по созданию объекта без передачи в него параметров;
- Создан тест, который протестирует установлен ли корректный Email адрес в поле email в классе User. Некорректным будет считаться тот email, в котором нет знака @ или же знака точки.
- Создан тест, который определяет, равны ли login и email (Они не должны быть равны).
