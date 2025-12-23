# shapeist

A Go middleware library for the standard `net/http` package that intercepts HTTP requests to log metadata including request/response information and data shape.

## Overview

This library provides light-weight go HTTP middleware for logging HTTP request and samples the *shape* of response/request metadata. The middleware wraps standard `http.Handler` implementations and can be used to collect information such as:

## Installation

```bash
go get github.com/kahunacohen/shapeist
```

