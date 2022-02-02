# Zoom and Resizing Text Testing

## Common Issues Identified During Zoom and Resizing Text Testing
- Horizontal Scrollbar. Content on the page should reflow rather than be lost outside the viewport when zooming in.
- Truncated, Obscured, and Overlapping Text. This issue can occur if the overflow property of the enclosing element has been set to hidden, when using absolute positioned content, or when creating modal dialogs that aren't big enough for their content at the new font size. 
- Images of Text. Watch for images of text on pages. These images usually don't resize well for low vision users and can become blurry on zoom.
- Low Res Images. Watch for low res images as well that become blurry upon Zoom. 

## Testing Resources by Browser
- [Chrome: zoom and set font size](https://support.google.com/chrome/answer/96810?hl=en)
- [Firefox: font size and zoom](https://support.mozilla.org/en-US/kb/font-size-and-zoom-increase-size-of-web-pages)
- [Microsoft Edge: making text larger](https://support.microsoft.com/en-us/microsoft-edge/increase-default-text-size-in-microsoft-edge-c62f80af-381d-0716-25a3-c4856dd3806c#:~:text=Select%20Settings%20and%20more%20%3E%20Settings,Fonts%2C%20choose%20a%20font%20size.)
- [Safari: changing font size and zoom level](https://support.apple.com/en-us/HT207209)
