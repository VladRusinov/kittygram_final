![example workflow](https://github.com/VladRusinov/kittygram_final/actions/workflows/main.yml/badge.svg)
## О проекте
проект kittygram_final Настраивает запуск проекта Kittygram в контейнерах и CI/CD с помощью GitHub Actions.

## Использованные технологии:
- Docker
- PostgreSQL
- Python
- Django


## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/VladRusinov/kittygram_final.git
```
Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```
Запустить проект:

```
docker compose up
```

## как заполнить .env:
```
POSTGRES_USER=django_user
POSTGRES_PASSWORD=mysecretpassword
POSTGRES_DB=django
DB_HOST=db
DB_PORT=5432
SECRET_KEY=ваш SECRET_KEY
```

## Автор:

Автор - Русинов Влад
