FROM alpine:3.16

RUN apk add --no-cache python3

COPY . /caesar-cipher

WORKDIR /caesar-cipher

CMD ["python3", "main.py"]
