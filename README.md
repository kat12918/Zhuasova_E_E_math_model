Эта модель используется для анализа работы очередей, в которых клиенты поступают в систему с определённой интенсивностью и обслуживаются одним узлом обслуживания. Модель позволяет оценить характеристики системы, такие как среднее количество клиентов в очереди, среднее время ожидания и вероятность того, что система пуста.
Входные данные:
•	lamb: интенсивность потока клиентов.
•	mu: интенсивность обслуживания (среднее количество клиентов, обслуживаемых за единицу времени).
Ограничения: интенсивность потока клиентов (lamb) должна быть меньше интенсивности обслуживания (mu), чтобы избежать бесконечного роста очереди.
Переменные:
rho: коэффициент загрузки системы, рассчитываемый как rho = lamb / mu.
L: Среднее количество клиентов в системе.
W: Среднее время ожидания в системе.
P_0: Вероятность того, что система пуста.
L: Среднее количество клиентов в очереди.
