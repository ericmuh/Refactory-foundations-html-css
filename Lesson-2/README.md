# In this lesson we looked at 
1. lists
2. images

## HTML Lists
HTML lists are used to organize and group related content together. 
There are two types of lists in HTML: unordered lists (bulleted lists) and ordered lists (numbered lists).
### Unordered Lists

Unordered lists are created using the `<ul>` element. Each list item is represented by the `<li>` element.

```html

<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
```

### Ordered Lists

Ordered lists are created using the `<ol>` element. Each list item is represented by the `<li>` element

```html

<ol>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ol>
```

## HTML Images
HTML images are added using the `<img>` element. The src attribute is used to specify the URL of the image file. The alt attribute is used to provide alternative text for the image, in case the image cannot be displayed

##### image tag
`<img src="image.jpg" alt="A beautiful sunset"> `

You can also set the size of the image using the width and height attributes.
`<img src="image.jpg" alt="A beautiful sunset" width="400" height="300">`

You can also make the image a link by wrapping it in an `<a>` element.

```html <a href="https://www.example.com">
  <img src="image.jpg" alt="A beautiful sunset">
</a>```
