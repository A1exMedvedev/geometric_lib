# Geometric_lid

Эта библиотека поддерживает функции для определения периметра 
(длины окружности) для круга и квадрата.

## Описание функций
1. Circle:
    - Area:
        ```python
        def area(r):
            return math.pi * r * r
        ```
        Функция получает на вход радиус r и возвращает площать окружности:
        Пример area(5) ~ 78,5398163375;
    - Perimeter:
        ```python
        def perimeter(r):
            return 2 * math.pi * r
        ```
        Функция получает на вход радиус r и возвращает периметр окружности:
        Пример perimeter(5) ~ 31,415926535;
2. Square:
    - Area:
        ```python
        def area(a):
            return a * a
        ```
        Функция получает на вход сторону квадрата a и возвращает площать квадрата:
        Пример area(5) = 25;
    - Perimeter:
        ```python
        def perimeter(a):
            return 4 * a
        ```
        Функция получает на вход сторону квадрата a и возвращает периметр квадрата:
        Пример perimeter(5) = 20;

## История изменения проекта с хешами комитов
```bash
* 7f51fb9 (HEAD -> main) Add comments for square.py
* fcc6354 Add comments for circle.py
* d078c8d (origin/main, origin/HEAD) L-03: Docs added
* 8ba9aeb L-03: Circle and square added
```

