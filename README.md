# jaroen-shop-golang-tutorial

## Lesson

- 001: Hello World - [Link](https://github.com/hx-natthawat/jaroen-shop-golang-tutorial/commit/b6064836a1ceb268b27235dcb762e82acb49d0ce)

- 002: Configurations / Env and Modules - [Link](https://github.com/hx-natthawat/jaroen-shop-golang-tutorial/commit/9fae974)

## Install go

1. ForInstall go

For MacOS

```bash
brew install go
```

For Ubuntu

```bash
sudo apt-get install golang-go
```

For Windows

```bash
choco install golang
```

2. Install go modules

```bash
go get -u golang.org/x/tools/gopls
```

3. Install gopls for VSCode

```bash
go install golang.org/x/tools/gopls@latest
```

---

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

## Style guide

1. [Go Style](https://google.github.io/styleguide/go/)
2. [Best practices](https://google.github.io/styleguide/go/best-practices)

## Related libraries

1. [Go Linter](https://go.dev/wiki/CodeReviewComments)

## Issue logs

1. bug: unable to determine go version with Go installed using Snap #166
   <https://github.com/golang/vscode-go/issues/166>

2. go: command not found #165
