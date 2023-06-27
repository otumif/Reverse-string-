# Reverse-string-
function reverseString(str) {
  return str.split("").reverse().join("");
}

let text = "Hello, Github!";
let reversedText = reverseString(text);
console.log("Reversed string: " + reversedText);
