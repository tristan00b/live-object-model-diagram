# Live Object Model Diagram

*For Ableton Live v11.1*

## Features
- Responsive
- Works in dark mode
- Configurable colours (see `:root` selector under the `<style>` tag within the svg file). There are also more CSS classes available than are used within the current style, which can be exploited to further customize the colour scheme.

## Caveats
- I used Affinity Designer (1.10.5) to recreate the LOM diagram from Cycling74's Max For Live documentation. Affinity Designer doesn't handle masking the same way as is done in the svg standard. So the svg had to be edited by hand and does not display correctly when loaded into Affinity Designer. Likewise, Affinity Designer cannot export an svg that displays correctly in web browsers without rasterizing some sections of the graphic.

## Please contribute
- If you find an error, or want any improvements
- If you know how to fix the CSS within `LOM.html` so that the svg scales with browser zoom (I couldn't figure it out)
- If you know how to apply masks in Affinity Designer in a way that is non-descructive to the existing drawing elements and will display correctly in web browsers
