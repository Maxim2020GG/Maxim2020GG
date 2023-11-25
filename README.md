#Console calculator in Python (Консольный калькулятор на Python) (on 2 values) (на 2 значения)
print("Действия:\n(+) - Сложение \n(-) - Вычитание \n(*) - Умнажение \n(/) - Деление \n(**) - возведение в степень \n(//) - целочисленное деление \n(%) - статок от деления\n")
first_number  = float(input("Введите первое число: "))              #(Acceptance of basic values) (Принятие основных значений) 
first_sign    = str(input("Введите действие: "))
second_number = float(input("Введите второе действие: "))
def wwtn():                                                         #(Working_With_Two_Numbers) (Работа с уже имеющимися двумя числами)
    if first_sign == "+":
        print(first_number + second_number)
    elif first_sign == "-":
        print(first_number - second_number)
    elif first_sign == "*":
        print(first_number * second_number)
    elif first_sign == "/":
        print(first_number / second_number)
    elif first_sign == "**":
        print(first_number ** second_number)
    elif first_sign == "//":
        print(first_number // second_number)
    elif first_sign == "%":
        print(first_number % second_number)
    else:
        print("Erorr")
wwtn()

