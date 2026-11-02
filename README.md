# CHXD FONT FAMILY

CHXD Font Family is a collection of custom pictographic fonts created by CHXD17.

Each font family represents a different icon category. Instead of searching for Unicode characters or manually inserting SVG files, you can simply type a keyboard character to display an icon.

Designed for code editors, file managers, software interfaces, and other applications.

**GitHub:** https://github.com/cardhollow/font-icon  
**Font Viewer:** https://cardhollow.github.io/font-icon

---

# Development Reason

I've been using Unicode characters for icons in my editor for a while. But every time I needed one, I had to find a character that matched what I wanted.

Sometimes I couldn't find the right one. Other times, I had to compromise because the available Unicode symbols didn't really match the icon I needed.

I also used SVG files whenever Unicode wasn't enough. They gave me more freedom, but managing and inserting them into my projects wasn't always convenient.

Then I thought:

**Why not create my own font?**

I already had a collection of SVG icons that I created previously. Instead of continuing to use them as separate files, I decided to convert them into font glyphs.

That way, I could just type a character on my keyboard and get the icon I wanted.

No more searching for a Unicode character that almost matches. No more compromising on the appearance. Just my own icons, accessible through my own fonts.

---

# Font Families

Each icon category has its own independent font family.

The naming convention is:

`CHXD <CATEGORY>`

Examples:

- CHXD Editing
- CHXD Drawing
- CHXD Media
- CHXD Navigation
- CHXD File Operations
- CHXD UI Controls

Each category uses its own font. This means the same keyboard character can represent different icons depending on the selected font.

For example:

| Character | CHXD Editing | CHXD File Operations |
|:---:|---|---|
| A | Edit | Delete |
| B | Copy | Rename |
| C | Cut | Move |

Simply change the selected font family to switch between icon categories.

---

# Character Mapping

The fonts use ordinary keyboard characters as icon mappings.

Supported characters include:

- Lowercase letters: `a-z`
- Uppercase letters: `A-Z`
- Numbers: `0-9`
- Common keyboard symbols and punctuation

Characters are assigned based on the icon's name, meaning, appearance, or whichever mapping makes the most sense.

Each category has its own character mapping, so the same character can display a different icon in another CHXD font.

---

# Installation

Install the `.ttf` fonts you want to use through your operating system's font installation process.

Once installed, select the desired CHXD font in your application and type the assigned characters to display their icons.

For ordinary text, switch back to your usual font.

---
# CSS IMPORT
```css sample
   @font-face { font-family: "CHXD Bags and Storage"; src: url("fonts/bags_and_storage.ttf") format("truetype"), url("https://cdn.jsdelivr.net/gh/cardhollow/font-icon@main/fonts/bags_and_storage.ttf") format("truetype"); font-display: swap; }
    @font-face { font-family: "CHXD Code Editor"; src: url("fonts/code_editor.ttf") format("truetype"), url("https://cdn.jsdelivr.net/gh/cardhollow/font-icon@main/fonts/code_editor.ttf") format("truetype"); font-display: swap; }
    @font-face { font-family: "CHXD Design Tools"; src: url("fonts/design_tools.ttf") format("truetype"), url("https://cdn.jsdelivr.net/gh/cardhollow/font-icon@main/fonts/design_tools.ttf") format("truetype"); font-display: swap; }
    @font-face { font-family: "CHXD Documents and Media"; src: url("fonts/documents_and_media.ttf") format("truetype"), url("https://cdn.jsdelivr.net/gh/cardhollow/font-icon@main/fonts/documents_and_media.ttf") format("truetype"); font-display: swap; }
    @font-face { font-family: "CHXD Editing"; src: url("fonts/editing.ttf") format("truetype"), url("https://cdn.jsdelivr.net/gh/cardhollow/font-icon@main/fonts/editing.ttf") format("truetype"); font-display: swap; }
    @font-face { font-family: "CHXD File Management"; src: url("fonts/file_management.ttf") format("truetype"), url("https://cdn.jsdelivr.net/gh/cardhollow/font-icon@main/fonts/file_management.ttf") format("truetype"); font-display: swap; }
    @font-face { font-family: "CHXD File Operations"; src: url("fonts/file_operations.ttf") format("truetype"), url("https://cdn.jsdelivr.net/gh/cardhollow/font-icon@main/fonts/file_operations.ttf") format("truetype"); font-display: swap; }
    @font-face { font-family: "CHXD Media"; src: url("fonts/media.ttf") format("truetype"), url("https://cdn.jsdelivr.net/gh/cardhollow/font-icon@main/fonts/media.ttf") format("truetype"); font-display: swap; }
    @font-face { font-family: "CHXD Miscellaneous"; src: url("fonts/miscellaneous.ttf") format("truetype"), url("https://cdn.jsdelivr.net/gh/cardhollow/font-icon@main/fonts/miscellaneous.ttf") format("truetype"); font-display: swap; }
    @font-face { font-family: "CHXD Navigation"; src: url("fonts/navigation.ttf") format("truetype"), url("https://cdn.jsdelivr.net/gh/cardhollow/font-icon@main/fonts/navigation.ttf") format("truetype"); font-display: swap; }
    @font-face { font-family: "CHXD Sorting and Views"; src: url("fonts/sorting_and_views.ttf") format("truetype"), url("https://cdn.jsdelivr.net/gh/cardhollow/font-icon@main/fonts/sorting_and_views.ttf") format("truetype"); font-display: swap; }
    @font-face { font-family: "CHXD Text Editor"; src: url("fonts/text_editor.ttf") format("truetype"), url("https://cdn.jsdelivr.net/gh/cardhollow/font-icon@main/fonts/text_editor.ttf") format("truetype"); font-display: swap; }
    @font-face { font-family: "CHXD UI Controls"; src: url("fonts/ui_controls.ttf") format("truetype"), url("https://cdn.jsdelivr.net/gh/cardhollow/font-icon@main/fonts/ui_controls.ttf") format("truetype"); font-display: swap; }
```
---

# Font Viewer

You can preview and test the fonts here:

https://cardhollow.github.io/font-icon

The viewer lets you browse categories, inspect icons and their assigned characters, search for icons, and type characters to preview their glyphs.

---

# Credits
GitHub: https://github.com/cardhollow/font-icon

Website: https://cardhollow.github.io

Copyright © 2026 CHXD17. All rights reserved.
