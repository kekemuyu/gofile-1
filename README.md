# Gottp

A tiny directory listing web server.
It implementats HTTP/1.1 keepalive and chunked transfer encoding.

This tool is built for learning purpose only. It is not intended to be used in production.

### Usage

    Usage: gofiles <port> [-v]

Example:

    cd ~/public/
    gofiles 8080

### Install

    go get -u github.com/siadat/gofiles

### Implementation

[x] GET and HEAD methods
[x] Support keep-alive connections
[x] Support chunked transfer encoding
[x] Requests must include a `Host` header
[x] Requests with `Connection: close` should be closed
[x] Support for requests with absolute URLs
