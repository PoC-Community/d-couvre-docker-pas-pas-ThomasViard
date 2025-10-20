FROM python:3.7.5-alpine

WORKDIR /app

ENV PORT=5000

EXPOSE $PORT

COPY . .

RUN pip install --no-cache-dir -r requirements.txt

CMD ["python3", "run.py"]
