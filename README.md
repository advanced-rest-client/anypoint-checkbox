[![Build Status](https://travis-ci.org/advanced-rest-client/anypoint-checkbox.svg?branch=stage)](https://travis-ci.org/advanced-rest-client/anypoint-checkbox)  

# anypoint-checkbox

`<anypoint-checkbox>` is a button that can be either checked or unchecked.
User can tap the checkbox to check or uncheck it.  Usually you use checkboxes
to allow user to select multiple options from a set.

Avoid using a single checkbox as an option selector and use toggle button intead.

### Example
```
<anypoint-checkbox>label</anypoint-checkbox>
<anypoint-checkbox checked>label</anypoint-checkbox>
```

### Styling
`<anypoint-checkbox>` provides the following custom properties and mixins for styling:

Custom property | Description | Default
----------------|-------------|----------
`--anypoint-checkbox` | Mixin applied to the element | `{}`
`--anypoint-checkbox-input-border-bolor` | Border color of the checkbox input square | `--anypoint-color-aluminum4`
`--anypoint-checkbox-label-color` | A color of the label. | ` --anypoint-color-steel1`
`--anypoint-checkbox-label` | Mixin applied to the label | ``
`--anypoint-checkbox-label-checked-color` | Color of checked label | `--anypoint-checkbox-label-color` or `--anypoint-color-steel1`
`--anypoint-checkbox-label-checked` | Mixin applie dto checked label | ``
`--anypoint-checkbox-unchecked-color` | Color of a label of unchecked checkbox | `--anypoint-checkbox-label-color` or `--anypoint-color-steel1`
`--anypoint-checkbox-error-color` | Color of error state | `--anypoint-color-danger`



### Events
| Name | Description | Params |
| --- | --- | --- |
| change | Fired when the checked state changes due to user interaction. | __none__ |
| iron-change | Fired when the checked state changes. | __none__ |
