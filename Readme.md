# go ビルド & 実行

```
docker exec go-http-server-hello-go bash -c "cd /opt/src/ && GOOS=linux GOARCH=amd64 go run sample.go"
```


# go ビルド

```
docker exec go-http-server-hello-go bash -c "cd /opt/src/ && GOOS=linux GOARCH=amd64 go build sample.go"
```
