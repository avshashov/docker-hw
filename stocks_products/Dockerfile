FROM python:3.11-alpine

WORKDIR /app/stocks_products

COPY . .

RUN pip install -r requirements.txt

CMD ["sh", "start_server.sh"]