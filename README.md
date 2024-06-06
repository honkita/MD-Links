[![](https://raw.githubusercontent.com/honkita/MD-Links/main/Pixel_GitHub.svg)](https://github.com/honkita) [![](https://raw.githubusercontent.com/honkita/MD-Links/main/Pixel_Link.svg)](https://elitelu.com) [![](https://raw.githubusercontent.com/honkita/MD-Links/main/Pixel_LinkedIn.svg)](https://www.linkedin.com/in/elitelu/)

# Pixel Buttons for README

## How to use

Replace the **NAME_OF_BUTTON** with the button name and **LINK** that when the button is pressed, redirects to the site/location.

### Markdown

Note that the default height of a button is 32px x 32px. To change the width/height, refer to the HTML code.

```
[![](https://raw.githubusercontent.com/honkita/PixelButtons/main/NAME_OF_BUTTON.svg)](https://github.com/honkita)
```

<h3> HTML </h3>

```
  <a href=LINK>
      <img title="NAME_OF_BUTTON" src="https://raw.githubusercontent.com/honkita/MD-Links/main/NAME_OF_BUTTON.svg">
  </a>
```

Note that the button is an \<img\> tag wrapped in an \<a\> tag. Below are some recommended settings:

| Variable | Use Case                                                                                                   |
| -------- | ---------------------------------------------------------------------------------------------------------- |
| target   | On click, does the link open a new tab or stay on the same tag. "\_blank" for new tab and "" for same tab. |
| width    | Width of the button.                                                                                       |

## Button Types

| Image                                                                           | Name           |
| ------------------------------------------------------------------------------- | -------------- |
| ![](https://raw.githubusercontent.com/honkita/MD-Links/main/Pixel_GitHub.svg)   | Pixel_GitHub   |
| ![](https://raw.githubusercontent.com/honkita/MD-Links/main/Pixel_Link.svg)     | Pixel_Link     |
| ![](https://raw.githubusercontent.com/honkita/MD-Links/main/Pixel_LinkedIn.svg) | Pixel_LinkedIn |
