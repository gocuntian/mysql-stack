## Running Tests

```
$ mkdir src
$ export GOPATH=`pwd`
$ go get -u github.com/gocuntian/mysql-stack/driver
$ cd src/github.com/gocuntian/mysql-stack/
$ make test
```

## Examples

1. ***examples/mysqld.go*** mocks a MySQL server by running:

```
$ go run example/mysqld.go
  2018/01/26 16:02:02.304376 mysqld.go:52:     [INFO]    mysqld.server.start.address[:4407]
```

2. ***examples/client.go*** mocks a client and query from the mock MySQL server:

```
$ go run example/client.go
  2018/01/26 16:06:10.779340 client.go:32:    [INFO]    results:[[[10 nice name]]]
```

## Status

go-mysqlstack is production ready.

## License

go-mysqlstack is released under the GPLv3. See LICENSE
