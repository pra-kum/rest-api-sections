FROM python:alpine
RUN apk update
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
ENTRYPOINT [ "python3" ]
CMD [ "app.py" ]
