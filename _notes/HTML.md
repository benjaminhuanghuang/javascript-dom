## Nodes vs Elements

All HTML elements are nodes. Every node is not an HTML element

Node是一个基类，DOM中的Element，Text和Comment都继承于它。
Element，Text和Comment是三种特殊的Node，它们分别叫做ELEMENT_NODE, TEXT_NODE和COMMENT_NODE

A node can be a number of different kinds of things: some text, a comment, an element, an entity, etc. An element is a particular kind of node.

```
  var x = document.getElementById("myP").nodeType;   // 1: ELEMENT_NODE
  var y = document.nodeType ;                        // 9: DOCUMENT_NODE
```

## Ancestor, Descendant and sibling

