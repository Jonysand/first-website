# First Website for Cheese

![Logo](./logo.svg)

## About

The Good Project Readme Project is a project about about how to make a good Readme so that you can keep your projects well documented and allow yourself and others to build on or learn from your work. The project is meant to be an example for others to learn by example and see what aspects might be necessary for a good readme.

This is an album page to present my pet cat ---- Cheese. The webpage is writen just with HTML and CSS

## Setup

To view the page, simply clone the project and open the html file. Or you can click [here](https://jonysand-first-website.glitch.me) to view the page deployed on Glitch.

### Deployment

This project is hosted on Github. Github renders markdown files.

## Built with

* [VS Code](https://code.visualstudio.com/)
* [Github](https://github.com)

## Authors

* [Yongkun Li](https://jonysandyk.com)

# Notes & Process

## Process & Documentation

Since I can only use HTML and CSS, at first I thought I can only make static page. So after consideration I decided to show some pictures of my cat. The goal is to put the pictures in timeline and viewers can scroll down to see pictures.

## Challenges & Struggles

### Center Aligning

Though seems easy, this is a tough task for me. I want to put the title pictures through along with the time line, which means that I need to put then slightly away from the center. To do this, the first step is to put everything presented in the timeline in a `<div>`, then style this `<div>` alining to the center by `text-align: center;`, which means everything in this `<div>` is aligned to center. Then for every individual picture, I add offset as setting `left: 15%;` or `left: -15%;`.

### Linked Styles

Since in my page pictures are shown in a similar style, I use linked styles to format them. To do this I created an external `css` file to describe all the format I want. To mark which kind of element the style to be applied, I use  "Class Selectors". In this way I don't have to paste style code to each individual tag.

### A vertical line in the middle

I googled online then get this code to get a vertical line in the back ground:

```css
background: linear-gradient(#dddddd, #dddddd) no-repeat center/2px 100%;
```

The code means to set a line of color `#dddddd`, with no repetition, in the center, with 2px width, with the same(100%) height of the page.

## Questions

## References

* Author First Name, Author Last Name. [Link]()
* Author First Name, Author Last Name. [Link]()