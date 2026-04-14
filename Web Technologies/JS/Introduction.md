
# Java Script
==**High-level, Interpreted programming language** එකක්.==

High-level → human-friendly syntax  
Interpreted → line by line run වෙනවා (compile කරන්න වෙනම step එකක් නැහැ)

---

# Why important
==**Web pages dynamic** කරන්න use කරන **Programming language** එකක්.==

**Used to create interactive web pages.**

HTML → structure (skeleton)  
CSS → style (design)  
JavaScript → behavior (actions)

### Main uses
1. Web pages interactive කිරීම
2. Form validation (username, password check)
3. Animations create කිරීම
4. Games develop කිරීම
5. Web apps build කිරීම
6. Server-side programming (Node.js)
7. Mobile apps develop කිරීම

### Internal working process

==*Browser load HTML*==
Browser එක server එකෙන් HTML file download කරනවා.
	Browser HTML parse කරලා **DOM (Document Object Model)** tree එක create කරනවා.
	**DOM** **tree** එක JavaScript එකට access කරන්න පුළුවන්.
	
	DOM = page structure representation	
*↓*
==*Browser load CSS*==
	Browser CSS file read කරලා **CSSOM tree** create කරනවා.
	DOM + CSSOM combine වෙලා **Render tree** create වෙනවා.
	
	Render tree → using page layout display.
*↓*
==*Browser load JavaScript*==
	Browser `<script>` tag එක හම්බුනොත්, Browser JavaScript file download කරනවා.
	Browser එකට built-in JavaScript engine එකක් තියෙනවා.

	JavaScript engine = program that executes JS code.
*↓*
==*JavaScript Engine execute code*==
*↓*
*==JavaScript modify DOM (page change dynamically)*==


==Web browser එකක් HTML, CSS, JavaScript files load කරගෙන,== 
==JavaScript engine (V8, SpiderMonkey) use කර code execute කරලා, 
page එක dynamically update කරන process එක.==

**JavaScript engine (V8, SpiderMonkey) කියන්නේ browser එක ඇතුලේ තියෙන special program එකක්.**
එය JavaScript code machine code වලට convert කර run කරනවා.


### Inside JavaScript Engine

| Browser | Engine         |
| ------- | -------------- |
| Chrome  | V8             |
| Firefox | SpiderMonkey   |
| Safari  | JavaScriptCore |
==JS Code==
↓
==Parser==
↓
==Abstract Syntax Tree (AST)==
↓
==Interpreter / JIT Compiler==
↓
==Machine Code==
↓
==Execute==


---

# Key Features

### Dynamic behavior
==**web page එක reload නොකර content change වෙන්න පුළුවන් ability එක**.==

Static page → always same content  
Dynamic page → situation අනුව content change වෙනවා

JavaScript use කරලා page content runtime වෙලාවේ change කරන්න පුළුවන්.
	- button click → text change
	- login success → welcome message
	- shopping cart update

### Client-side scripting
==**JavaScript code browser (user computer) එකේ run වෙන එක**.==
			
	client = user device (browser)

JavaScript mostly client-side language එකක්.

### Server-side scripting
==**Code server එකේ run වෙලා result browser එකට send කරන එක**.==

	example languages:
		- Node.js (JavaScript)
		- PHP
		- Python
		- Java

Server scripts create dynamic response based on user request.

### DOM Manipulation

	DOM = Document Object Model
	
HTML page structure tree format එකක්.
==JavaScript use කරලා HTML elements modify කරන්න පුළුවන්.==
==**HTML change using JS.**==
DOM allows JS to change content, structure, style.

#### Common DOM methods

###### Select Element
```
document.getElementById("id")
document.querySelector(".class")
```

###### Change Content
```
element.innerHTML="Hello"
```

###### Create Element
```
document.createElement("p")
```


### Asynchronous programming

	Asynchronous = task run වෙන අතර same time another task run වෙන්න පුළුවන්.
	Asynchronous = background execution.

background processing without blocking program.
Ajax technique allows data load without page reload.

**Synchronous**  
	step by step wait වෙනවා
	
**Asynchronous**  
	wait නොවී next task run වෙනවා

```
fetch("data.json")
.then(response => response.json())
.then(data => console.log(data));
```
data load වෙනකම් page freeze වෙන්නේ නැහැ.


|Feature|Simple idea|
|---|---|
|Dynamic behavior|page reload නැතුව change|
|Client-side|browser run|
|Server-side|server run|
|DOM manipulation|HTML change|
|Asynchronous|background tasks|