
# Software Architecture

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
==**Software Quality Attributes** කියන්නේ software system එකේ **non-functional characteristics**.==
	
	Quality Attributes = Software system එකේ quality measure කරන properties

Why used ? 
		- System **performance evaluate** කරන්න  
		- Software **architecture design guide** කරන්න  
		- **User satisfaction** ensure කරන්න  
		- **System reliability** measure කරන්න

#### Major Software Quality Attributes
	-  Usability  
	-  Performance  
	-  Reliability  
	-  Security  
	-  Maintainability  
	-  Scalability  
	-  Availability  
	-  Portability

| Internal        | External        |
| --------------- | --------------- |
| Code quality    | User experience |
| Architecture    | Performance     |
| Maintainability | Usability       |
| Modularity      | Reliability     |

---
## Main Purpose 

**System structure define කිරීම**
- System එක කොටස් වලට divide කරනවා
	Example: 
		UI, Business Logic, Database

**Maintainability improve කිරීම**
- Code easily modify කරන්න පුළුවන්

**Scalability**
- System එක users වැඩි උනත් run වෙන්න පුළුවන්

**Performance optimize කිරීම**
- Components efficient ලෙස communicate කරනවා

**Team development support**
- Different developers different modules develop කරන්න පුළුවන්

---
## Common Software Architecture Types

| Architecture  | Best For                  |
| ------------- | ------------------------- |
| Layered       | Enterprise applications   |
| Client-Server | Web systems               |
| MVC           | UI based applications     |
| Microservices | Large distributed systems |
| Monolithic    | Small applications        |

1. Layered Architecture (N-Tier Architecture)
		[[Layered Architecture]]
2. Client-Server Architecture
		[[Client-server Architecture]]
3. MVC Architecture (Model-View-Controller)
		[[MVC Architecture]]
4. Micro-services Architecture
		[[Micro-service]]
5. Monolithic Architecture
		[[Monolithic]]


---

# Design Patterns

==Software development වල 
frequently occur වෙන problems solve කරන්න developers භාවිතා කරන 
**reusable solution template** එකක්.==

==**Common software design problems solve කරන්න reusable solution model එකක්**.==

### Why use
Software systems develop කරනකොට **same problems repeatedly occur වෙනවා**.
	- Object create කිරීම.
	- Object communication
	- Code reuse
	- Dependency manage කිරීම

Design patterns මේ problems **standardized method එකකින් solve කරනවා**.

## Types of Design Patterns

### Creational Design Patterns
==**Creational Design Patterns** කියන්නේ  **new objects create** කරන process manage කරන patterns.==
	- Object creation control කරන්න.
	- Object instantiation flexible කරන්න.
	- System loosely coupled කරන්න.

|Pattern|Purpose|
|---|---|
|Singleton|Only one object create|
|Factory Method|Object creation delegate|
|Abstract Factory|Related objects create|
|Builder|Complex object build step-by-step|
|Prototype|Existing object copy|

1. Singleton Design Pattern
	 [[Singleton Design Pattern]]
2. Factory Design Pattern 
	 [[Factory Design Pattern]]
3. Facade Design Pattern
	[[Facade Design Pattern]]
4. Strategy Design Pattern
	[[Strategy Design Pattern]]

### Structural Design Patterns
==**Structural Design Patterns** කියන්නේ **classes සහ objects structure organize කරන patterns**.==
	Large systems වල
	- classes
	- objects
	relationship manage කරන්න.

| Pattern   | Purpose                         |
| --------- | ------------------------------- |
| Adapter   | Incompatible interfaces connect |
| Bridge    | Implementation separate         |
| Composite | Tree structure represent        |
| Decorator | Object functionality extend     |
| Facade    | Simplified interface            |
| Flyweight | Memory usage reduce             |
| Proxy     | Access control                  |

### Behavioral Design Patterns
==**Behavioral Design Patterns** කියන්නේ **objects අතර communication manage කරන patterns**.==

| Pattern                 | Purpose                  |
| ----------------------- | ------------------------ |
| Observer                | Event notification       |
| Strategy                | Algorithm selection      |
| Command                 | Request encapsulation    |
| Iterator                | Collection traversal     |
| Mediator                | Communication control    |
| Memento                 | Object state save        |
| State                   | Object behaviour change  |
| Template Method         | Algorithm structure      |
| Visitor                 | Operation extension      |
| Interpreter             | Language grammar process |
| Chain of Responsibility | Request chain            |

---
### Summary Table of Design Patterns types

| Category   | Main Purpose         |
| ---------- | -------------------- |
| Creational | Object creation      |
| Structural | Object structure     |
| Behavioral | Object communication |
|            |                      |

---
### Architectures vs Design Patterns

| Software Architecture         | Design Pattern              |
| ----------------------------- | --------------------------- |
| Big picture structure         | Small reusable solution     |
| System level decision         | Class level design          |
| Example: Layered Architecture | Example: Factory, Singleton |
