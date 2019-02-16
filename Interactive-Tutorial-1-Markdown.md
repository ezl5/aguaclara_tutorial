# Interactive Tutorial 1: Markdown

## Working with Markdown

Press `Ctrl + Shift + M` to open a formatted preview on the right.

## Basic Text

Write two sentences about yourself, each in a different paragraph.

I like pandas.

Pandas like me.

## Headers

Make a 3rd level header with your name:

# Emily
## Emily
### Emily

## Emphasis

Write 4 of your favorite words using each type of emphasis:

*Avatar*
**the**
***Last***
~~Airbender~~

## Lists

Make an ordered list of 3 things you hope to achieve this semester, and elaborate on them with sub items. Then, make an unordered list of 3 classes that you're taking this semester:

1. Maintain my academic and social life
2. Learn
3. Have fun

- Baby Orgo
- Immigrants and Immigration
- CEE 3510

## Links

Write a sentence describing your major, and insert a link to your major's department website:

[Environmental Engineers engineer the environment.](https://www.cee.cornell.edu/cee)

## Images

Insert the Cornell seal image with:
  1. A relative file path(`/images/Cornell_University_seal.png`)
  2. A URL (https://raw.githubusercontent.com/AguaClara/aguaclara_tutorial/master/Images/Cornell_University_seal.svg.png)

![a URL](https://images.ecosia.org/LPj42R0GlqvilleKGe0BzUwyzAk=/0x390/smart/https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2Fthumb%2F4%2F47%2FCornell_University_seal.svg%2F1200px-Cornell_University_seal.svg.png)

![relative file path](/images/Cornell_University_seal.png)


## Code Formatting

Put the name of this file in an in-line (single backtick) code format.

`Interactive-Tutorial-1-Markdown.md`

Put the following text in a Python-formatted code block:

```
def foo():
    print("Particles of a feather...")
    print("...floc together!")
```

```Python
def foo():
    print("Particles of a feather...")
    print("...floc together!")
```

## Tables

Create a table listing your 3 favorite animals, books, and places on campus. Use a different alignment for each column.

| Animals | Books | Places on Campus |
| --- | :---: | ---: |
| Pandas | Pendragon | Top of the Slope |
| Geckos | Iron Fey | PSB |
| Rabbits | Scenes of Subjugation | Bethe |


## Blockquotes

Write your favorite quote. It must be attributed to Albert Einstein.

> Try not to become a man of success, but rather try to become a man of value

## Horizontal Rules

Add a horizontal rule:

---

## LaTeX Formatting

Copy the equation towards the end of the [Markdown tutorial](https://github.com/AguaClara/aguaclara_tutorial/wiki/Markdown#latex-formatting) and paste it here:

$$ a^2 + b^2 = c^2 $$
