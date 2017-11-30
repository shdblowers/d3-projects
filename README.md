# d3-projects

## About D3

### Selecting elements

#### CSS3 selectors

CSS3 selector can be used to select an element based on the tag, class or id.

| Selector | Code            |
| -------- | --------------- |
| tag      | div             |
| class    | .myContainer    |
| id       | #firstContainer |

#### d3.select

Creates a selection with the first element that matches the selector.

`d3.select("div")` will match the first `div` element that it finds.

#### d3.selectAll

Like `d3.select` but will get all nodes that match the selection, even if they
are nested.

#### Chaining

Selections can be chained: `d3.select("#main").selectAll("p")`.

#### Getting the nodes

With any selection you can call `.nodes()` to get all the actual nodes. Example:
`d3.select(".centered").nodes()`
