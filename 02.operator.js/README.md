Here’s a clean **GitHub README.md** version of your JavaScript Operators notes — ready to copy and paste 👇

---

````markdown
# 📘 JavaScript Operators

Operators are symbols used to perform operations on variables and values.

---

## 1️⃣ Arithmetic Operators
Used to perform mathematical calculations.

| Operator | Description | Example |
|----------|------------|----------|
| `+` | Addition | `10 + 5 // 15` |
| `-` | Subtraction | `10 - 5 // 5` |
| `*` | Multiplication | `10 * 5 // 50` |
| `/` | Division | `10 / 5 // 2` |
| `%` | Modulus (Remainder) | `10 % 5 // 0` |

### Example:
```javascript
let a = 10;
let b = 5;

console.log(a + b); // 15
console.log(a - b); // 5
console.log(a * b); // 50
console.log(a / b); // 2
console.log(a % b); // 0
````

---

## 2️⃣ Assignment Operators

Used to assign values to variables.

| Operator | Description         | Example  |
| -------- | ------------------- | -------- |
| `=`      | Assign              | `x = 10` |
| `+=`     | Add and assign      | `x += 5` |
| `-=`     | Subtract and assign | `x -= 3` |
| `*=`     | Multiply and assign | `x *= 2` |
| `/=`     | Divide and assign   | `x /= 2` |
| `%=`     | Modulus and assign  | `x %= 3` |

### Example:

```javascript
let x = 10;

x += 5; // 15
x -= 3; // 12
```

---

## 3️⃣ Comparison Operators

Used to compare two values. They return `true` or `false`.

| Operator | Description                 | Example              |
| -------- | --------------------------- | -------------------- |
| `==`     | Equal (value only)          | `5 == "5" // true`   |
| `===`    | Strict Equal (value + type) | `5 === "5" // false` |
| `!=`     | Not Equal                   | `5 != "5" // false`  |
| `!==`    | Strict Not Equal            | `5 !== "5" // true`  |
| `>`      | Greater than                | `10 > 5 // true`     |
| `<`      | Less than                   | `10 < 5 // false`    |
| `>=`     | Greater than or equal       | `10 >= 10 // true`   |
| `<=`     | Less than or equal          | `5 <= 10 // true`    |

---

## 4️⃣ Logical Operators

Used to combine multiple conditions.

| Operator | Name               | Description                                                        |
| -------- | ------------------ | ------------------------------------------------------------------ |
| `&&`     | AND                | Both conditions must be true                                       |
| `\|\|`   | OR                 | At least one condition must be true                                |
| `!`      | NOT                | Reverses a boolean value (`true` → `false`, `false` → `true`)      |
| `??`     | Nullish Coalescing | Returns the right value if the left value is `null` or `undefined` |

### Example:

```javascript
let age = 20;
let hasID = true;

console.log(age > 18 && hasID); // true
console.log(age < 18 || hasID); // true
console.log(!hasID); // false
```

---

## ✅ Summary

* Arithmetic operators → Perform math
* Assignment operators → Assign values
* Comparison operators → Compare values
* Logical operators → Combine conditions

---

