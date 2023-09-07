package main

import "github.com/01-edu/z01"

func IsNegative(nb int) {
	if nb < 0 {
		z01.PrintRune('T')
	} else {
		z01.PrintRune('F')
	}
	z01.PrintRune('\n')
}
func main() {
	IsNegative(1)
	IsNegative(1)
	IsNegative(-1)
}
## isnegative

### Instructions

Write a function that prints `'T'` (true) on a single line if the `int` passed as parameter is negative, otherwise it prints `'F'` (false).

### Expected function

```go
func IsNegative(nb int) {

}
```

### Usage

Here is a possible program to test your function :

```go
package main

import "piscine"

func main() {
	piscine.IsNegative(1)
	piscine.IsNegative(0)
	piscine.IsNegative(-1)
}
```

And its output :

```console
$ go run .
F
F
T
$
```

### Notions

- [01-edu/z01](https://github.com/01-edu/z01)
