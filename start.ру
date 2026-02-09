import time

def search_money():
    # Имитация поиска. В следующем шаге мы подключим реальные чаты Паттайи
    opportunities = [
        {"task": "Аудит систем яхты 50ft", "budget": 20000, "loc": "Ocean Marina"},
        {"task": "Диагностика двигателя", "budget": 8000, "loc": "Bali Hai Pier"}
    ]
    return opportunities

if __name__ == "__main__":
    print("--- АГЕНТСТВО ААРОНА ЗАПУЩЕНО ---")
    while True:
        jobs = search_money()
        for job in jobs:
            profit = job['budget'] * 0.3
            print(f"ОБЪЕКТ: {job['task']} | Бюджет: {job['budget']} THB")
            print(f"Твоя прибыль (30%): {profit} THB | Локация: {job['loc']}\n")
        
        print("Система мониторит рынок... Ждем новые заказы.")
        time.sleep(60)
