# Sunstone
# Создаем словарь с видами янтаря и их ценами
янтарь_расценка = {
    "синий": 1000,
    "зеленый": 800,
    "красный": 1200,
    "желтый": 900
}

# Выводим расценку для каждого вида янтаря
for вид_янтаря, цена in янтарь_расценка.items():
    print(f"Янтарь {вид_янтаря}: {цена} рублей")
