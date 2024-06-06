# module_math_for_good_learning_language
Это модуль для шуточного рускоязычного языка ХУЯ, на подобии math из python

Для использования модуля нужно положить файл математика.хуя в директорию с остальными файлами модулей (прелюдия.хуя, рейлиб.хуя)


КОНСТАНТЫ:

ПИ = 3.1415926535897932384626433832795

Е = 2.7182818284590452353602874713527


КОМАНДЫ:

модуль(число: вещ): вещ - принимает вещественное число и возвращает его вещественный модуль

возвести_в_степень(число: вещ, степень: нат): вещ - принимает 2 параметра: 1. вещественное чесло x, 2. натуральный показатель степени y, возвращает вещественный x^y

возвести_в_квадрат(число: вещ): вещ - принимает вещественный x, возвращает вещественный х² 

возвести_в_куб(число: вещ): вещ - принимает вещественный x, возвращает вещественный х³ 

факториал(нач_число: цел): цел - принимает целый x, возвращает целый x факториал (x!)

квадратный_корень_с_погрешностью(число: вещ, погрешность: вещ): вещ - принимает 2 параметра: 1. вещественный x, 2. допустимая вещественная погрешность y, возвращает вещественный √x ± y

квадратный_корень(число: вещ): вещ - принимает вещественный параметр x, возвращает вещ √x с заданой погрешьностью 1/1 000 000

округление_вверх(число: вещ): цел - принимает вещественный параметр x, возвращает целое x округлённое вверх

округление_вниз(число: вещ): цел - принимает вещественный параметр x, возвращает целое x округлённое вниз

радианы(число: вещ): вещ - принимает вещественный угол в градусах, возвращает вещественный угол в радианах

градусы(число: вещ): вещ - принимает вещественный угол в радианах, возвращает вещественный угол в градусах

округлить(нач_число: вещ, знак: нат): вещ - принимает 2 параметра: 1. вещественное x, 2. натуаральное, до какого знака округлить, возвращает вещественное округлённное значение
