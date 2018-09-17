# Задание к уроку "Основы Ruby. Часть 1"

- Идеальный вес. Программа запрашивает у пользователя имя и рост и выводит идеальный вес по формуле <рост> - 110, после чего выводит результат пользователю на экран с обращением по имени. Если идеальный вес получается отрицательным, то выводится строка "Ваш вес уже оптимальный"
- Площадь треугольника. Площадь треугольника можно вычислить, зная его основание (a) и высоту (h) по формуле: 1/2*a*h. Программа должна запрашивать основание и высоту треугольника и возвращать его площадь.
- Прямоугольный треугольник. Программа запрашивает у пользователя 3 стороны треугольника и определяет, является ли треугольник прямоугольным, используя теорему Пифагора (www-formula.ru) и выводит результат на экран. Также, если треугольник является при этом равнобедренным (т.е. у него равны любые 2 стороны), то дополнительно выводится информация о том, что треугольник еще и равнобедренный. Подсказка: чтобы воспользоваться теоремой Пифагора, нужно сначала найти самую длинную сторону (гипотенуза) и сравнить ее значение в квадрате с суммой квадратов двух остальных сторон. Если все 3 стороны равны, то треугольник равнобедренный и равносторонний, но не прямоугольный.
- Квадратное уравнение. Пользователь вводит 3 коэффициента a, b и с. Программа вычисляет дискриминант (D) и корни уравнения (x1 и x2, если они есть) и выводит значения дискриминанта и корней на экран. При этом возможны следующие варианты:
    - Если D > 0, то выводим дискриминант и 2 корня
    - Если D = 0, то выводим дискриминант и 1 корень (т.к. корни в этом случае равны)
    - Если D < 0, то выводим дискриминант и сообщение "Корней нет"
