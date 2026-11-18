# Notes

## Next Step
**S3:** slices, maps, structs

## Learned

### Session 2
- predeclared types have zero values (default), the is no None
- short declaration, `:=` infers the type (inside functions only)
- no implicit conversion, i.e. things like `int * float64` won't compile
- untyped constants adapt to where they're used (e.g. they could be `int` or `float64`)
- strings are bytes; `len` counts bytes, not characters
- fixed-size integers wrap around

### Session 1
- go run compiles to a temp dir; go build leaves a binary
- unused imports and variables are compile errors