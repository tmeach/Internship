Система проверяет ключевые метрики в продукте (DAU, WAU, MAU, CTR, LPU) с помощью статистических методов детектирования аномалий. В случае обнаружения аномального значения в чат в Telegram отправляется сообщение с названием метрики, ее значением, величиной отклонения, и ссылкой на дашборд в Apache Superset. 
DAG выполняется каждый день в 11:00, количество попыток выполнить DAG - 2, интервал между запусками - 5 минут.