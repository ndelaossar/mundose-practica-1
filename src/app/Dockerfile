FROM python:3.10.8-alpine
WORKDIR /app
COPY src/app /app
RUN pip install -r requirements.txt
EXPOSE 8000
CMD ["python", "app.py"]
