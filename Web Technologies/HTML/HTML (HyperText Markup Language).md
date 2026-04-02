Web Pages වල ,
==structure සහ content define කරන්න== **use කරන** ,
standard mark-up ==language එකක්.==

==Most basic building block of the web.==

---
# <!**DOCTYPE**  html>
browser එකට,
==මේ file එක, **HTML5 Standard document** එකක්,  ඒ rules අනුව page එක display (render) කරන්න==
කියලා කියන ==declaration== එකක්.

**DOCTYPE = Document Type Declaration**
#### What is important?
Browser එකකට modes දෙකක් තියෙනවා:
==Browser එකට HTML Document type එක දෙනවා.==
==පරන browser වලට doc type එක දන්නේ නෑ අදුරගන්න. 
ඒ නිසා තමයි use කරන්නේ.== 

1️⃣ **Standards Mode** (හරිම වැදගත්)  
2️⃣ **Quirks Mode** (පැරණි, වැරදි rendering)

`<!DOCTYPE html>` තියෙනකොට:
- Browser එක **Standards Mode** වලින් page එක render කරනවා
- HTML / CSS rules හරියට follow කරනවා
    
 `<!DOCTYPE html>` නැතිනම්:
- Browser එක **Quirks Mode** වලට යනවා
- Layout issues එනවා

#### Main purposes
1. HTML version එක identify කරනවා
2. Browser rendering errors avoid කරනවා
3. CSS layout correctly apply වෙනවා
4. Old browser compatibility maintain කරනවා
5. Standards Mode enable කරනවා

![[Pasted image 20260331192829.png]]



---

![[Capture.PNG]]

```
<html lang = "en">
```
මෙම webpage එකේ,
**Content English language එකෙන් ලියලා තියෙනවා** කියලා browser එකට කියන එක.
###### Purpose
`lang` attribute එක browser, search engine, screen reader වලට help කරනවා.


# head Element
==`<head>` element එක, 
**HTML document එකක meta data** (page එක ගැන information) අඩංගු කරන කොටසයි.==

==browser එකට සහ search engines වලට ( meta data ) information දෙන section එක.==
`<head>` section එක userට directly පෙනෙන්නේ නෑ.

### title element
==Web page එකේ title එක define කරන element එක.==
![[Pasted image 20260211144017.png]]
### meta Element 
==HTML document එක ගැන **extra information (metadata)** provide කරන tag එකක්..==

👉 Metadata = data about data  
👉 user ට page එකේ visible වෙන්නේ නෑ  
👉 browser, search engine, devices වලට information දෙනවා

Meta tag helps:
- browser එකට page එක display කරන්න
- search engine වලට page එක understand කරන්න
- mobile responsive behaviour control කරන්න
- page description provide කරන්න
- character encoding define කරන්න

```
<meta charset="UTF-8">
```
මෙම webpage එකේ,
**Text characters UTF-8 encoding එකෙන් ලියලා තියෙනවා.** ඒ අනුව text display කරන්න.
###### Purpose
1. All languages support වෙනවා
2. Text errors prevent වෙනවා
3. Standard encoding

![[Pasted image 20260211144640.png]]
✔ Sinhala / English / Special characters support කරන්න
✔ Mobile devices වල responsive layout
✔ Google search result description



### link Element
==External resource එකක් HTML document එකට link කරන element එක.==
![[Pasted image 20260211144845.png]]

### style Element
==Internal CSS code ලියන්න use කරන element එක.==
![[Pasted image 20260211145042.png]]

### script element
==JavaScript code add කිරීම සඳහා use කරන element එක.==
![[Pasted image 20260331231734.png|414]]



---

# HTML Element

==HTML document එකක,==
==content එකක් build කරන,== 
==full unit එකක්.==

==An HTML element consists of a start tag, content, and an end tag, which together define a part of a web page.==
![[Element.jpg]]
### Type of Elements
#### Nesting Elements
==Element එකක් ඇතුළත තවත් element එකක්==.
![[Pasted image 20260211140855.png]]
#### Inline-level Elements
==Line එක බිඳින්නේ නැතිව, same line එකේ content පෙන්වන elements.
new line එකක් create කරන්නේ නෑ.==
![[Pasted image 20260211140811.png]]
#### Block-level Elements
==Always new line එකකින් start වෙලා, 
full width එකක් ගන්න elements 
block-level elements කියනවා.==
![[Pasted image 20260211140736.png]]

#### Empty / Void Elements
==Content එකක්වත් closing tag එකක්වත් නැති HTML elements.
==ඇතුළේ content නෑ, 
Closing tag නෑ.
![[Pasted image 20260211140611.png]]

![[Pasted image 20260212211318.png]]


---


# Favicon Icon
==Tab එකේ title එකට ඉස්සරහින් තියෙන කුඩා image එක තමයි **favicon**.==
![[Pasted image 20260211145812.png]]

![[Pasted image 20260212211532.png]]

---

## Comments
![[Pasted image 20260212211113.png]]



---

# Semantic HTML

![[semantic_photo.webp]]

## Semantic Tags
==element එකේ name එකෙන්ම එය represent කරන content එකේ meaning එක පැහැදිලිව දක්වන elements.==
**Content එකේ meaning browser එකට සහ developers ට පැහැදිලිව කියන HTML tags.**

==Text එක **just display කරනවා නෙමෙයි**==  
==Text එක **meaningfully define කරනවා==

### Heading Tag 
==**Heading hierarchy** define කරන්න use වෙන tags.==
==Heading tags කියන්නේ font size control කරන්නම නෙමෙයි.==
==ඒවා indicate කරන්නේ:  Document structure hierarchy==
![[Pasted image 20260212214723.png]]

### Paragraph Tag
==Text content group කරලා **block level text container** ලෙස use වෙනවා.==
![[Pasted image 20260212220029.png]]
### Emphasis Tag
==Text එකට **semantic emphasis** add කරනවා.==
Usually italic ලෙස show වෙනවා.
![[Pasted image 20260212220056.png]]
### Strong Tag
==Text එකට **strong importance** indicate කරනවා.==
![[Pasted image 20260212220248.png]]
### Presentational Tags
![[Pasted image 20260212220401.png]]
### Superscript
![[Pasted image 20260212220550.png]]
![[Pasted image 20260212220631.png]]
### Subscript
![[Pasted image 20260212220703.png]]
![[Pasted image 20260212220829.png]]
### Preformatted Text
==Displays text **exactly as written**.==
- Preserves spaces
- Preserves line breaks
Text එක **original formatting** (spaces, tabs, line breaks) browser එකේ show වෙනවා.

![[Pasted image 20260212221431.png]]
![[Pasted image 20260212221502.png]]

### Code Tag
==Indicates computer code.==
මෙය **computer code fragment** (programming code words, syntax) indicate කරන්න use කරනවා.

![[Pasted image 20260212221630.png]]
![[Pasted image 20260212221656.png]]
### Address Tag
==Contact information display.==
![[Pasted image 20260212221823.png]]
### Time Tag
==Machine-readable date/time.==
![[Pasted image 20260212221957.png]]
### Blockquote Tag
==Used for long quotations.==
මෙය **long quotation (දිග quote)** indicate කරන්න use කරනවා.

Browser එකට කියනවා:
මෙම text එක වෙන source එකකින් quote කරපු content එකක්.

![[Pasted image 20260212222203.png]]
### Mark Tag
==Highlight text.==
![[Pasted image 20260212222428.png]]
![[Pasted image 20260212222503.png]]


### Anchor tag
HTML වල **hyperlink create කරන්න use කරන tag එක**.
###### HyperLink
	click කළාම user,
එක වෙන page එකකට, file එකකට, section එකකට හෝ website එකකට ගෙනියන clickable connection එකක්.
	Hyperlink = clickable link

`href` attribute එක භාවිතා කරන්නේ **link එක යන්න ඕන destination (URL) specify කරන්න**.
`target` attribute එක භාවිතා කරන්නේ **link එක open වෙන්න ඕන place එක specify කරන්න**.

| Value             | Meaning (English)     | සිංහල පැහැදිලි කිරීම                               | Example                                                   |
| ----------------- | --------------------- | -------------------------------------------------- | --------------------------------------------------------- |
| `_self` (default) | Opens in same tab     | same tab/window එකේ open වෙනවා (default behaviour) | `<a href="page.html" target="_self">Open</a>`             |
| `_blank`          | Opens in new tab      | new tab එකක් open වෙනවා                            | `<a href="https://google.com" target="_blank">Google</a>` |
| `_parent`         | Opens in parent frame | parent frame එකේ open වෙනවා                        | `<a href="page.html" target="_parent">Open</a>`           |
|`_top`|Opens in full window|full browser window එකේ open වෙනවා|`<a href="page.html" target="_top">Open</a>`|



---
## Non-Semantic
==content එකේ meaning එකක් දක්වන්නේ නැති, 
structure හෝ styling purpose සඳහා use කරන elements.==

### div tag
==Webpage එකේ **sections / layout parts group** කරන්න use කරනවා.==

`<div>` = large container (box)

`<div>` use කරන්නේ:
- webpage layout structure create කරන්න
- multiple elements group කරන්න
- CSS apply කරන්න
- JavaScript manipulate කරන්න
- sections divide කරන්න

```
<div>
   <h1>Title</h1>
   <p>Description</p>
</div>
```
### span tag
==small text part **style change** කරන්න use කරනවා.==

👉 `<span>` = small container

`<span>` use කරන්නේ:
- sentence inside specific word highlight කරන්න
- text colour change කරන්න
- font style change කරන්න
- small part group කරන්න

| Feature      | `<div>`       | `<span>`             |
| ------------ | ------------- | -------------------- |
| element type | block         | inline               |
| size         | full width    | content width        |
| new line     | yes           | no                   |
| use          | large section | small part           |
| layout       | structure     | styling              |
| contain      | many elements | text/inline elements |


---

# HTML Sectioning 
==webpage එක **logical parts (sections)** වලට divide කිරීම==

Sectioning use කරන්නේ:
- webpage structure clear කරන්න
- SEO improve කරන්න
- readability improve කරන්න
- accessibility improve කරන්න (screen readers)
- large content organize කරන්න

![[sectioning.jpg]]

```
<body>

<header>
   <h1>My Blog</h1>
</header>

<nav>
   <a href="#">Home</a>
   <a href="#">Contact</a>
</nav>

<section>

   <article>
      <h2>HTML</h2>
      <p>HTML lesson</p>
   </article>

</section>

<aside>
   <p>Advertisement</p>
</aside>

<footer>
   <p>Copyright 2026</p>
</footer>

</body>
```


```
<body>

<header>
   website title
</header>

<nav>
   menu links
</nav>

<main>
   main content
</main>

<footer>
   footer details
</footer>

</body>
```

## Main Sectioning Tags

### header tag
==page header part==

use for:
- title
- logo
- navigation intro

```
<header>
   <h1>My Website</h1>
</header>
```

### nav tag
==navigation link==
menu links define කරනවා.
```
<nav>
   <a href="#">Home</a>
   <a href="#">About</a>
</nav>
```

### section tag
==related content group==
topic based content divide කරනවා.
```
<section>
   <h2>HTML Tutorial</h2>
   <p>HTML basics</p>
</section>
```

### article tag
==independent content part==
- blog post
- news article
- forum post
independent use කරන්න පුළුවන්.

```
<article>
   <h2>News Title</h2>
   <p>News description</p>
</article>
```

### aside tag
==side content==
- sidebar
- ads
- related info

```
<aside>
   <p>Related links</p>
</aside>
```

### footer tag
==bottom part==
```
<footer>
   <p>Copyright 2026</p>
</footer>
```

### main tag
==introduce in page එකේ most important information.==
`<main>` use කරන්නේ:
- page එකේ main topic content indicate කරන්න
- SEO improve කරන්න
- accessibility improve කරන්න
- page structure clear කරන්න
- repeated parts remove කරන්න (nav, footer etc)
```
<main>
   <h1>HTML Tutorial</h1>
   <p>HTML lesson content</p>
</main>
```








[[CSS]]
