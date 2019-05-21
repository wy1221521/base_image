FROM python:3
RUN apt-get update
RUN apt-get install gcc
RUN apt-get install git
RUN apt-get -y install vim
RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
RUN echo 'Asia/Shanghai' >/etc/timezone
RUN pip3 install requests==2.21.0
RUN pip3 install sanic==18.12.0
RUN pip3 install uvloop>=0.8.0
RUN pip3 install peewee>=3.0.1
RUN pip3 install psycopg2>=2.7.1
RUN pip3 install asyncpg>=0.11.0
RUN pip3 install aiohttp==3.5.4
RUN pip3 install aioamqp==0.12.0
RUN pip3 install aioredis==1.2.0
RUN pip3 install opentracing==2.0.0
RUN pip3 install python-gitlab==1.7.0
RUN pip3 install python-jenkins==1.4.0
RUN pip3 install pika==0.13.1
RUN pip3 install oss2==2.6.0
