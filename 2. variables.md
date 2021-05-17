# Variables

## Declaration

```go
    // var variableName variableType

    var i int
    i = 42

    var a int = 42

    k := 100

    var (
        actorName string = "Micky Dola"
        actressName string = "Dandy Slow"
    )
```

## Visibility

- lowercase global variable names are scoped to package
- uppercase global variable names are available everywhere

## Naming convention

- length of variable name should tell you about life of variable
- camel case

## Conversions

Conversions are explicit

```go
    var i int = 42
    var j float32

    j = float32(i)
```

for conversions between numbers and strings, use `strconv` package
