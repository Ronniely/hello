# hello

just say hello

## Install

import code

```bash
go get github.com/Ronniely/hello@latest
```

install cmd

go install github.com/Ronniely/hello/cmd/hello@latest
```

## Example

Here's a simple example as follows:

```go
package main

import (
  "fmt"
  "github.com/Ronniely/hello"
)

func main() {
  result := hello.Hello("jack")
  fmt.Println(result)
}
```