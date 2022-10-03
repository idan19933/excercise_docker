FROM python

WORKDIR /app

COPY eccomerce /app

RUN pip install -r "requirements.txt"

CMD ["python", "./manage.py runserver"]