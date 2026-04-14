
# Java Script
==**High-level, Interpreted programming language** එකක්.==

High-level → human-friendly syntax  
Interpreted → line by line run වෙනවා (compile කරන්න වෙනම step එකක් නැහැ)

### Why important
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