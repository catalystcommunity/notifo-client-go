# notifo-client-go

A golang http client for [Notifo](https://github.com/notifo-io/notifo)

This client was generated using [oapi-codegen](https://github.com/deepmap/oapi-codegen/tree/v1.11.0) with the command
```shell
oapi-codegen -package notifo_client_go -generate types,client -old-config-style -o notifo-client.go openapi.json
```

You can get the notifo openapi spec by running notifo and going to `http://localhost:5000/api/docs` in yor browser, then click the `Download` button at the top.