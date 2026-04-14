![[Pasted image 20260414101125.png]]
	
	- number
	- string
	- boolean
	- null
	- undefined
	- symbol
	- object

==**variable එක තුළ store කරන value එකේ type** එක.==

```
let age = 25;        // number
let name = "Kamal";  // string
let isStudent = true; // boolean
```



---

# Primitive Data types
### number
==Numbers store numeric values.==
	Integer (whole numbers)  
	Decimal numbers
```
let x = 10;
let price = 99.50;
```

### String
==String = text data (letters, words, sentences)==
```
let name = "Nimal";
let city = 'Colombo';
```

### Boolean
==Boolean = true or false values only.==
```
let isLogin = true;
let isAdmin = false;
```

### null
==null = intentionally empty value==
```
let middleName = null;
```

### Undefined
==variable declare කරලා value assign කරලා නැතිනම් undefined.==
```
let x;
console.log(x);
```

**null → intentionally empty**  
**undefined → value assign කරලා නැහැ**

### Symbol
==unique value create කරන්න use කරන special type.==
```
let id = Symbol("id");
```
mostly advanced programming වල use කරනවා.
symbol used for unique identifiers.

---

# Non-primitive Data type
### Object
==multiple values store කරන්න use කරන complex type.==
**Objects store collections of related data.**

		key-value pairs format.

```
let person = {
 name: "Kamal",
 age: 25
}
```


---


| Data type | example    | description         |
| --------- | ---------- | ------------------- |
| number    | 10         | numeric value       |
| string    | "hello"    | text                |
| boolean   | true       | true or false       |
| null      | null       | intentionally empty |
| undefined | undefined  | value not assigned  |
| symbol    | Symbol()   | unique value        |
| object    | {name:"a"} | collection          |


---

# type of Operator()
