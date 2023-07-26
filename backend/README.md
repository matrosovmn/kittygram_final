## Kittygram — социальная сеть для обмена фотографиями любимых питомцев. Проект состоит из бэкенд-приложения на Django и фронтенд-приложения на React.


### Описание проекта
Проект написан в рамках учебного курса по Python от Яндекс.Практикум.
Пользователи могут зарегистрироваться и авторизоваться, добавить нового котика на сайт или изменить существующего, загружать фотографии своих котов с кратким описанием, а также просмотреть записи других пользователей. Основная задача  - автоматизация деплоя проекта на удаленный сервер.

### Стек технологий использованный в проекте:
- Python 3.x
- backend: Django
- frontend: React
- Nginx
- Gunicorn
- Docker
- PostgreSQL

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/yandex-praktikum/kittygram_backend.git
```

```
cd kittygram_backend
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

* Если у вас Linux/macOS

    ```
    source env/bin/activate
    ```

* Если у вас windows

    ```
    source env/scripts/activate
    ```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```


### Автор
Михаил Матросов - [GitHub](https://github.com/matrosovmn)