# 📄 The White Stripes "Elephant" Liner Notes

## 🎯 Overview

Style a finished HTML page about The White Stripes' *Elephant* so it matches a design, using
only an external stylesheet.

Every White Stripes record uses the same three colors: red, white, and black. In this
exercise, you will bring that look to a liner notes page for their 2003 album **Elephant**.

The HTML is already written for you in `index.html`. It has a header, the album cover, an
*About the Album* section with a quote, the tracklist, the credits, the singles, and a
footer. Your job is to write `css/style.css` so the page matches the screenshot in
`images/final.png`.

You are matching a design, not copying it pixel for pixel. Your colors, sizes, and spacing
should be close enough that someone looking at both would call them the same page.

### 🧠 What You'll Practice

- Create an external stylesheet and link it to a page
- Select elements by type, by `id`, by class, and by where they sit in the page
- Set colors, background colors, fonts, and text styles
- Use the box model: `margin`, `border`, and `padding`
- Center a column of content with `max-width` and `margin`
- Make an image shrink to fit its container
- Restyle lists and description lists, and remove browser default spacing
- Style a link and a quotation

## 📋 Requirements

### 🎨 Style Guide

| Use | What it looks like |
| --- | --- |
| Red | A strong, true red. Used for headings, track times, the lead single, the quote's edge, the link, and the stripe under the header. |
| Black | A near-black. Used for the header, footer, quote box, and borders. |
| White | The page background and the text on black or red. |
| Font | A clean sans-serif, such as Inter from Google Fonts, or `Arial, Helvetica, sans-serif`. |
| Column | About `600px` wide at most, centered on the page. |

### Setup

- [ ] `css/style.css` exists and is linked in the `head` of `index.html` with a `link` element
- [ ] All styles are in `css/style.css`: no `style` attributes and no `<style>` element
- [ ] The text and elements in `index.html` are unchanged (adding `class` attributes is fine)

### Whole page

- [ ] The `body` has no default margin, so the header and footer touch the edges of the window
- [ ] The page uses a sans-serif font
- [ ] `main` is a centered column about `600px` wide at most, with space above and below,
      and a little space on each side on small screens
- [ ] Every `h2` is red

### Header and footer

- [ ] The `header` has a black background, white centered text, and space inside it
- [ ] "The White Stripes" is small, uppercase, and letter-spaced, above the album title
- [ ] A thick red stripe runs along the bottom of the `header`
- [ ] The `footer` has a black background, small white centered text, and space inside it

### Album cover

- [ ] The cover fills the width of the column and never gets wider than it, keeping its
      shape as the window narrows
- [ ] The `figure` has no extra indent, and the caption is small text under the image

### About the Album

- [ ] The section is a box with a thick black border and space inside it
- [ ] The "Start with the lead single" link is red and underlined
- [ ] The `blockquote` is a black box with bold white text, a red bar on its left edge, and
      space inside it
- [ ] The `cite` sits on its own line, in italics

### Tracklist

- [ ] Each track is its own box with a black border, space inside it, and a gap between boxes
- [ ] The track numbers sit inside the boxes
- [ ] Each track time is red and bold, with space between it and the song title
- [ ] The lead single's box has a red background with white text, including its time

### Credits

- [ ] The section is a box with a thick black border and space inside it, like *About the Album*
- [ ] Each role (`dt`) is bold, and each name (`dd`) sits right under it with no indent
- [ ] There is space between each role and name pair

### Singles

- [ ] The singles stay a plain numbered list, with no boxes
- [ ] Each release date is red, not bold, with space between it and the song title

### ✅ Before You Submit

Check the following:

- [ ] You put your live page and `images/final.png` side by side and compared every section
- [ ] The header and footer touch both edges of the window, with no white gap
- [ ] You made the window narrow, and the album cover shrank to fit with no sideways scrolling
- [ ] The lead single's time is white, not red
- [ ] Every color on the page is red, white, or black
- [ ] `css/style.css` passes the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)
      with no errors
- [ ] `index.html` still passes the [W3C Markup Validator](https://validator.w3.org/#validate_by_input)
      with no errors
- [ ] You saved all of your files
- [ ] The site is live on GitHub Pages, it has your styles, and the URL is in your pull request

## 🖼️ Example Output

![The finished Elephant liner notes page: a black header with a red stripe under it, the red album cover, a bordered About the Album box with a black quote box, a tracklist of bordered rows with the lead single in red, a bordered Credits box, the singles list, and a black footer](../images/final.png)

The screenshot is the page at a desktop width. On a phone, the column should fill the
screen with a little space on each side, and the album cover should shrink to fit.

## 📂 Starter Files

| File | Purpose |
| --- | --- |
| `index.html` | The finished HTML. You only add a `link` to your stylesheet, plus any `class` attributes you choose to use. |
| `images/album-art.webp` | The album cover. Already in the page. |
| `images/final.png` | A screenshot of the finished page. Your target. Don't add it to the page. |
| `css/style.css` | **You create this.** All of your CSS goes here. |

> [!IMPORTANT]
> Don't change the text or the elements in `index.html`. You may add a `link` in the `head`
> and `class` attributes to elements. Everything else, including every color and size,
> belongs in `css/style.css`. No `style` attributes and no `<style>` element.

## 🧮 Grading

| Criteria | What earns full credit | Points |
| --- | --- | --- |
| **Setup** | `css/style.css` is linked in the `head` and loads on the live site; no `style` attributes or `<style>` element; the HTML's text and elements are unchanged. | 1 |
| **Whole page** | No default `body` margin; a sans-serif font; `main` is a centered column about `600px` wide at most with space on small screens; every `h2` is red. | 3 |
| **Header and footer** | Black header with white centered text and inner space; letter-spaced uppercase band name; thick red stripe under the header; black footer with small white centered text. | 3 |
| **Album cover** | The image fits the column and keeps its shape at any width; no extra `figure` indent; small caption under the image. | 1 |
| **About the Album** | Bordered box with inner space; red underlined link; black `blockquote` with bold white text, red left bar, and inner space; `cite` on its own line in italics. | 4 |
| **Tracklist** | Each track is a bordered box with inner space and a gap between boxes; numbers inside the boxes; red bold times with space before them; the lead single is red with white text. | 4 |
| **Credits** | Bordered box matching *About the Album*; bold roles; names under their roles with no indent; space between pairs. | 1 |
| **Singles** | A plain numbered list with red, non-bold dates and space before them. | 1 |
| **Published and submitted** | GitHub Pages site is live and loads correctly with its styles; pull request into `main` is open with the live URL in the description; PR URL submitted in Canvas. | 1 |
| **Total** |  | **19** |

Close counts. A slightly different red, a border that's `3px` instead of `4px`, or spacing
that's a little off still earns full credit. A missing style, a color outside red, white,
and black, or a part of the page that clearly doesn't match the screenshot does not.

## 📚 Resources

- [MDN — CSS basics](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website/Styling_the_content)
- [MDN — CSS selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_selectors)
- [MDN — The box model](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Box_model)
- [MDN — Styling lists](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Text_styling/Styling_lists)
- [MDN — `list-style-position`](https://developer.mozilla.org/en-US/docs/Web/CSS/list-style-position)
- [Google Fonts — Inter](https://fonts.google.com/specimen/Inter)
- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/#validate_by_input)

## 🆘 Getting Help

Ask during class or office hours, or post on the Canvas discussion board.

Before you ask, check these common problems:

- **None of your styles show up?** Check the `link` in the `head`. It needs
  `rel="stylesheet"`, and its `href` must be `css/style.css`, letter for letter. Make sure
  the file is named `style.css`, not `style.css.txt`.
- **Styles work in WebStorm but not on GitHub Pages?** File names on GitHub are case
  sensitive. `CSS/Style.css` and `css/style.css` are different files there.
- **A white gap around the header and footer?** The browser adds a margin to the `body`
  by default. Set it to `0`.
- **The album cover is wider than the column?** Give the image `max-width: 100%` and
  `height: auto`.
- **The track numbers hang outside the boxes?** Look up `list-style-position` on MDN.
- **The names in Credits are indented?** Browsers indent `dd` by default with a left
  margin. `figure` and `blockquote` have default margins too.
- **Only some sections need a border, but they're all `section`s?** Add a class to the
  ones that need it, or look up `:nth-of-type()` on MDN.
- **A rule isn't working?** Check for a missing `;`, `:`, or `}`. One missing character
  can break every rule after it. The CSS validator will point to the line.

---

The AI policy and submission instructions are in the [README](../README.md).
