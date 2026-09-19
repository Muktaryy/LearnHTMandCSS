# HTML Basics

## What I learned

### Basic HTML document structure

- `<!DOCTYPE html>` tells the browser that the document uses HTML5.
  - Somali: `<!DOCTYPE html>` waxay browser-ka u sheegtaa in document-ku isticmaalayo HTML5.
- `<html>` contains the whole HTML document.
  - Somali: `<html>` wuxuu ka kooban yahay dhammaan HTML document-ka.
- `<head>` contains information about the webpage.
  - Somali: `<head>` wuxuu ka kooban yahay xog ku saabsan webpage-ka.
- `<title>` sets the name shown in the browser tab.
  - Somali: `<title>` wuxuu dhigaa magaca ka muuqda tab-ka browser-ka.
- `<body>` contains the content the user sees on the webpage.
  - Somali: `<body>` wuxuu ka kooban yahay content-ka uu user-ku ku arko webpage-ka.

The basic structure is:

`<!DOCTYPE html>` → `<html>` → `<head>` and `<body>`

### Headings

- `<h1>` is the main heading of the page.
  - Somali: `<h1>` waa cinwaanka ugu weyn ee bogga.
- `<h2>` is a major section heading.
  - Somali: `<h2>` waa cinwaan qayb weyn ah.
- `<h3>` is a subsection inside an `<h2>`.
  - Somali: `<h3>` waa qayb-hoosaad ku jirta `<h2>`.
- `<h4>` is a deeper subsection inside an `<h3>`.
  - Somali: `<h4>` waa qayb-hoosaad ka sii qoto dheer oo ku jirta `<h3>`.
- `<h5>` comes after `<h4>` in the heading hierarchy.
  - Somali: `<h5>` wuxuu ka dambeeyaa `<h4>` marka la raacayo kala sarreynta cinwaannada.
- `<h6>` is the deepest heading level.
  - Somali: `<h6>` waa heerka ugu hooseeya ee cinwaannada.
- The heading hierarchy is `h1 → h2 → h3 → h4 → h5 → h6`.
  - Somali: Kala sarreynta cinwaannadu waa `h1 → h2 → h3 → h4 → h5 → h6`.
- Heading levels describe the structure and importance of sections, not just text size.
  - Somali: Heerarka headings-ku waxay sharxayaan qaab-dhismeedka iyo muhiimadda qaybaha, ma aha oo keliya cabbirka qoraalka.

### Text

- `<p>` creates a paragraph.
  - Somali: `<p>` wuxuu sameeyaa paragraph.
- `<strong>` marks important text, usually shown in bold.
  - Somali: `<strong>` wuxuu tilmaamaa qoraal muhiim ah, badanaa wuxuu u muuqdaa bold.
- `<em>` adds emphasis, usually shown in italic.
  - Somali: `<em>` wuxuu qoraalka siinayaa emphasis, badanaana wuxuu u muuqdaa italic.
- `<span>` is a small container for a piece of text. It has no special meaning or visual change by itself.
  - Somali: `<span>` waa container yar oo lagu duubo qayb qoraal ah. Kaligiis macne gaar ah ama isbeddel muuqaal ah ma sameeyo.

### Line breaks and dividers

- `<br>` forces a line break.
  - Somali: `<br>` wuxuu qoraalka ku qasbaa inuu galo line cusub.
- `<hr>` creates a horizontal divider between sections.
  - Somali: `<hr>` wuxuu sameeyaa xariiq jiif ah oo kala saarta qaybaha.
- There is no standard `<vr>` tag for a vertical line. Vertical lines are normally made with CSS.
  - Somali: Ma jiro tag HTML oo caadi ah oo la yiraahdo `<vr>` oo sameeya xariiq taagan. Xariiqyada taagan badanaa CSS ayaa lagu sameeyaa.

### Links

- `<a>` creates a link.
  - Somali: `<a>` wuxuu sameeyaa link.
- `href` tells the link where to go.
  - Somali: `href` wuxuu sheegaa meesha link-gu aadayo.
- `target="_blank"` tells the browser to open the link in a new tab.
  - Somali: `target="_blank"` wuxuu browser-ka u sheegaa inuu link-ga ku furo tab cusub.

A simple link looks like:

`<a href="URL">Link text</a>`

A link that opens in a new tab looks like:

`<a href="URL" target="_blank">Link text</a>`

## My understanding

The `<head>` and `<body>` are both inside `<html>`.

Somali: `<head>` iyo `<body>` labaduba waxay ku jiraan `<html>`.

The head is where we put information about the HTML page, while the body is where we put the content the user sees.

Somali: Head-ku waa meesha lagu dhigo xogta ku saabsan HTML page-ka, halka body-gu yahay meesha lagu dhigo content-ka uu user-ku arko.

`<title>` is for the browser tab, while headings such as `<h1>` are visible page content.

Somali: `<title>` waxaa loogu talagalay tab-ka browser-ka, halka headings sida `<h1>` ay yihiin content ka muuqda page-ka.

Headings should follow a logical hierarchy: `h1 → h2 → h3 → h4 → h5 → h6`. If I am inside an `<h3>` section and need a deeper subsection, I can use `<h4>`.

Somali: Headings-ku waa inay raacaan kala sarreyn macquul ah: `h1 → h2 → h3 → h4 → h5 → h6`. Haddii aan ku jiro qayb `<h3>` ah oo aan u baahanahay qayb ka sii hooseysa, waxaan isticmaali karaa `<h4>`.

`<strong>` and `<em>` give text meaning, while `<span>` is mainly a small wrapper that can be targeted later with CSS or JavaScript. A `<span>` does not normally change how text looks by itself.

Somali: `<strong>` iyo `<em>` waxay qoraalka siinayaan macne, halka `<span>` uu inta badan yahay wrapper yar oo mustaqbalka CSS ama JavaScript lagu bartilmaameedsan karo. `<span>` kaligiis badanaa ma beddelo muuqaalka qoraalka.

`<br>` moves content to a new line, while `<hr>` separates content with a horizontal line.

Somali: `<br>` wuxuu content-ka u dhaqaajiyaa line cusub, halka `<hr>` uu content-ka ku kala saaro xariiq jiif ah.

`<a>` is the link, `href` is the destination, and `target` controls where the link opens.

Somali: `<a>` waa link-ga, `href` waa meesha uu link-gu aadayo, halka `target` uu xakameeyo meesha link-gu ka furmayo.

## Practice

I created a basic Himma Academy page with a browser tab title and a visible main heading.

Somali: Waxaan sameeyay page aasaasi ah oo Himma Academy ah oo leh magaca browser tab-ka iyo main heading muuqda.

I practiced using `<p>`, `<strong>`, `<em>`, `<span>`, `<br>`, and `<hr>`.

Somali: Waxaan ku tababartay isticmaalka `<p>`, `<strong>`, `<em>`, `<span>`, `<br>`, iyo `<hr>`.

I also practiced understanding the heading hierarchy through `<h1>` to `<h6>`, including using `<h4>` for a deeper subsection.

Somali: Waxaan sidoo kale ku tababartay fahamka kala sarreynta headings-ka laga bilaabo `<h1>` ilaa `<h6>`, oo ay ku jirto isticmaalka `<h4>` qayb-hoosaad ka sii qoto dheer.

I practiced making text clickable with `<a>` and `href`, including using `#` as a practice destination.

Somali: Waxaan ku tababartay sida qoraal looga dhigo clickable anigoo isticmaalaya `<a>` iyo `href`, waxaana isticmaalay `#` sidii meel tababar ah.

I learned that `target="_blank"` opens a link in a new tab.

Somali: Waxaan bartay in `target="_blank"` uu link-ga ku furo tab cusub.
