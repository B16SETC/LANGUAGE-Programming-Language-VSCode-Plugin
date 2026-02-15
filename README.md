# LANGUAGE VS Code Extension

Syntax highlighting for the [LANGUAGE programming language](https://github.com/B16SETC/LANGUAGE-Programming-Language).

## Features

- Syntax highlighting for all LANGUAGE keywords
- String highlighting with escape sequence support
- Comment highlighting (`#` toggle syntax)
- Number literals
- Boolean constants (`True`, `False`)
- Function definitions and calls
- Logical operators (`And`, `Or`, `Not`)
- Auto-closing brackets and quotes
- Auto-indentation for blocks

## Supported Keywords

| Category | Keywords |
|----------|----------|
| Control Flow | `If`, `Elif`, `Else`, `While`, `For`, `To`, `End`, `Return` |
| Functions | `Func` |
| Logical | `And`, `Or`, `Not` |
| Built-ins | `Print`, `Push`, `Pop`, `Length`, `Upper`, `Lower`, `Contains`, `Substring` |
| Constants | `True`, `False` |

## File Extension

Files with the `.LANGUAGE` extension are automatically detected.

## Example

```language
# This is a comment #
Func greet(name)
  greeting = "Hello " + name
  Print greeting
End

For i = 1 To 5
  greet("World")
End
```

## Links

- [LANGUAGE Repository](https://github.com/B16SETC/LANGUAGE-Programming-Language)
- [Report Issues](https://github.com/B16SETC/LANGUAGE-Programming-Language-VSCode-Plugin/issues)

## License

MIT
