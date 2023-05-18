$ go build -buildmode=plugin ../mrapps/wc.go
$ rm mr-out*
$ go run mrmaster.go pg-*.txt
$ go run mrworker.go wc.so
$ cat mr-out-* | sort | more
A 509
ABOUT 2
ACT 8
