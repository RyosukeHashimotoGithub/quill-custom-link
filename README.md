# quill-custom-link
Customize tooltip for snow theme.

## Usage

```
import Quill from "quill";
import CustomSnowTheme, { CustomSnowTooltip } from "./CustomSnowTheme";

CustomSnowTooltip.TEMPLATE = [
  // Edit here!
  '<a class="ql-preview" target="_blank" href="about:blank"></a>',
  '<input type="text" data-formula="e=mc^2" data-link="https://quilljs.com" data-video="Embed URL">',
  '<a class="ql-action"></a>',
  // ...
].join("");

Quill.register("themes/CustomSnowTheme", CustomSnowTheme);
```
