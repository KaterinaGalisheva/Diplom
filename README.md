'''Дипломная работа на тему: " Анализ и сравнение написания web-приложений с использованием разных фреймворков: Разработать простые веб-приложения с использованием Django, Flask и FastAPI, провести их сравнение"

Данный проект представляет собой исследование и сравнение фреймворков для разработки сайтов. Разработан сайт для интернет магазина с интеграцией блога и телеграм бота.

ОПИСАНИЕ:
• Сравнение и выбор фреймворков для разработки сайта.
• Разработка сайта на выбранном фреймворке, а именно Django.
Решаемые задачи:
• Оптимизация процесса разработки.
• Выбор наиболее подходящего фреймворка для конкретных задач.
Важность проекта:
• Упрощение выбора фреймворка для разработчиков.
• Повышение качества и скорости разработки веб-приложений.

УСТАНОВКА ПРОЕКТА:

1. Клонируйте проект с GitHub:
```bash
git clone https://github.com/KaterinaGalisheva/Diplom

 2. Перейдите в папку проекта:

cd Diplom

 3. Создайте виртуальное окружение (если используется):

python -m venv venv
source venv/bin/activate  # Для macOS/Linux
venv\Scripts\activate  # Для Windows

4. Установите зависимости:

pip install -r requirements.txt

ЗАПУСК ПРОЕКТА:

Запуск основного скрипта:
```bash
Необходимо разделить терминалы для одновременного запуска сайта и телеграмбота
терминал сайта:
cd DiplomDjango
cd diplom
python manage.py runserver
терминал бота:
cd DiplomDjango
cd diplom
cd bot_app
python run.py

ОСНОВНОЙ ФУНКЦИОНАЛ ПРОЕКТА:
БОТ
- взаимодействие с клиентами через одну базу данных с сайтом
Регистрация на сайте
- удобный функционал регистрации и добавления клиента в базу данных
Магазин
- показывает ассортимент товара
- добавляет в корзину
оформляет покупку
Блог
- обозревает статьи по тематике магазина


СТРУКТУРА ПРОЕКТА:

- DiplomDjango - папка с основным проектом
 - diplom - папка с проектом
  - diplom - основной проект
  - bot_app - приложение с ботом
   - run.py - главный файл проекта с телеграм ботом
  - sign_in - приложение с регистрацией
  - spacestore - приложение с магазином
  - spaceposts - приложение с блогом
  - manage.py - главный файл проекта джанго
- DiplomFastApi - папка с разработкой похожего сайта на фреймворке fastapi
 - main.py - главный файл проекта на фастапи
- DiplomFlask - папка с разработкой похожего сайта на фреймворке fastapi
 - app.py - главный файл проекта на фласк

- static - папки со статическими файлами
- templates - папки с шаблонами
- media - папки с медиа файлами
- README.md - Документация проекта
- requirements Список зависимостей

АВТОР ПРОЕКТА:

Галышева Екатерина



'''
