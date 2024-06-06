<style>
  header1 {
    margin-top: 0.5rem;
    font-family: "Calibri", sans-serif;
    font-size: 2rem;
    margin-bottom: 0.5rem;
  }

  header2 {
    margin-top: 0.5rem;
    margin-bottom: 0.5rem;
    font-family: "Calibri", sans-serif;
    font-size: 1.75rem;
  }

  header3 {
    margin-top: 0.5rem;
    margin-bottom: 0.5rem;
    font-family: "Calibri", sans-serif;
    font-size: 1.5rem;
  }

  body-text {
    font-family: "Calibri", sans-serif;
    font-size: 1rem;
    margin-bottom: 0.5rem;
  }

  table {
    font-family: "Calibri", sans-serif;
    border-collapse: collapse;
    width: 100%;
  }

  td,
  th {
    border: 1px solid #dddddd;
    text-align: left;
    padding: 8px;
  }

  td:first-child {
  font-weight: bold;
  width: 25%;
}

  tr:nth-child(even) {
    background-color: #dddddd;
  }

</style>

<div align="center">
    <a href="https://github.com/honkita">
        <img title="GitHub" src="https://raw.githubusercontent.com/honkita/MD-Links/main/Pixel_GitHub.svg">
    </a>
    <a href="https://elitelu.com">
        <img title="Link" src="https://raw.githubusercontent.com/honkita/MD-Links/main/Pixel_Link.svg">
    </a>
    <a href="https://www.linkedin.com/in/elitelu/">
        <img title="LinkedIn" src="https://raw.githubusercontent.com/honkita/MD-Links/main/Pixel_LinkedIn.svg">
    </a>
</div>

<header1> Pixel Buttons for README </header1>

<header2> How to use </header2>

<body-text>
Replace the **NAME_OF_BUTTON** with the button name and **LINK** that when the button is pressed, redirects to the site/location.
</body-text>

<header3> Markdown </header3>

<body-text>
Note that the default height of a button is 32px x 32px. To change the width/height, refer to the HTML code.
<body-text>

<pre>
[![](https://raw.githubusercontent.com/honkita/PixelButtons/main/NAME_OF_BUTTON.svg)](https://github.com/honkita)
</pre>

<header3> HTML </header3>

<pre>
  &lta href=LINK&gt
      &ltimg title="NAME_OF_BUTTON" src="https://raw.githubusercontent.com/honkita/MD-Links/main/NAME_OF_BUTTON.svg"&gt
  &lt/a&gt
</pre>

Note that the button is an \<img\> tag wrapped in an \<a\> tag. Below are some recommended settings:

<table>
  <tr>
    <th>Variable</th>
    <th>Use Case</th>
  </tr>
  <tr>
    <td>target</td>
    <td>On click, does the link open a new tab or stay on the same tag. "_blank" for new tab and "" for same tab. </td>
  </tr>
  <tr>
    <td>width</td>
    <td>Width of the button.</td>
  </tr>
</table>

<header2> Button types </header2>

<table>
  <tr>
    <th>Image</th>
    <th>Name</th>
  </tr>
  <tr>
    <td><img src = "Pixel_GitHub.svg"/></td>
    <td>Pixel_GitHub</td>
  </tr>
    <tr>
    <td><img src = "Pixel_Link.svg"/></td>
    <td>Pixel_Link</td>
  </tr>
  <tr>
    <td><img src = "Pixel_LinkedIn.svg"/></td>
    <td>Pixel_LinkedIn</td>
  </tr>
</table>
