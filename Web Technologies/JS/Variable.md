![[Pasted image 20260414084146.png]]


---

# Variable declaration types

JavaScript වල variables declare කරන්න **3 methods** තියෙනවා:
	1️⃣ **var**  
	2️⃣ **let**  
	3️⃣ **const**

![[Pasted image 20260414084239.png]]

==**const → default**  
**let → if value change needed**  
**var → avoid**==

| type  | used                   |
| ----- | ---------------------- |
| let   | if value change needed |
| const | default                |
| var   | avoid                  |

---

# Var
	
	var → function scope (Non-block scope variable).  
	var → re-declare allowed.
	

**Old method** එක variable declare කරන්න.
```
var name = "Kamal";
```

var variable එක **==function එක ඇතුළත ඕනෑම තැනක access== කරන්න පුළුවන්**.

```
function test(){
   var x = 10;
   if(true){
      var x = 20;
   }
   console.log(x);
}
```

	out put = 20
	reason:  
	var block scope support නොකරයි.

```
var x = 10;
var x = 20; // allowed
```
var variables are function-scoped and allow re-declaration.


---

# Let
let කියන්නේ ==**modern variable declaration method**==.
```
let age = 25;
```

let variable එක **=={ } code block ඇතුළත විතරයි== work වෙන්නේ**.

```
if(true){
   let x = 10;
}
console.log(x);
```
	
	error:- x is not defined. 

**==Re-assign allowed.**
**Re-declare not allowed.**==


---

# Const

	const = constant
	
==const variable value **change කරන්න බැහැ**.==
```
const PI = 3.14;
```

=={ } code block ඇතුළත විතරයි.==

```
const x = 10;
x = 20;
```
==Re-assign not allowed.==

```
const person = {
 name:"Kamal"
}

person.name="Nimal"; // allowed
```
==const object values change කරන්න පුළුවන්.==


| feature    | var      | let   | const |
| ---------- | -------- | ----- | ----- |
| scope      | function | block | block |
| reassign   | yes      | yes   | no    |
| redeclare  | yes      | no    | no    |
| modern use | no       | yes   | yes   |


![[Pasted image 20260414084326.png]]

![[Pasted image 20260414091126.png]]

![[Pasted image 20260414091142.png]]


[[Data type]]