# color-palette-picker for bootstrap 4
Simple color palette picker for bootstrap

## Usage:

```html
<div id="colorpalettediv"></div>
```
```javascript
$('#colorpalettediv').colorPalettePicker();
```
## Options

Name|Type|Default|Description
---|---|---|---
lines|int|1|Number of rows to be divided palette array
palette|array|['aqua', 'azure', 'beige', 'brown', 'cyan', 'darkcyan', 'darkgrey', 'darkkhaki', 'darkorange', 'darkorchid', 'darksalmon', 'fuchsia', 'gold', 'green', 'khaki', 'lightblue', 'lightcyan', 'lightgreen', 'lightgrey', 'lightpink', 'lightyellow', 'lime', 'magenta', 'olive', 'orange', 'pink', 'silver', 'yellow']|List of colors to choose from
buttonText|string|Choose color|
buttonClass|string|btn btn-secondary dropdown-toggle|
dropdownTitle|string|Available colors|

## Methods

```
onSelected
```
Return chosen color 

```javascript
$('#colorpalettediv').colorPalettePicker({
  onSelected: function(color){
		alert(color);
	}
});
```
