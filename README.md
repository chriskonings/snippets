# Snippets

## A collection of my favourite code, including native functions, methods, and CSS properties.

# CSS

[Object-fit](https://developer.mozilla.org/en-US/docs/Web/CSS/object-fit)

The object-fit CSS property specifies how the contents of a replaced element, such as an <img> or <video>, should be resized to fit its container.

[Working example](https://twitter.com/wesbos/status/977223833206829056)

# JS

If object doesn't exist create one

`if (!obj[d]) {
  obj[d] = {}
  obj[d][n.subject] = {id: n.id, views: n.views}
} else {
  obj[d][n.subject] = {id: n.id, views: n.views}
}`

Is the same as:

`const day = obj[d] || (obj[d] = {})
day[n.subject] = {id: n.id, views: n.views}
`
