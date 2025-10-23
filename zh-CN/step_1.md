在 JavaScript 中，条件语句用于根据条件在代码中做出决策。 检查条件是否为真，并根据检查结果执行代码。

JavaScript 中有三种类型的条件语句：
`if`、`else if`、`else`。

### if

`if` 用于在满足指定条件（真）的情况下执行代码块。

--- code ---
---
language: js
filename: 
line_numbers: true
---
if (condition) {
  // 如果条件为真则执行代码
}

--- /code ---

### else if

`else if` 用于检查多个条件。 它根据检查结果运行不同的代码块。

当满足 `else if` 条件时，不会对后续的 `else if`（或 `else`）块进行检查。

--- code ---
---
language: js
filename: 
line_numbers: true
---

if (condition1) {
  // 如果 condition1 为真则执行的代码
} else if (condition2) {
  // 如果 condition2 为真则执行的代码
}

--- /code ---

### else

`else` 设置一个替代代码块，如果前面的（`if` 和/或 `else if`）条件不满足（false）则执行该代码块。

--- code ---
---
language: js
filename: 
line_numbers: true
---

if (condition1) {
  // 如果 condition1 为真，则执行的代码
} else if (condition2) {
  // 如果 condition2 为真，则执行的代码
} else {
  // 如果所有条件都不为真，则执行的代码
}

--- /code ---

### 如何编写条件语句

- 使用关键字 `if` 来启动条件语句
- 将要检查的条件放在括号 `()` 内
- 在花括号 `{}` 内添加代码，当条件为真时执行

--- code ---
---
language: js
filename: 
line_numbers: true
---

var age = 18;

if (age >= 18) {
  console.log("你已成年。");
}

--- /code ---


