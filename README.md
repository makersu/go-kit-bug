# go-kit-bug
bug tracking


## go-kit cli
```
go get github.com/go-kit/kit
go get github.com/kujtimiihoxha/kit
```

## service
```
kit new service users
kit new service bugs
kit new service notificator
```

## middleware
```
kit generate service users --dmw
kit generate service bugs --dmw
kit generate service notificator -t grpc --dmw
```

## docker
```
kit generate docker
docker-compose up
```

## test
```
curl -XPOST http://localhost:8800/create -d '{"email": "test"}'
```
