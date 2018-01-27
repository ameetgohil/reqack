# Grapth, Node, Edge Labeling

## Graph
fhyper(label)
* `undefined`, `null` -> `{}`
* `String` -> `{label: <String>}`

## Nodes
node (label)
* `undefined`, `null` -> XOR
* `String` -> Operator
* `Object`
    * Name: String
    * ...
    * latency: Number (Int)
    * function?
* Function

## Edges
edge (label)
* `undefined`, `null` -> wire (sizable)
* `Number` (Int) -> width
* `Object`
    * name: string -> .toString()
    * capacity: Number (Int)
    * latency: Number (Int)
    * eager: bool
    * width: (undefined/Number)
