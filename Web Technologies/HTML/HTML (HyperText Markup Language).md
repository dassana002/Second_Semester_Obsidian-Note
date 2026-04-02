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

# Favicon Icon
==Tab එකේ title එකට ඉස්සරහින් තියෙන කුඩා image එක තමයි **favicon**.==
![[Pasted image 20260211145812.png]]

![[Pasted image 20260212211532.png]]

---

## Comments
![[Pasted image 20260212211113.png]]

[[Element]]