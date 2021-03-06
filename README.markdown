# TextMate Snippets
These are bits of code that I use and reuse often. They speed up development and help to keep my coding practices consistent. It's very easy to install one or more of them into your workflow:

1. You must use [TextMate](http://macromates.com). I wrote the snippets myself; but they're exported from TextMate, so I don't know if they'll work with another editor.
2. Download this repository. Cloning it probably won't help much - just download the source.
3. Navigate the topic areas in your downloaded folder to find a snippet you think might improve your workflow.
4. Double-click to install each snippet you have a crush on. You're done.

## Documentation
Here's a quick rundown of what each snippet does:

- Refresh Running Browser(s) - Hit `CMD` + R to refresh running browsers. This is part of the HTML bundle that comes with TextMate, but it doesn't work properly if you use the Webkit Nightly instead of Safari. My version fixes that.

### CSS
- Reset Styles - Type `reset` and hit TAB to insert some CSS reset styles (my own blend - kind of a mix of YUI and Eric Meyer's)

### Javascript
- jQuery Scope - Type `q` and hit TAB to insert an anonymous function that's automatically bound to $(document).ready(). I put all of my jQuery goodness inside of this.
- jQuery Selector - Type `$` and hit TAB to insert a blank jQuery selector. The cursor focus moves into the quotes. Example: `$` + `TAB` + `#someId` results in `$('#someId')`.
- jQuery Plugin - Type `jp` and hit TAB to insert a jQuery plugin template. *(Credit: [kneath](http://github.com/kneath/textmate-snippets))*
- Write to Console - Type `c` and hit TAB to insert `console.log('');` for debugging and whatnot.

### Markdown
- Add Footnote - Type `^` and hit TAB to insert a reference and footnote. After hitting TAB, you type the number of the reference. This is one of my favorites.
- Insert Image - Type `img` and hit TAB to insert an image.
- Insert Link - Type `a` and hit TAB to insert a link.