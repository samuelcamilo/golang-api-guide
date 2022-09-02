# Golang API with Gin - Structure Guide

Gin-Gonic is a framework based on [httprouter](https://github.com/julienschmidt/httprouter). It's an HTTP multiplexer like gorilla/mux, but it is more fast. Gin allows a high-level API to create REST services.

## Folder's Structure

This structure is based on [Standard Go Project Layout](https://github.com/golang-standards/project-layout/blob/master/README.md), but with some diferences.

- cmd: don't put a lot of code in the application directory. It resposability is initialize the application environments, 
starts the server and logs.
- controllers: 
- core:
- db:
- middleawares:
- server:
- utils: