FROM python:3.6-alpine
ADD . /code
WORKDIR /
RUN pip install redis flask
CMD ["python", "app.py"]