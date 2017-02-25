# attribute-editor
A webcomponent that lets authors edit inline attributes on the user components.

## Installation

```shell
bower install --save pancake-cms-attribute-editor
```

## Attributes

| name | description |
|------|-------------|
| path | The path of the node |
| contentId | The content id of the user content |
| usercontent | The usercontent inside contentId node |

## Events

The element triggers a `value-changed` event. You can get the value of `usercontent` from it.