# FROM python:3
# MAINTAINER Jake House "jhouse@uoregon.edu"
# RUN apt-get update -y
# RUN apt-get install -y python3-pip python-dev build-essential
# COPY . /app
# WORKDIR /app
# RUN pip install -r requirements.txt
# ENTRYPOINT ["python"]
# CMD ["flask_vocab.py"]

FROM python:3
MAINTAINER Jake House "jhouse@uoregon.edu"
COPY . /app
WORKDIR /app
RUN pip install --no-cache-dir flask
ENTRYPOINT ["python"]
CMD ["flask_vocab.py"]