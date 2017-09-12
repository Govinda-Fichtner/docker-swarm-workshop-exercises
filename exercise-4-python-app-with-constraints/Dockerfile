FROM python:3.4-alpine
ADD ./lib /code
WORKDIR /code
RUN pip install -r requirements.txt
CMD ["python", "app.py"]
