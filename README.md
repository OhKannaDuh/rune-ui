## Installation via NPM

`npm add https://github.com/OhKannaDuh/rune-ui`


## Usage

You can either just use the assets and style it yourself or use the provided style sheets.

You can import the three style sheets as needed:
```
@import "rune-ui/toolbar.css"
@import "rune-ui/content.css"
@import "rune-ui/button.css"
```

### Toolbar
The following html can be used for the header, I'd recommend adding the resize event to the divet, reposition event to the main and close event to the close.
```
<div class="toolbar">
   <div class="toolbar-divet"></div>
   <div class="toolbar-main"></div>
   <div class="toolbar-close"></div>
</div>
```

### Content
The `.content` class styles the element like the main section of an RS3 UI window.

The `.panel` class styles an element as a panel within the content interface, for example item's pinned in the activity tracker.

### Button
The `.button` class styles an element similar to the buttons at the bottom of RS3's inventory, equipment or prayer windows.

The `.button-border` class can be used to only add the border, this can be useful for making icon buttons similar to RS3s ribbon menu
