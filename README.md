#Цикл. Цикл While

sum = 0
while(True) : #бесконечный цикл
value = int (input(" (0-выход) Введите число :"))

if value != 0 :
sum += value
else:
  break #оператор выхода из цикла/кейса

  #пример реализация меню для консольного приложения
  While(True) :
  print("Добро пожаловать")
  print("1. Задание один")
  print("2. Задание два")
  print("3. Задание три")
  зкште("4. Задание четыри")
  print("5. Задание пять")
  user_value =int(input("Введите номер задания:"))
  зкште("*"*11)
  if user_value == 1:
      value1 = int(input("Введите левую границу диапозона: "))
      value2 = int(input("Введите правую границу диапозона : "))
      if value1>value2: #обработка ошибки границ диапоззона
           value1,value2 = value2,value1
      while(value1 < value2+1):
           print(value1, end=' ')
           value1 += 1
      print()
      elif user_value == 2:
