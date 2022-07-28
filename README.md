# Cinemate

## Стек проекта

![Python](https://img.shields.io/badge/python-3.10-blue.svg?style=for-the-badge&logo=python)
![Django](https://img.shields.io/badge/django-4.1.6-blue.svg?style=for-the-badge&logo=django)
[![Pillow](https://img.shields.io/badge/Pillow-9.4.0-blue.svg?style=for-the-badge)](https://pypi.org/project/Pillow/)
[![django-ckeditor](https://img.shields.io/badge/django--ckeditor-6.5.1-blue.svg?style=for-the-badge)](https://pypi.org/project/django-ckeditor/)
[![Лицензия](https://img.shields.io/github/license/kluevevga/Cinemate?color=blue&style=for-the-badge&logo=github)](https://github.com/kluevevga/Cinemate/blob/master/LICENSE)
[![Размер кода](https://img.shields.io/github/languages/code-size/kluevevga/Cinemate?style=for-the-badge&logo=github)](https://github.com/kluevevga/Cinemate)

## О проекте

Проект представляет собой веб-сайт о кинофильмах, разработанный с использованием Django. Сайт обладает следующими
основными возможностями:

1. Рейтинги: Пользователи могут просматривать рейтинги кинофильмов, что позволяет им оценить фильмы на основе
   популярности или рейтинга.

2. Категории и жанры: Фильмы классифицированы по различным категориям и жанрам, что облегчает поиск и навигацию для
   пользователей.

3. Поиск: Сайт предоставляет возможность осуществления поиска, что позволяет пользователям быстро находить фильмы по
   названию, актерам или другим ключевым словам.

4. Фильтрация: Пользователи могут фильтровать фильмы по жанру, годам выпуска и актерам, что помогает им находить фильмы,
   соответствующие их интересам.

5. Админ-панель: Для управления контентом сайта создана административная панель. Это позволяет администраторам легко
   добавлять, редактировать или удалять фильмы, обновлять информацию и поддерживать актуальность контента.

6. Рендеринг на сервере: Сайт полностью рендерится на сервере и отдается клиентам в готовом виде. Это способствует
   оптимизации производительности и улучшению пользовательского опыта.

7. База данных: Для хранения данных используется база данных SQLite, что является легким и удобным решением для проекта
   данного типа.

Этот проект предоставляет пользователям удобный способ искать и получать информацию о кинофильмах, а также оценивать их.

## Установка

Для начала, склонируйте проект на свой компьютер:

```shell
git clone https://github.com/kluevevga/Cinemate.git
```

Перейдите в папку с проектом:

```shell
cd Cinemate
```

После этого, создайте виртуальное окружение:

```shell
python3 -m venv env
```

Активируйте виртуальное окружение:

Для Windows(power shell):

```shell
.\venv\Scripts\activate
```

Для macOS и Linux и windows(git bash):

```shell
source env/bin/activate
```

Установите зависимости, необходимые для проекта:

```shell
pip install -r requirements.txt
```

## Запуск development сервера

Выполните миграции для базы данных:

```shell
python manage.py migrate
```

Запустите сервер:

```shell
python manage.py runserver
```

## Лицензия 📜

Этот проект распространяется под лицензией `MIT`. Дополнительную информацию можно найти
в [LICENSE](https://github.com/kluevevga/Cinemate/blob/master/LICENSE).