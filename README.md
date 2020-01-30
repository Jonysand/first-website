# First Website for Cheese
> This is a photo album page for my pet Cheese.

<!-- vim-markdown-toc GFM -->

* [Usage](#usage)
* [Logs](#logs)
	* [Linked Styles](#linked-styles)
	* [A vertical line in the middle](#a-vertical-line-in-the-middle)

<!-- vim-markdown-toc -->

## Usage
Just simply click the [link](https://jonysand-first-website.glitch.me) here, and you will see my cute cat!

## Logs

### Linked Styles
Since in my page pictures are shown in a similar style, I use linked styles to format them. To do this I created an external `css` file to describe all the format I want. To mark which kind of element the style to be applied, I use  "Class Selectors". In this way I don't have to paste style code to each individual tag.

### A vertical line in the middle
I googled online then get this code to get a vertical line in the back ground:

```html
background: linear-gradient(#dddddd, #dddddd) no-repeat center/2px 100%;
```

The code means to set a line of color `#dddddd`, with no repetition, in the center, with 2px width, with the same(100%) height of the page.


