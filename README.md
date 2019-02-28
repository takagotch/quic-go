### quic-go
---
https://github.com/lucas-clemente/quic-go

```go
http.Handle("/", http.FileServer(http.Dir(wwwDir)))
h2quic.ListenAndServeQUIC("localhost:4242", "/path/to/cert/chain.pem", "/path/to/privkey.pem", nil)

http.Client {
  Transport: &h2quic.RoundTripper{},
}
```

```
go get -t -u ./...
go test ./...
```

```
```


