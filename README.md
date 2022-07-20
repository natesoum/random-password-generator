# random-password-generator

// Psuedo-code


// For the following functions this website was used as reference : https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/charCodeAt
// Function for getting a random lowercase letter (ASCII Table)

var password = userInput
function getRandomLower() {
    return String.fromCharCode(Math.floor(Math.random() * 26) + 97);
}

// Function for getting a random uppercase letter (ASCII Table)
function getRandomUpper() {
    return String.fromCharCode(Math.floor(Math.random() * 26) + 65);
}

// Function for getting a random number (ASCII Table)
function getRandomNumber() {
    return String.fromCharCode(Math.floor(Math.random() * 10) + 48);
}

function getRandomSpecChars() {
  var specChars = "!#$%&'()*+,-./:;<=>?@[\]^_`{|}~"; // Took out double quotes because function will cause an error if double quotes was included and string was wrapped with dou
  return specChars[Math.floor(Math.random() * specChars.length)];
}


----------------

DECLARE Variables
string / password (the result)
num    / passLength (user input)
bool   / useUpper (user input)
bool   / useLower (user input)
bool   / useSpecial (user input)
bool   / useNumber (user input)
arr    / lowerChars (choices)
arr    / upperChars (choices)
arr    / specChars = "!"#$%&'()*+,-./:;<=>?@[\]^_`{|}~" (choices)
arr    / numChars (choices)
arr    / choices (array containing all characters chosen by the user) 

# Objective 

I am creating a password generator for users.

USER will click "Generate Password" button

USER will be prompted with the desired length of password. Length will be ranging from 8 - 128 characters.
IF user input is between 8 - 128, store desired length in VAR password
IF user input isn't between 8 - 128, program will end and user will have to click the "Generate Password" button again

AFTER choosing desired length between 8 - 128
USER will be prompted with the choice of their password to contain uppercase letters (upperChars)
IF yes, user's password will randomly select characters within the choices of uppercase letters (upperChars)
IF no, user's password will not contain any uppercase letters (upperChars)

AFTER user chooses whether or not their password will contain uppercase letters (upperChars)
USER will be prompted with the choice of their password to contain lowercase letters (lowerChars)
IF yes, user's password will randomly select characters within the choices of lowercase letters (lowerChars)
IF no, user's password will not contain any lowercase letters (lowerChars)

AFTER user chooses whether or not their password will contain lowercase letters (lowerChars)
USER will be prompted with the choice of their password to contain special characters (specChars)
IF yes, user's password will randomly select characters within the choices of special characters (specChars)
IF no, user's password will not contain any special characters (specChars)

AFTER user chooses whether or not their password will contain special characters (specChars)
USER will be prompted with the choice of their password to contain numbers (numChars)
IF yes, user's password will randomly select characters within the choices of numbers (numChars)
IF no, user's password will not contain any numbers 

USERS MUST choose at least one password input type
THEN a password from the user desired choices will appear in either a alert or written on the page

## What was your motivation?

My motivation for this project is to create a random password generator for users to get a user-desired password! I also wanted to practice the skills I've learned recently to help them "stick" more. There's no better way to learn than to build stuff! I want to broaden my knowledge on my very beginner skills of JavaScript. This project was to help myself build a strong foundation to build upon as time goes on. I hope you enjoy my project and I will enjoy any feedback you have! 

## Why did you build this project? 

## What problem does it solve?

## What did you learn?

## What makes your project stand out?