FROM python:3.10.2-slim

WORKDIR /usr/src/app

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

ENV PORT=8000

EXPOSE 8000

CMD uvicorn test:app --reload --host 0.0.0.0 --port ${PORT}
