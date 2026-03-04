==Software system එකක 
**high-level structure**, **components**, **modules**, **their responsibilities**, සහ **how they interact with each other** describe කරන design model එක.==

==Software system එකේ **high-level structure (Over-view Idea)** එක.==

Software architecture is the high-level structure of a software system that defines components, their relationships, and the principles guiding system design.

==Software system එකක් organized , maintain, scale , reuse, bugs අඩු කරන්න 
use කරන වැදගත් concepts දෙකක්.==

==**Software Architecture = System Blueprint==

Software system එකක් build කරනකොට  
අපි direct coding කරන්නෙ නැහැ.

First design in Project:
- System එක **modules වලට divide** කරනවා
- **Database කොහෙද**
- **UI කොහොම communicate වෙන්නේ**
- **Modules connect වෙන්නේ කොහොමද**

System එකේ:
- major components
- components communication
- data flow
- technologies
- deployment structure

මේ ==**Overall structure design (Blue print)**== එකට කියන්නේ.

---

## How improve software
There are two ways,
	==- **Internal Quality** → code quality==
	==- **External Quality** → UI quality==

මෙම දෙකම **==Software Improvement Methods==** ලෙස consider කරනවා.

---
### Internal Quality
==Software system එකේ 
**source code, design structure, architecture quality** වගේ 
**inside technical properties** වල quality එක.==

	- Maintainability improve
	- High Code readability
	- Bugs reduce 
	- Future modification easy 
	- Development cost reduce 
#### Advantages
✔ Code maintain කරන්න easy  
✔ New features add කරන්න easy  
✔ Bugs fix කිරීම fast  
✔ Software lifespan වැඩි වෙනවා  
✔ Team collaboration improve වෙනවා
#### Disadvantages
❌ User directly notice නොකරන quality  
❌ Improve කරන්න extra development time යනවා

---
### External Quality
==**External Quality** කියන්නේ software system එක **userට visible වන behavior quality**.==	
	
	- User satisfaction    
	- Performance
	- Reliability
	- Usability
	- Security
#### Advantages
✔ User satisfaction increase  
✔ System reliability increase  
✔ Business value increase  
✔ Market success increase
#### Disadvantages
❌ Internal code bad වුනත් external quality temporarily good වෙන්න පුළුවන්  
❌ Fix කරන්න sometimes costly

| Feature    | Internal Quality           | External Quality       |
| ---------- | -------------------------- | ---------------------- |
| Focus      | Code structure             | User experience        |
| Visible to | Developers                 | Users                  |
| Phase      | Development                | Testing / Usage        |
| Examples   | Clean code, modular design | Performance, usability |


---
## Software Quality Attributes




---
## Main Purpose of Software Architecture

###### ==System Structure define.==
	System එක Modules වලට Divide කරනවා.
			UI Layer
			Business Logic Layer
			Data Access Layer
			Database

###### ==Complexity Manage.==
	Large systems වල thousands of classes තියෙනවා.
	
	Architecture help කරනවා:
	- System understandable වෙන්න
	- Structure maintain කරන්න
	
###### ==Development guide.==
	Developer ට guideline එකක් ලැබෙනවා.
		Controller → Service → DAO → Database
		
###### ==Scalability Support.==
	Future growth handle කරන්න architecture important.
		- Microservices	    
		- Layered architecture

###### ==Maintainability.==
	System update කරනකොට
		- bugs fix	    
		- new features add
	




| Software Architecture         | Design Pattern              |
| ----------------------------- | --------------------------- |
| Big picture structure         | Small reusable solution     |
| System level decision         | Class level design          |
| Example: Layered Architecture | Example: Factory, Singleton |