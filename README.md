# Проект TODOLIST

TODOLIST - это веб приложение - планировщик, который помогает вам вести свой распорядок дня, выделять наиболее 
важные дела, фильтровать события и т.д.

## Установка
1. Клонируйте репозиторий с github
2. Создайте виртуальное окружение
3. Установите зависимости 'pip install -r requirements.txt'
4. Создайте файл .env.py
5. Впишите в .env.py перерменные:
'''
SECRET_KEY=django-insecure-ob%t1%iazrqpd-o%03(e=kx#vb1i5-*k-+e&rq$@+@uhbukeup

DEBUG=True

export DB_NAME = todolist
export DB_USER = postgres
export DB_USER_PASSWORD = 1
export DB_HOST = localhost
export DB_PORT = 5433
'''
6. Запустите приложение командой в терминале 'py manage.py runserver'