# geometric_lib
Данный проект содержит функции, позволяющие получать результаты выражений стандартных значений для разных фигур.

# How to use calculator:
1. Run `python calculate.py`
2. Enter the figure name. Available are Circle, Square.
3. Enter the function: Area or Perimeter.
4. Enter figure sizes. Radius for circle, one side for square.
5. Get the answer!

## Circle
### Area
    Возвращает площадь круга.

    Параметры:
        r (int): радиус круга

### Perimeter
    Возвращает периметр круга.

    Параметры:
        r (int): радиус круга
## Square
### Area
    Возвращает площадь квадрата. 

    Параметры:
        a (int): длина стороны квадрата
### Perimeter
    Возвращает периметр квадрата.

    Параметры:
        a (int): длина стороны квадрата
## Rectangle
### Area
    Возвращает площадь прямоугольника.

    Параметры:
        a (int): длина одной стороны прямоугольника
        b (int): длина другой стороны прямоугольника
### Perimeter
    Возвращает периметр прямоугольника.
    Параметры:
        a (int): длина одной стороны прямоугольника
        b (int): длина другой стороны прямоугольника
## Triangle
### Area
    Возвращает площадь треугольника.

    Параметры:
        a (int): длина первой стороны треугольника.
        b (int): длина второй стороны треугольника.
        c (int): длина третьей стороны треугольника.
        
### Perimeter
    Возвращает периметр треугольника.

    Параметры:
        a (int): длина первой стороны треугольника
        b (int): длина второй стороны треугольника
        с (int): длина третьей стороны треугольника
# Math formulast
## Area
- Circle: `S = πR²`
- Rectangle: `S = ab`
- Square: `S = a²`
- Triangle: `S = sqrt(p * (p-a) * (p-b) * (p-c))` where p is semiperimeter

## Perimeter
- Circle: `P = 2πR`
- Rectangle: `P = 2a + 2b`
- Square: `P = 4a`
- Triangle: `P = a + b + c`
# Change story
- 51c40ebfd0e0b65f52fe5e54740cbb038e492db3
- d76db2ac7f69cc920ae2e6f669fb0671a7fa7d71
- d080c7888b81955bad2ed78d58ad910526b5132a
