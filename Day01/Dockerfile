FROM alpine:3.16

RUN apk add --no-cache python3

COPY . /band-name-generator

WORKDIR /band-name-generator

CMD ["python3", "main.py"]
