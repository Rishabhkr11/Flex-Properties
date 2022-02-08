`````js
/**

- Returns a letter grade.
- "A": 90-100%
- "B": 80-89%
- "C": 70-79%
- "D": 60-69%
- "F": 0-59%
- @param {number} score
- @param {number} total maximum possible score
- @return {string} the score represented as a letter grade
/**

function result(marks) {
    if (marks <= 100 && marks >= 90){
        return "A";
    } else if (marks <= 89 && marks >= 80){
        return "B";
    } else if (marks <= 79 && marks >= 70){
        return "C";
    } else if (marks <= 69 && marks >= 60){
        return "D";
    } else if (marks <= 59 && marks >= 0){
        return "Fail";
    } else {
        return "Please enter marks between 0 to 100";
    }
````
`````
