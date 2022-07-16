FROM python:3.10.0

COPY requirements.txt ./src/requirements.txt
RUN pip install -r ./src/requirements.txt

ENV PYTHONUNBUFFERED 1

COPY . /src

WORKDIR src

EXPOSE 8000

CMD ["python", "./manage.py", "runserver", "0.0.0.0:8000" ] 



