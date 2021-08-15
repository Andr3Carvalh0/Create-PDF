# Create PDF
Automator workflow for converting SVG to PDF using automator script for macOS.
In Finder, select the svgs you want to convert, right click, and select Pdfify.
Perfect to convert SVGs exported by Figma for iOS projects.

<img src="Screenshot.png?raw=true" alt="screenshot"/>

Uses rsvg-convert internally for conversion.

Use homebrew to install rsvg-convert:

```
brew install librsvg
```

