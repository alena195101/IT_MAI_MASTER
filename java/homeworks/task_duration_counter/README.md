# Расчет длительности проекта
### Расчет произваодится по критериям
1) Для каждой задачи есть предыдущая задача, кроме задачи 0. Если хотябы для одной задачи нету полследователя, такая последовательность задач, является недопустимой.
2) Задачи могут выполняться паралельно, только в том случае, если на это хватает ресурсов
### Датасеты
Так как рандомная генерация последовательностей в 99 процентах случаев приводит к невозможности критерия 1, внутри лежит датасет  который при любой последовательности вернет валидный результат.
* alwaysSuccess - всегда валидные результаты
* data - стандартный датасет
### Констатны
* ITERATIONS - Число последовательностей
* FILE_NAME - Имя датасета