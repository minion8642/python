#Задание1
x = int(input("Введите ваш возраст: "))
if x < 18:
    print("Вы несовершеннолетний")
elif 18 <= x <= 65:
    print("Вы трудоспособный")
else:
    print("Вы пенсионер")
#Задание2
cost = int(input("Введите стоимость покупки: "))
if cost < 1000:
print("скидка не предоставляется")
elif 1000 <= cost<= 5000:
print("скидка 5%")
else:
print("скидка 10%")
#Задание3
def main():
 """Запрашивает у пользователя два числа и операцию, затем выводит результат вычисления."""
num1 = float(input("Введите первое число: "))
num2 = float(input("Введите второе число: "))
operation = input("Введите операцию (+, -, *, /): ")
if operation == "+":
result = num1 + num2
elif operation == "-":
result = num1 - num2
elif operation == "*":
result = num1 * num2
elif operation == "/":
if num2 == 0:
print("Деление на ноль!")
return
else:
result = num1 / num2
else:
print("Некорректная операция")
return
print(f"Результат: {result}")
if __name__ == "__main__":
main()
#Задание4
num0 = int(input("введите число: "))

if num0 %2 == 0 and (str(num0).endswith('2') or str(num0).endswith('6')):
    print("True")
else:
    print("False")
#Задание5
password = 228
n = int(input("введите пароль: "))
if n == password:
    print("доступ разрешен")
else:
    print("неверный пароль")
