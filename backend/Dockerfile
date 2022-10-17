FROM python:3.9

COPY ./backend/requirements.txt /run

WORKDIR /run

RUN pip install -r requirements.txt

CMD [ "sh", "entrypoint.sh" ]