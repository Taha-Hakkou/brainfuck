## A Brainf\*\*k Interpreter

### Instructions

The source code should be given as the first parameter

The interpreter consists of an array of 2048 bytes

To generate a new executable from th script:

```console
$ go mod init bf
go: creating new go.mod: module bf
go: to add module requirements and sums:
        go mod tidy
$ go build .
```

### Usage

```console
$ ./bf "++++++++++[>+++++++>++++++++++>+++>+<<<<-]>++.>+.+++++++..+++.>++.<<+++++++++++++++.>.+++.------.--------.>+.>." | cat -e
Hello World!$
$ ./bf "+++++[>++++[>++++H>+++++i<<-]>>>++\n<<<<-]>>--------.>+++++.>." | cat -e
Hi$
$ ./bf "++++++++++[>++++++++++>++++++++++>++++++++++<<<-]>---.>--.>-.>++++++++++." | cat -e
abc$
$ ./bf
$
```
