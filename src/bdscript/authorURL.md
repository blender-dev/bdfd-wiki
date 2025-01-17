# $authorURL
Adds a hyperlink to the author text.

## Syntax
```
$authorURL[URL;(Index)]
```
> `$authorURL[]` will not work if there is no text provided in [`$author[]`](./author.md).

### Parameters
- `URL` `(Type: URL || Flag: Emptiable)`: The link to set as the author hyperlink.
- `Index` `(Type: Integer || Flag: Optional)`: To which embed the author URL will be added. [(learn more)](../resources/embedIndexes.md)

## Example
```
$nomention
$author[Click me to visit the BDFD website!]
$authorURL[https://botdesignerdiscord.com]
```
![example](https://user-images.githubusercontent.com/113303649/209984969-3f5c56e6-5817-4acf-b2df-37bf237d00df.png)
