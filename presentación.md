<!-- $theme: gaia -->


# ==Base de datos== para tu proyecto

- ¿Qué es una base de datos?
- BD u hojas de calculo
- Implementación
	1. Pico

---
<!-- *template: invert -->
# ¿Qué es una base de datos?

Es un almacén en el que se guardan grandes cantidades de información de manera estructurada y con la menor redundancia posible.
<p align="center">
	<img src="images/relational-database-model1.png"  height="400">
</p>

---

 First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

---

[https://www.gcfaprendelibre.org/tecnologia/curso/access_2010/trabajar_con_bases_de_datos/1.do]


---






Marp
===

# ![](images/marp.png)

##### Markdown presentation writer, powered by [Electron](http://electron.atom.io/)

###### Created by Yuki Hattori ( [@yhatt](https://github.com/yhatt) )

---

# Features

- **Slides are written in Markdown.**
- Cross-platform. Supports Windows, Mac, and Linux
- Live Preview with 3 modes
- Slide themes (`default`, `gaia`) and custom background images
- Supports emoji :heart:
- Render maths in your slides
- Export your slides to PDF

---

# How to write slides?

Split slides by horizontal ruler `---`. It's very simple.

```md
# Slide 1

foobar

---

# Slide 2

foobar
```

> *Notice: Ruler (`<hr>`) is not displayed in Marp.*

---

# Directives

Marp's Markdown has extended directives to affect slides.

Insert HTML comment as below:
```html
<!-- {directive_name}: {value} -->
```

```html
<!--
{first_directive_name}:  {value}
{second_directive_name}: {value}
...
-->
```
---

## Global Directives

### `$theme`

Changes the theme of all the slides in the deck. You can also change from `View -> Theme` menu.

```
<!-- $theme: gaia -->
```

|Theme name|Value|Directive|
|:-:|:-:|:-|
|***Default***|default|`<!-- $theme: default -->`
|**Gaia**|gaia|`<!-- $theme: gaia -->`


---

### `$width` / `$height`

Changes width and height of all the slides.

You can use units: `px` (default), `cm`, `mm`, `in`, `pt`, and `pc`.

```html
<!-- $width: 12in -->
```

### `$size`

Changes slide size by presets.

Presets: `4:3`, `16:9`, `A0`-`A8`, `B0`-`B8` and suffix of `-portrait`.

```html
<!-- $size: 16:9 -->
```

<!--
$size: a4

Example is here. Global Directive is enabled in anywhere.
It apply the latest value if you write multiple same Global Directives.
-->

---

## Page Directives

The page directive would apply to the  **current page and the following pages**.
You should insert it *at the top* to apply it to all slides.

### `page_number`

Set `true` to show page number on slides. *See lower right!*

```html
<!-- page_number: true -->
```

<!--
page_number: true

Example is here. Pagination starts from this page.
If you use multi-line comment, directives should write to each new lines.
-->

---

### `template`

Set to use template of theme.

The `template` directive just enables that using theme supports templates.

```html
<!--
$theme: gaia
template: invert
-->

Example: Set "invert" template of Gaia theme.
```

---

### `footer`

Add a footer to the current slide and all of the following slides

```html
<!-- footer: This is a footer -->
```

Example: Adds "This is a footer" in the bottom of each slide

---

### `prerender`

Pre-renders a slide, which can prevent issues with very large background images.

```html
<!-- prerender: true -->
```

---

## Pro Tips

#### Apply page directive to current slide only

Page directive can be selectively applied to the current slide by prefixing the page directive with `*`.

```
<!-- *page_number: false -->
<!-- *template: invert -->
```

<!--
*page_number: false

Example is here.
Page number is not shown in current page, but it's shown on later pages.
-->

---

#### Slide background Images

You can set an image as a slide background.

```html
![bg](mybackground.png)
```

Options can be provided after `bg`, for example `![bg original](path)`.

Options include:

- `original` to include the image without any effects
- `x%` to include the  image at `x` percent of the slide size

Include multiple`![bg](path)` tags to stack background images horizontally.

![bg](images/background.png)

---

#### Maths Typsetting

Mathematics is typeset using the `KaTeX` package. Use `$` for inline maths, such as $ax^2+bc+c$, and `$$` for block maths:

$$I_{xx}=\int\int_Ry^2f(x,y)\cdot{}dydx$$

```html
This is inline: $ax^2+bx+c$, and this is block:

$$I_{xx}=\int\int_Ry^2f(x,y)\cdot{}dydx$$

```

---

## Enjoy writing slides! :+1:

### https://github.com/yhatt/marp

Copyright &copy; 2016 [Yuki Hattori](https://github.com/yhatt)
This software released under the [MIT License](https://github.com/yhatt/marp/blob/master/LICENSE).


















# Introducing ==Gaia== theme

#### Marp's new slide theme

###### Created by [Yuki Hattori (@yhatt)](https://github.com/yhatt)

---
<!-- *template: invert -->

> In Greek mythology, **Gaia** also spelled **Gaea**, was the personification of the Earth and one of the Greek primordial deities.
>
> <small>-- *[Gaia (mythology) - Wikipedia, the free encyclopedia](https://en.wikipedia.org/wiki/Gaia_%28mythology%29)*</small>

---
<!-- page_number: true -->

# Overview

**Gaia** is the beautiful presentation theme on Marp!

- ==**New features**==
	1. Title Slides
	2. Highlight
	3. Color scheme

---

# How to use

#### From menu

Select menu: *View :arrow_right: Theme :arrow_right: Gaia*

#### Use directive

Set `gaia` theme by `$theme` Global Directive.

```
<!-- $theme: gaia -->
```

---

# Basic example 1

**Lorem ipsum** dolor *sit* amet, ***consectetur*** adipiscing elit, sed do `eiusmod` tempor ==incididunt== ut labore et dolore ~~magna aliqua~~. :smile:

> Stay Hungry. Stay Foolish. <small>_--Steve Jobs (2005)_</small>

- List A
	1. [Sub list](https://yhatt.github.io/marp/)
	1. Sub list
		- _More Sub list_

---

# Basic example 2

```javascript
document.write('Hello, world!');
```

|table|layout|example|
|:--|:-:|--:|
|align to left|align to center|align to right|
|:arrow_left: left|:arrow_left: center :arrow_right:|right :arrow_right:

![70% center](../images/marp.png)

---
<!-- *template: gaia -->

## Introduce new features!!

# ==1.== Title Slides

---

# ==e.g.== This page :yum:

---

## ==Apply centering== to the page<br />that has only headings!

##### Useful to title slide. :laughing:

---

> **==Tips:==**
> Apply vertical centering to quote only page too.

---
<!-- *template: gaia -->

# ==2.== Highlight

---
## Highlight Markup

You can use `==` for ==highlighting blue==.

```markdown
==This is highlight markup.==
```

#### Notice

*Marp would show <span style="background-color:yellow;">yellow marker highlight</span> in Markdown view or default slide theme.*

---
<!-- *template: gaia -->

# ==3.== Color scheme templates
---
# ==Color== scheme templates

Change color scheme *by `template` page directive.*

```
<!-- template: default -->
```

- **Default** :arrow_left: This page
- Invert
- Gaia (Theme color)

---
<!-- *template: invert -->
# ==Color== scheme templates

Change color scheme *by `template` page directive.*

```
<!-- template: invert -->
```

- Default
- **Invert** :arrow_left: This page
- Gaia (Theme color)

---
<!-- *template: gaia -->
# ==Color== scheme templates

Change color scheme *by `template` page directive.*

```
<!-- template: gaia -->
```

- Default
- Invert
- **Gaia** (Theme color) :arrow_left: This page

---
<!-- *template: invert -->

# Templates can use<br />to ==per pages==!

##### with using temporally page directive `<!-- *template: invert -->`

---
<!-- template: gaia -->

# ==That's all!==

## Let's create beautiful slides<br />with ==Marp== + ==Gaia== theme!

---

#### `<!-- $theme: gaia -->` of Marp

###### [![](../images/marp.png)](https://yhatt.github.io/marp)

#### https://yhatt.github.io/marp