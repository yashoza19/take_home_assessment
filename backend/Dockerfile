FROM python:3.6
ENV PYTHONBUFFERED 1
RUN mkdir /my_app_dir
WORKDIR /my_app_dir
COPY . /my_app_dir
RUN pip install -r requirements.txt
RUN ls
CMD ["python3","manage.py", "runserver","0.0.0.0:8000","--noreload"]
