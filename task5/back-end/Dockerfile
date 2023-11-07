FROM ubuntu:latest
RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install -y python3 python3-pip
RUN pip3 install flask
RUN pip install flask-cors
WORKDIR /app
COPY ./api.py /app/api.py
EXPOSE 5252
CMD ["python3", "api.py"]
