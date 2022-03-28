Headings
# Título h1
## Título h2
### Título h3
#### Título h4
##### Título h5
###### Título h6

# Negrito e italic
Este é um exemplo de um texto que possui uma ênfase em **negrito**, e outro em _itálico_.

# List
* Item 1
* Item 2
  * Item 2a
  * Item 2b

1. Item 1
2. Item 2
3. Item 3
   * Item 3a
   * Item 3b

# Links
[This link](http://example.net/) has no title attribute.

# References
This is [an example][id] reference-style link.

# Imagens
An image: ![gras](img/image.jpg)

# Blockquotes
> We're living the future so

# Tables
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

# Code
This is a sample code block.

    Continued here.


# Fenced code blocks
```
function test() {
  console.log("notice the blank line before this function?");
}
```

# Syntax highlighting
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

# Inline code
Use `honkit` to convert the `text` in markdown
syntax to HTML.

# Footnotes
Text prior to footnote reference.[^2]

[^2]: Comment to include in footnote.

# HTML
<div>
Markdown here will not be **parsed**
</div>

# Horizontal Rule

Three or more...

---

Hyphens

***

Asterisks


# Ignoring Markdown formatting
Let's rename \*our-new-project\* to \*our-old-project\*.