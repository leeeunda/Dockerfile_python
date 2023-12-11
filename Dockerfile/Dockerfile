FROM python:3.9.12
LABEL mantainer="daun0219@gmail.com"

COPY . /app
RUN apt-get update
RUN echo "this is a python container"
CMD ["python","./pythonmain.py"]
EXPOSE 9000
