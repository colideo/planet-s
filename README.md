# university_u3d
### Author: Баранов Иван. Студент УрФУ МатМех "Механика и математическое моделирование". 4-ый курс.

## В репозитории находятся 2 приложения, сделанных на Unity3d
### 1. Pendulums: проект реализован на версии 5.3.5f1
В проекте представлена реализация следующего:
1. Пружинный маятник по формуле.
2. Пружинный маятник на основе движка Unity3d.
3. Математичнский маятник по формуле.
4. Математический маятник на основе движка Unity3d.
5. Математический маятник на основе численных методов (методом Эйлера).
6. Математический маятник на основе численных методов (методом Рунге- Кутты 4 порядка).
### 2. Universe of Planet's: проект реализован на версии 2019.2.17f1
В проекте представлена реализация следующего:
1. Центральный объект обладает силой притяжения (Object Earth).
2. Орбитальное движение относительно Earth.
3. Помимо Earth, есть еще 3 Object'а, обладающих силой притяжения.
4. В проекте есть пушка, которая производит выстрел (по нажатию ЛКМ).
5. Добавлено n Object'ов (Появляются по нажатию Spase), которые обладают силой притяжения.
### В процессе реализации:
Делаю пушку, которая будет стрелять от 1-го лица и смотреть, как будут взаимодействовать Object'ы между собой
### Баги:
1. В процессе добавления n Object'ов, сломал Object Earth, элементы пролетают сквозь него. Найти ошибку пока не получается.
2. В процессе создания Gun, столкнулся со следующей проблемой: 
  1) Не смог настроить прицел так, чтобы он поворачивался в сторону указателя мыши.
  2) Движение Bullet сперва было баллистическим, но за счет того, что к Object Earth добавил силу притяжения, движение теперь не такое.
