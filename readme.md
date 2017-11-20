```go

a := 43
fmt.Println(a) // 43
fmt.Println(&a) // 0x20818a220

var b *int = &a
fmt.Println(b) // 0x20818a220
fmt.Println(*b) // 43

*b = 42
fmt.Println(a) // 42


```
