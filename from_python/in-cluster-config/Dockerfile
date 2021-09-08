FROM python:3.8

ADD in_cluster_config.py /home
WORKDIR /home
RUN pip install kubernetes

ENTRYPOINT ["python", "-u", "/home/in_cluster_config.py"]
