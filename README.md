# gocyr

Converts string from Cyrillic to Latin and backward for Serbian language

## Documentation

[https://godoc.org/github.com/mileusna/gocyr]: https://godoc.org/github.com/mileusna/gocyr

## Examples

```Go
package main

import (
	"fmt"
	"github.com/mileusna/gocyr"
)

func main() {
    fmt.Println(gocyr.ToCyr("Kragujevac"))
    fmt.Println(gocyr.ToLat("кошарка"))
    fmt.Println(gocyr.FixDj("Novak Djoković"))
    fmt.Println(gocyr.HtmlToCyr("<h1><a href='http://naslovi.net/'>Vesti dana</a></h1>"))
}
```
