# Something-is-rotten-in-the-state-of-Denmark
import random

# Создаем список с номерами участников
participants = list(range(1, 51))

# Выбираем победителя случайным образом
winner = random.choice(participants)

print("Победитель лотереи - участник номер", winner)
