# Formatting Strings

  What if we want to print a full name in one variable:

  `Haris Samingan`

How do we do it? Well, we can use this:

```javascript
const firstName = 'Haris';
const lastName = 'Samingan';
const fullName = `${firstName} ${lastName}`;
console.log(fullName);
```

This should print out:

```
Haris Samingan
```

## Explanation 

This is called formatting string. The backtick (`) character is used to enclose the string. `${}` is used to reference the variables inside the string. It converts them into string values.

## Exercise
1. Create a variable called `firstName` and assign it to your first name as a string e.g. `'Haris'`.
```javascript
const firstName = 'Haris';
```

1. Create a variable called `lastName` and assign it to your last name as a string e.g. `'Samingan'`.
```javascript
const lastName = 'Samingan';
```

1. Create a variable called `fullName` and assign it to a formatted string in this format:
```javascript
const fullName = `${firstName} ${lastName}`;
```

4. Console log `fullName`
```javascript
console.log(fullName);
```
5. It should look like this in console:
```
Haris Samingan
```

<details>
<summary>Answer</summary>

```javascript
const firstName = 'Haris';
const lastName = 'Samingan';
// space between the curly brackets
const fullName = `${firstName} ${lastName}`; 
console.log(fullName);
```
</details>

## Take note
If you format it like this:
```javascript
const firstName = 'Haris';
const lastName = 'Samingan';
// no space between the curly brackets
const fullName = `${firstName}${lastName}`; 
console.log(fullName);
```
It will print:

`HarisSamingan`