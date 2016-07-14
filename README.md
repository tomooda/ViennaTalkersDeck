# Presentation
Presentation is a package to use Webly Walk-Through as a presentation tool.

#Setup

## Load the spec

Open a webly walk-through and load the Presentation.vdmsl

## Translation rule

Type the following into the Web API tab.

```
mk_SlideInfo($page, $slide) <=> {"page":$page, "slide": $slide}
```

## Open the slide

Open the index.html in a web browser.
