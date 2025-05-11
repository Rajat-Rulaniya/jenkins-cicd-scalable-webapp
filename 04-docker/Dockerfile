FROM python:3.10.17-alpine3.21
COPY . /application
WORKDIR /application
RUN pip install --no-cache-dir -r requirements.txt
EXPOSE 5000
CMD ["python", "app.py"]