from random import randint
x = randint(1, 10)
attempt = 0
while True:
    print("Я загадав число від 1 до 10 попробуй вгадати його:)")
    user_num = int(input("Ваш здогад: "))
    attempt += 1
