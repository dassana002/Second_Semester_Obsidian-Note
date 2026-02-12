==Web Pages වල ,==
==structure සහ content define කරන්න use කරන== ,
standard markup language එකක්.

==Most basic building block of the web.==

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
Text එක අතරමැද වැඩ කරන elements.
new line එකක් create කරන්නේ නෑ.==
![[Pasted image 20260211140811.png]]
#### Block-level Elements
==Always new line එකකින් start වෙලා, 
full width එකක් ගන්න elements block-level elements කියනවා.==
![[Pasted image 20260211140736.png]]

#### Empty / Void Elements
==Content එකක්වත් closing tag එකක්වත් නැති HTML elements.
Opening tag එක විතරයි, 
ඇතුළේ content නෑ, 
Closing tag නෑ.==
![[Pasted image 20260211140611.png]]

![[Pasted image 20260212211318.png]]

---

# <!**DOCTYPE**  html>
==browser එකට “මේ file එක HTML5 document එකක්” කියලා කියන declaration එකක්.==
#### What is important?
Browser එකකට modes දෙකක් තියෙනවා:
==Browser එකට දෙන Document type එක දෙනවා. මේකේ  තියෙන්නේ html Document type එකක්. පරන browser වලට doc type එක දන්නේ නෑ අදුරගන්න. ඒ නිසා තමයි use කරන්නේ.== 

1️⃣ **Standards Mode** (හරිම වැදගත්)  
2️⃣ **Quirks Mode** (පැරණි, වැරදි rendering)

`<!DOCTYPE html>` තියෙනකොට:
- Browser එක **Standards Mode** වලින් page එක render කරනවා
- HTML / CSS rules හරියට follow කරනවා
    
 `<!DOCTYPE html>` නැතිනම්:
- Browser එක **Quirks Mode** වලට යනවා
- Layout issues එනවා

![[Pasted image 20260211140439.png]]

# head Element
==`<head>` element එක HTML document එකක metadata (page එක ගැන information) අඩංගු කරන කොටසයි.==
==browser එකට සහ search engines වලට information දෙන section එක.==

`<head>` section එක userට directly පෙනෙන්නේ නෑ.

### title element
==Web page එකේ title එක define කරන element එක.==
![[Pasted image 20260211144017.png]]
### meta Element 
==Web page එක ගැන metadata (data about data) define කරන element එක==.
![[Pasted image 20260211144640.png]]
✔ Sinhala / English / Special characters support කරන්න
✔ Mobile devices වල responsive layout
✔ Google search result description

### link Element
==External resource එකක් HTML document එකට link කරන element එක.==
![[Pasted image 20260211144845.png]]

### style Element
==Internal CSS code ලියන්න භාවිතා කරන element එක.==
![[Pasted image 20260211145042.png]]

### script element
==JavaScript code add කිරීම සඳහා භාවිතා කරන element එක.==
![[Pasted image 20260211145211.png]]


---

# Favicon Icon
==Tab එකේ title එකට ඉස්සරහින් තියෙන කුඩා image එක තමයි **favicon**.==
![[Pasted image 20260211145812.png]]

![[Pasted image 20260212211532.png]]

---

## Comments
![[Pasted image 20260212211113.png]]



---

# Semantic 