# https://github.com/cdrx/scrapyd-authenticated
FROM python:3.7.7-slim-buster

ADD requirements.txt /
RUN pip install -r requirements.txt

VOLUME /scrapyd

ADD scrapyd.conf /etc/scrapyd/scrapyd.conf

EXPOSE 6800

CMD ["scrapyd"]
