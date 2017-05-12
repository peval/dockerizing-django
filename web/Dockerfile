FROM index.alauda.cn/library/python:3.5

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

COPY ./web/ /usr/src/app

COPY ./web/requirements.txt /usr/src/app/
RUN pip install --no-cache-dir -r requirements.txt
