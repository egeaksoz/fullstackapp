FROM python:3.7

RUN mkdir /app
WORKDIR /app
ADD . /app/
RUN pip install -r requirements.txt

ENV DATABASE_URI="localhost"
ENV FLASK_APP=main.py

EXPOSE 5000
CMD ["python", "/app/main.py"]