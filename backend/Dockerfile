FROM python:3.6
ENV PYTHONBUFFERED 1
RUN groupadd -g 999 appuser && \
    useradd -r -u 999 -g appuser --home /my_app_dir appuser
RUN id
WORKDIR /my_app_dir
COPY . /my_app_dir
RUN pip install -r requirements.txt
USER appuser
RUN ls