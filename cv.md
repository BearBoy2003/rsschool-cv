# Mikhail Parshin  

> *Aspiring Frontend Developer | HSE Nizhny Novgorod Student | Passionate about Clean Code and Web Technologies*

---

## 📬 Contact Information

- **Location:** Nizhny Novgorod, Russia  
- **Phone:** [+7 930 810-67-44](tel:+79308106744)  
- **Email:** [sdbuh3@mail.ru](mailto:sdbuh3@mail.ru)  
- **GitHub:** [BearBoy2003](https://github.com/BearBoy2003)  
- **Discord:** `f0xes1`

---

## 💡 Self-Introduction

I’m a student at HSE Nizhny Novgorod studying Applied Mathematics and Information Science.
I’ve started learning frontend development — HTML, CSS, JavaScript, and Git — mostly through practice and online courses like RS School.
I’m not experienced yet, but I’m eager to learn, solve problems step by step, and build things that work.
I like when code is clear and easy to understand — and I’m working on getting better every day.

---

## ⚙️ Skills

- **Languages:** JavaScript (ES6+), Python, HTML5, CSS3  
- **Libraries & Tools:** Pandas, NumPy, Git, GitHub  
- **Concepts:** DOM Manipulation, Responsive Design, Functional Programming, Algorithmic Thinking  
- **Development Practices:** Version Control, Code Readability, Debugging  
- **Learning Focus:** React, TypeScript, Flexbox/Grid, Testing Basics

---

## 💻 Code Example

**Task:** [Valid Phone Number (6 kyu)](https://www.codewars.com/kata/525f47c79f2f25a4db000025)  
*Validate a phone number in one of these formats:  
`(123) 456-7890`, `123-456-7890`, or `123.456.7890`*

```javascript
function validPhoneNumber(phoneNumber) {
  const pattern = /^\(\d{3}\)\s\d{3}-\d{4}$|^\d{3}-\d{3}-\d{4}$|^\d{3}\.\d{3}\.\d{4}$/;
  return pattern.test(phoneNumber);
}

// Test cases:
console.log(validPhoneNumber("(123) 456-7890")); // true
console.log(validPhoneNumber("123-456-7890"));   // true
console.log(validPhoneNumber("123.456.7890"));   // true
console.log(validPhoneNumber("1234567890"));     // false
console.log(validPhoneNumber("(123) 456-789"));  // false
