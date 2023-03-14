```python
# OOП
# ЗАДАЧА 1 Создать класс который принимает на вход имя напитка и возвращает его

class Soda:
    def __init__(self, name):
        self.name = name

    def get_name(self):
        return self.name
    
    def __str__(self):
        return self.name
    
# ЗАДАЧА 2 Создать класс автомата с напитками, в котором хранится инфа о всех напитках и их цена.

class Automat:
    def __init__(self):
        self.sodas = ['cola', 'sprite', '7up']
        self.price = [60, 700, 40]

    def get_soda(self, id):
        return f"{self.sodas[id]}-{self.price[id]}$"
    
# Задача 3 Класс квадрата, в котором считается его площадь
class Square:
    def __init__(self, side):
        self.side = side

    def get_S(self):
        return self.side * self.side
    
# Задача 4 - Класс группы колледжа
class Group:
    def __init__(self, students):
        self.students = students

    def get_students(self):
        return self.students
    
# Задача 5 - найти площадь квадрата -
side = int(input("Введите сторону квадрата: "))
print(side*side)
# задача 6  пользователь выбирает напиток - надл написать его цену
sodas = ['cola', 'sprite', '7up']
price = [60, 700, 40]
print(sodas)
_id = int(input("Введите номер напитка: "))
print(price[_id])
# Задача 7 - найти площадь равностроннего треугольника
side = int(input("Введите сторону равностроннего треугольника"))

print((side*side*(3**1/2))/4)

# Задача 8 узнать совершеноллетный ли пользователь
age = int(input("Введите возраст: "))
if age >= 18:
    print("18+")
else:
    print('18-')

"""

Вывод - классами всё делать удобнее, и более читаемо
Пишите все классами

"""

```
