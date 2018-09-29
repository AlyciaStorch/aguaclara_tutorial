# Interactive Tutorial 1: Markdown

## Working with Markdown

Press `Ctrl + Shift + M` to open a formatted preview on the right.

## Basic Text

Write two sentences about yourself, each in a different paragraph.

My name is Aly, I am from New Jersey.

I have a dog named Ivy.

## Headers

Make a 3rd level header with your name:

###Aly

## Emphasis

Write 4 of your favorite words using each type of emphasis:

*Vestibule*
**Coconut**
***Emphatic***
~~Categorically~~

## Lists

Make an ordered list of 3 things you hope to achieve this semester, and elaborate on them with sub items. Then, make an unordered list of 3 classes that you're taking this semester:

1. Get really good at OnShape!
2. Work Efficiently
  1. Come up with clear and logical direction of work
3. Learn more about the entire plant

* Mechatronics
* Fluids
* Stats


## Links

Write a sentence describing your major, and insert a link to your major's department website:

My major is mechanical engineering and you can find out more about it [here](http://www.mae.cornell.edu/).

## Images

Insert the Cornell seal image with:
  1. A relative file path(`/Images/Cornell_University_seal.png`)
  2. A URL (https://raw.githubusercontent.com/AguaClara/aguaclara_tutorial/master/Images/Cornell_University_seal.svg.png)

![CornellSeal](/Images/Cornell_University_seal.png)

<img src="https://raw.githubusercontent.com/AguaClara/aguaclara_tutorial/master/Images/Cornell_University_seal.png">

## Code Formatting

Put the name of this file in an in-line (single backtick) code format.

`Interactive-Tutorial-1-Markdown.md`

Put the following text in a Python-formatted code block:

```
def foo():
    print("Particles of a feather...")
    print("...floc together!")
```

```python
def foo():
    print("Particles of a feather...")
    print("...floc together!")
```

## Tables

Create a table listing your 3 favorite animals, books, and places on campus. Use a different alignment for each column.

| Animal  | Foods    | Books | Places on campus |
|:------- |:--------: | :-----: | ----------------: |
| Penguin | Ice Cream |The Hate You Give| My room!      |
| Dog     | Tacos       | Kabul Beauty School | Ag Quad     |
|Giraffe     |Bell Peppers  |The Heart of a Woman| Slope (except when I'm walking up it)|


## Blockquotes

Write your favorite quote. It must be attributed to Albert Einstein.

> Imagination is more important than knowledge
> -Albert Einstein

## Horizontal Rules

Add a horizontal rule:

---

## LaTeX Formatting

Copy the equation towards the end of the [Markdown tutorial](https://github.com/AguaClara/aguaclara_tutorial/wiki/Markdown#latex-formatting) and paste it here:

$$ a^2 + b^2 = c^2 $$
