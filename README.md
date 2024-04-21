### Marketing for Isso

At the moment, this repo serves mostly to document how to (re-) create the
screenshot used in Isso's README.

---

## How to recreate screenshot for README

- `comments.db` has example.data
- Text is:
  ```
  Type comment here. You can use *italics*, **bold**, `code blocks` and links
  with [markdown](https://daringfireball.net/projects/markdown/) syntax.`
  ```
- Width of `#wrapper` set to `720px`
- `font-family: "IBM Plex Sans` or `Cantarell`
- GIMP border: `1px #e2e2e2`

## How to recreate Isso logo with border

`convert -bordercolor white -border 35 isso.svg isso-border.png`
