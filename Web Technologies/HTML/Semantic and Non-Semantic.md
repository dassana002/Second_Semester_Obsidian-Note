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

[[Section]]
