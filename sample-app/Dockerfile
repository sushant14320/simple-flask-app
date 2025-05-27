FROM python:3.10-slim

WORKDIR /app

COPY . .

RUN pip intstall -r requirements.txt

EXPOSE 5000

ENTRYPOINT ["python", "main.py"]