## style_formats_autohide

This option enables auto hiding of styles that doesn't match the current context. That means if you have a style for tables only it wouldn't be visible in the styles drop down when the caret isn't inside a table.

**Type:** `Boolean`
**Defaults:** `False`

##### Example

```js
tinymce.init({
  selector: 'textarea',
  style_formats: [
    {title: 'Red cell', selector: 'td', classes: 'red'},
    {title: 'Red text', inline: 'span', styles: {color: '#ff0000'}}
  ],
  style_formats_autohide: true
});
```
