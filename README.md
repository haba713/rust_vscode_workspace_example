If you open [example.code-workspace](example.code-workspace) in VSCode, 
[rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)
plugin should show the following error but it doesn't.

```
error: expected one of `!`, `.`, `::`, `;`, `?`, `{`, `}`, or an operator, found `line`
 --> src/lib.rs:2:10
  |
2 |     This line should cause a compile-time error.
  |          ^^^^ expected one of 8 possible tokens
```
