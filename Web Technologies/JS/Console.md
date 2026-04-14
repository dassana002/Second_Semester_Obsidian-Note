![[Pasted image 20260414110431.png]]

==**Console** කියන්නේ **browser එකේ debugging tool එකක්**. ==
JavaScript code run කරනකොට **messages, errors, values display කරන්න** console use කරනවා.

| method          | purpose             |
| --------------- | ------------------- |
| console.log()   | normal output       |
| console.error() | error message       |
| console.warn()  | warning message     |
| console.info()  | information message |
| console.clear() | clear console       |
| console.table() | show table          |

### Why console important?
Programming කරනකොට ==errors හොයාගන්න සහ values check කරන්න== use කරනවා.
	example:
		- variable value check
		- error detect
		- code working flow understand
		- debugging

# console.log()
==**normal message print කරන්න** භාවිත කරන method එක.==
```
console.log("Hello world");
```

# console.error()
==error message display කරන method එක.==
```
console.error("Something went wrong");
```

# console.warn()
==**warning messages display කරන method එක.==
```
console.warn("Password is weak");
```

# console.info()
==**information messages display කරන method එක.==
```
console.info("User logged in");
```

# console.clear()
==**console screen clear කරන method එක.**==
```
console screen clear කරන method එක.
```

# console.table()
==**array or object data **table format එකෙන් display කරන method**.==
```
let students = [
 {name:"Kamal", age:20},
 {name:"Nimal", age:22}
];

console.table(students);
```

