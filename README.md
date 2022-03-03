# Развертывание на локальной машине
1. Создаем виртуальное окружение: python3 -m venv flask_venv
1. Активируем venv: source flask_venv/bin/activate
1. Устанавливаем зависимости: pip install -r requirements.txt
1. Создаем локальную БД: flask db upgrade


# для создания миграции
1. создать тестовую базу main.db
2. изменить в модели формат
3. flask db migrate -m "add surname"
