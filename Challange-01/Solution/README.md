# Challange 1

# Solution to this challage is available at https://ruchiagarwal26.github.io/Ruchi_bootcamp/Challange-01/Solution/


## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Solution:

#### Index.html file changes:

a) updated <head> by redefining the title and rearranging it above link

b) updated class "hero" with adding link of the image

c) Added 'alt' condition to all the images and links in the file

#### style.css file changes:

a) rearranged the styles in the correct orders
b) reduced code redundancy by adding div.class > * for similar code that needs to be applied to all the similar elements in parent class