# Editor

- [CommonMark](http://commonmark.org/) ([npm:commonmark](https://www.npmjs.com/package/commonmark))

| Type    | Code                               | Code (ast renderer)                | Code (html renderer)                     |
|---------|------------------------------------|------------------------------------|------------------------------------------|
| Mention | `@username`                        | `<@username>`                      | `[@username](/users/username)`           |
| Sticker | `:sticker-name:`                   | `![](omega:sticker/sticker-name)`  | `![](/upload/stickers/sticker-name.png)` |
| Media   | `![file-name](omega:file/file-id)` | `![file-name](omega:file/file-id)` | `[file-name](/upload/files/file-id)`     |
