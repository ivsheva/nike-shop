FROM alpine:3.12

WORKDIR /pocketbase

COPY . .

RUN ./pocketbase migrate

EXPOSE 8090

CMD [ "./pocketbase", "serve", "--http=0.0.0.0:8090" ]