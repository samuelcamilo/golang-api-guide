# Golang API with Gin - Structure Guide
[![GoDoc](https://pkg.go.dev/badge/github.com/gin-gonic/gin?status.svg)](https://pkg.go.dev/github.com/gin-gonic/gin?tab=doc)

Gin-Gonic is a framework based on [httprouter](https://github.com/julienschmidt/httprouter). It's an HTTP multiplexer like gorilla/mux, but it is more fast. Gin allows a high-level API to create REST services.

## Folder's Structure

This structure is based on [Standard Go Project Layout](https://github.com/golang-standards/project-layout/blob/master/README.md), but there is a few diferences in your composition.

- **cmd:** don't put a lot of code in the application directory. It resposability is initialize the application environments and IoC´s.
- **controllers:** put any code related to public endpoints. 
- **core:**
- **db:**
- **middleawares:**
- **server:**
- **utils:**

## Packages Project
This packages are using in this projects.

| Packages | Reference |
| ------ | ------ |
| Go | [go.dev/][PlDb] |
| Gin | [github.com/gin-gonic/gin#readme][PlGh] |

## Requirements
TODO...

## Run API
TODO...