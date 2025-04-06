# Використовуємо базовий образ Python версії 3.10
FROM python:3.10-slim

# Встановлюємо робочий каталог всередині контейнера
WORKDIR /app

# Копіюємо всі файли проекту в контейнер
COPY . /app

# Встановлюємо всі залежності з requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Вказуємо основну команду запуску програми
CMD ["python", "pomychnyk_project.py"]
