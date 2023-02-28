Создаем папку проекта и устанвливаем в ней виртуальное окружение:
python -m venv venv
активируем его:
venv\scripts\activate.bat
On Unix or MacOS, run: (source venv/bin/activate)

В папку проекта клонируем репозиторий:
https://github.com/suvorova-ya/F9.git

Затем инсталлируем необходимые для работы проекта пакеты:
pip install -r requirements.txt

В консоли переходим в директорию проекта и стартуем проект:
python server.py

API проекта будет доступно по адресам:
http://localhost:6969
или
http://127.0.0.1:6969/
