# bcd

Go implementation of BCD conversion functions

## Usage

```go
package main

import (
	"fmt"
	"github.com/johnsonjh/gobcd"
)

func main() {
	fmt.Printf("Uint32: %d", bcd.ToUint32([]byte{0x11, 0x22, 0x33, 0x44}))
	fmt.Printf("BCD: %x", bcd.FromUint32(11223344))
}
```
