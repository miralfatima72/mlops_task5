FROM python:3.8

WORKDIR /usr/src/app

COPY . /usr/src/app/

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 5000

CMD ["python", "app.py"]
