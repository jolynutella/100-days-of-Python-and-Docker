FROM alpine:3.16

RUN apk add --no-cache python3

COPY . /password-generator

WORKDIR /password-generator

CMD ["python3", "main.py"]
