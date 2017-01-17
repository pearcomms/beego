## Beego

[![Build Status](https://travis-ci.org/pearcomms/beego.svg?branch=master)](https://travis-ci.org/pearcomms/beego)
[![GoDoc](http://godoc.org/github.com/pearcomms/beego?status.svg)](http://godoc.org/github.com/pearcomms/beego)

beego is used for rapid development of RESTful APIs, web apps and backend services in Go.
It is inspired by Tornado, Sinatra and Flask. beego has some Go-specific features such as interfaces and struct embedding.

More info [beego.me](http://beego.me)

##Quick Start
######Download and install

    go get github.com/pearcomms/beego

######Create file `hello.go`
```go
package main

import "github.com/pearcomms/beego"

func main(){
    beego.Run()
}
```
######Build and run
```bash
    go build hello.go
    ./hello
```
######Congratulations! 
You just built your first beego app.
Open your browser and visit `http://localhost:8000`.
Please see [Documentation](http://beego.me/docs) for more.

## Features

* RESTful support
* MVC architecture
* Modularity
* Auto API documents
* Annotation router
* Namespace
* Powerful development tools
* Full stack for Web & API

## Documentation

* [English](http://beego.me/docs/intro/)
* [中文文档](http://beego.me/docs/intro/)
* [Русский](http://beego.me/docs/intro/)

## Community

* [http://beego.me/community](http://beego.me/community)

## LICENSE

beego source code is licensed under the Apache Licence, Version 2.0
(http://www.apache.org/licenses/LICENSE-2.0.html).
