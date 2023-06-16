Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:

git clone git@github.com:FenixZip/kittygram_final.git
cd kittygram
Cоздать и активировать виртуальное окружение:

python3 -m venv env
* Если у вас Linux/macOS

    ```
    source env/bin/activate
    ```

* Если у вас windows

    ```
    source env/scripts/activate
    ```

python3 -m pip install --upgrade pip
pip install -r requirements.txt
Выполнить миграции:

python3 manage.py migrate
Запустить проект:

python3 manage.py runserver