number = int(input("введите целое число: "))
# a)
if number > 0:
    print("число положительное")
elif number == 0:
    print("число равно нулю")
elif number < 0:
    print("число отрицательное")
# б)
if number == 0:
    print("число не имеет чётности")
elif number % 2 == 0:
    print("число чётное")
elif number % 2 == 1:
    print("число не чётное")
