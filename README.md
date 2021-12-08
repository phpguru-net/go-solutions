# Go Solution

## 1. Init project structure

```bash
go mod init github.com/phpguru-net/go-solutions
```

## 2.Use external package

```bash
go get github.com/phpguru-net/go-hello
```

```go
package main

import (
	"github.com/phpguru-net/go-hello/day1"
)

func main() {
	day1.Examples()
}

```
