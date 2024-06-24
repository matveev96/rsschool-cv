# **Aliaksandr Matsveyeu**

## Contacts:
* Telegram: @penzlik
* Email: sasha.matveev1996@gmail.com
* Github account: https://github.com/matveev96
* Discord: alex965156

## About me:
I'm 28. My goal is to achieve high results in my studies on the course, and in the future to find a dream job and engage in interesting projects together with a team of like-minded people. My strengths are perseverance and determination, concentration in educational projects and thirst for learning new material.

## Skills (Basic knowlage):
* Git, GitHub
* HTML5, CSS
* JavaScript
* Figma
* VS Code

## Code example:
**JavaScript-code:**
*DESCRIPTION Kata from CODEWARS:*
*As part of this kata, you need to find the length of the sub-array that begins and ends with the specified number.*
*For example, if the array arr is [0, -3, 7, 4, 0, 3, 7, 9], finding the length of the sub-array that begins and ends with 7s would return 5.*
*For sake of simplicity, there will only be numbers (positive or negative) in the supplied array.*
*If there are less or more than two occurrences of the number to search for, return 0.*
```
var lengthOfSequence = function (arr, n) {
  // TODO: Write some scripts here
  
  var indices = [];
  var idx = arr.indexOf(n);
  
  while (idx != -1) {
    indices.push(idx);
    idx = arr.indexOf(n, idx + 1);
  };
  
  if (indices.length === 2) {
    return indices[indices.length - 1] - indices[0] + 1;
  } else {
    return 0;
  };
};
```

## Education:
* BSTU (Belarusian state technological university) - Organic Substances Technology Faculty (2015-2019)
* SkyEng - Pre-intermediate course (2019-2020)
* freeCodeCamp - JavaScript Algorithms and Data Structures
* freeCodeCamp - Responsive Web Design

## Languages:
* English (A2 Pre-Intermediate)
* Belarusian (Native)
* Russian (Native)