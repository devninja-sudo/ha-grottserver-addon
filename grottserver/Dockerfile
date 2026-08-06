FROM python:3.12-slim

WORKDIR /app

COPY app /app

RUN pip install --no-cache-dir -r requirements.txt

RUN chmod +x /app/run.sh

CMD ["/app/run.sh"]