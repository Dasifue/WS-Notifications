# Django Websockets


## How to run

1. Run Redis server via Docker

    ```bash
    docker run -p 6379:6379 -d redis
    ```
2. Install dependencies

    ```bash
    python -m venv venv # create venv
    venv\Scripts\activate # activate it

    pip install -r requirements.txt
    ```

3. Migrate database

    ```bash
    python manage.py migrate
    ```

4. Run project

    ```bash
    python manage.py runserver
    ```
