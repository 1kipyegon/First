// Prompt the user for three numbers
var num1 = parseFloat(prompt("Enter the first number:"));
var num2 = parseFloat(prompt("Enter the second number:"));
var num3 = parseFloat(prompt("Enter the third number:"));

// Check which number is the greatest
if (!isNaN(num1) && !isNaN(num2) && !isNaN(num3)) {
    if (num1 >= num2 && num1 >= num3) {
        alert("The greatest number is: " + num1);
    } else if (num2 >= num1 && num2 >= num3) {
        alert("The greatest number is: " + num2);
    } else {
        alert("The greatest number is: " + num3);
    }
} else {
    alert("Invalid input. Please enter valid numbers.");
}
