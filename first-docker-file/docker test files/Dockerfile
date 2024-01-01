FROM python

WORKDIR ./app
COPY app.py app.py
RUN apt-get update && apt-get upgrade

ENTRYPOINT ["python3", "app.py"]