# jaroen-shop-golang-tutorial

## Install go

1. Install go

```bash
brew install go
```

## Initial setup

1. Create folder and then run `go mod init`

```bash
go mod init github.com/hx-natthawat/jaroen-shop-golang-tutorial
```

2. Create `main.go` file

```go
package main

import "fmt"

func main() {
 fmt.Println("Hello, world!")
}
```

3. Run `go run main.go`

```bash
$ go run main.go
Hello, world!
```

## Issue logs

1. bug: unable to determine go version with Go installed using Snap #166
   <https://github.com/golang/vscode-go/issues/166>

2. go: command not found #165
