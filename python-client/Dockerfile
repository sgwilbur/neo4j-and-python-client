FROM python:3-alpine
LABEL maintainer="sgwilbur@gmail.com"

COPY requirements.txt /work/requirements.txt
WORKDIR /work

RUN pip install -r requirements.txt

ENTRYPOINT ["python"]
