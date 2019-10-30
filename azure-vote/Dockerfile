# FROM tiangolo/uwsgi-nginx-flask:python3.6
# RUN pip install redis
# ADD /azure-vote /app

FROM    tiangolo/uwsgi-nginx-flask:flask

RUN     apt-get update && \
        apt-get install libmysqlclient-dev -y && \
        pip install flask-mysql
 
ADD     /azure-vote /app