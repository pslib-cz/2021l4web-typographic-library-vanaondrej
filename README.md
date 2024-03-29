# MODERN -  free CSS library
**Author:** *Ondřej Váňa*
## Characterization
MODERN is free CSS library. From the name you can spot, that the main purpose of this gallery is to help you with modern and simple intended websites.

## Demo site
Link to **[MODERN demo](https://pslib-cz.github.io/2021l4web-typographic-library-vanaondrej/)** site for preview of this CSS gallery. You can clearly see, what will it look like used.

## Implementation
The implementation of this gallery is very simple. You just need to follow these steps:

 1. Download **modern.css** from this folder **[docs/downloads](https://github.com/pslib-cz/2021l4web-typographic-library-vanaondrej/tree/master/docs/downloads)** or just by pressing this **[link](https://downgit.github.io/#/home?url=https://github.com/pslib-cz/2021l4web-typographic-library-vanaondrej/blob/master/docs/downloads/modern.css)**
 2. Put **modern.css** beside your other .css files
 3. Link it in your .html file as a child of  `<head>`
```html
<link href="modern.css" rel="stylesheet">
```

## Components of MODERN
### Fonts
MODERN is using fonts from Google Fonts.
**Archivo** for headings and **Open Sans** for every other text.

### Colours
For this gallery has been carefully chosen color palette.
There is a list of these colors.

 - Black
 - Light gray
 - Dark blue
 - Neon blue 
 - Gray blue
 
 They are predefined:
`:root{
--black: #0b0c10;
--lgrey: #c5c6c7;
--dblue: #1f2833;
--nblue: #66fcf1;
--gblue: #45a29e;
 }`
 
 You can use them just by typing `var(--colorname)`

### Headings
Without headings the website would not be a website:
`<h1>` - 40 px
`<h2>` - 30 px
`<h3>` - 25 px
`<h4>` - 22 px
`<h5>` - 20 px
`<h6>` - 18 px

### Paragraph
Size of `<p>` 18 px.

### Different text styles
`<b>Bold</b>` - **bold** text

`<i>Italic</i>` - *italic* text

`<u>Underline</u>` - <ins>underlined</ins> text

`<s>Strike</s>` - ~~striked~~ text

`<mark>Marked</mark>` - <mark> marked </mark> text

`<small>Small</small>` - <small> small </small> text

### Lists
You can use `<ul>` as an **unordered** list or `<li>` as and **ordered** list with numbers.

Use this structure:
```html
<ul>
	<li>Lorem</li>
	<ul>
		<li>Lorem</li>
		<li>Ipsum</li>
	</ul>
	<li>Ipsum</li>
	<li>Lorem</li>
	<li>Ipsum</li>
</ul>
```
or
```html
<ol>
	<li>Lorem</li>
	<li>Ipsum</li>
	<li>Lorem</li>
	<ul>
		<li>Lorem</li>
		<li>Ipsum</li>
	</ul>
	<li>Ipsum</li>
</ol>
```

### Quotes and blockquotes
Quote is defined by `<q>` tag.
Blockquote as an `<blockquote>` tag.

Using these is very simple:
```html
<q>A whole universe from nothing.</q>
<br>
<q>I am another type of church.</q>

<blockquote>
<p>How is that even possible?</p>
<br>
<p>-Larry
</blockquote>
```

### Table
Table is defined by tag `<table>` and contains these tags:
`<tbody> <tr> <th> <td>`
The structure of table is following:
```html
<table>
	<tbody>
		<tr>
			<th>Name</th>
			<th>Job</th>
			<th>Age</th>
		</tr>
		<tr>
			<td>Ondra</td>
			<td>Photograph</td>
			<td>18</td>
		</tr>
		<tr>
			<td>Adam</td>
			<td>Senior developer</td>
			<td>18</td>
		</tr>
		<tr>
			<td>Thomas</td>
			<td>Guitarist</td>
			<td>18</td>
		</tr>
	</tbody>
</table>
```

### Buttons
There are 2 design types of buttons in **MODERN**.
Both are defined by tag `<button>`.
There are 2 optional classes - `.btn-outline` and `.btn-normal`. You can see the difference on the **[MODERN demo](https://pslib-cz.github.io/2021l4web-typographic-library-vanaondrej/)** site.
Structure:
```html
<button  class="btn-normal">Button</button>
<button  class="btn-outline">Button</button>
```

### Code
Tag `<code>`should be used mainly with tag `<pre>`, which keeps the same text structure.
```html
<pre>
	<code>
body {
	display: flex;
	justify-content: center;
	align-items: center;
	min-height: 100vh;
	background: radial-gradient;
	overflow: hidden;
}
	</code>
</pre>
```

### Pictures
You can insert pictures by tag `<img>`.
Structure is following:
```html
<figure>
	<img  src="./images/2.jpg"  alt="auto">
	<figcaption>BMW M2</figcaption>
</figure>
```