FROM python:3

RUN pip3 install Flask mysql-connector-python hvac

WORKDIR /usr/src/app
ADD templates ./templates/
ADD app.py config.ini db_client.py ./


CMD [ "python", "./app.py" ]
