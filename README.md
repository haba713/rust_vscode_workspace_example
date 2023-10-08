If you open [example.code-workspace](example.code-workspace) in VSCode, 
[rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)
plugin should show the error below but it doesn't. It does if you open the
folder [lib1](lib1) in VSCode.

```
error: expected one of `!`, `.`, `::`, `;`, `?`, `{`, `}`, or an operator, found `line`
 --> src/lib.rs:2:10
  |
2 |     This line should cause a compile-time error.
  |          ^^^^ expected one of 8 possible tokens
```
