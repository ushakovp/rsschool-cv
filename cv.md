# Pavel Ushakov

log9099@gmail.com  
Discord: Pavel Ushakov (@ushakovp)

# Summary

Quality Assurance Engineer with experience in manual and automation testing of web-based and desktop applications:

-   test documentation and test plan development
-   creating and executing manual tests
-   test design and test framework implementation
-   creating and executing automated tests for web applications in Cypress with JavaScript.
-   creating and maintaining API automation test scripts using Postman

# Skills:

-   Knowledge of SDLC, Agile
-   Creating check-lists, test-cases, bug reports
-   Tech:
    -   Languages: JavaScript, HTML, CSS, SQL
    -   Frameworks/Libraries: Cypress,Playwright
    -   API: Postman, SOAP UI
    -   DB: MySQL, PostgreSQL
    -   Bug Tracking & Management Tools: JIRA, HP ALM
    -   Version control / CI: Git, Jenkins,
    -   OS: Windows, Android, Linux

# Code example

## Students final grade

Create a function finalGrade, which calculates the final grade of a student depending on two parameters: a grade for the exam and a number of completed projects.

This function should take two arguments: exam - grade for exam (from 0 to 100); projects - number of completed projects (from 0 and above);

This function should return a number (final grade). There are four types of final grades:

    100, if a grade for the exam is more than 90 or if a number of completed projects more than 10.
    90, if a grade for the exam is more than 75 and if a number of completed projects is minimum 5.
    75, if a grade for the exam is more than 50 and if a number of completed projects is minimum 2.
    0, in other cases

Solution

```
function finalGrade(exam, projects) {
    if(exam > 90 || projects > 10) return 100;
    if(exam > 75 & projects >= 5) return 90;
    if(exam > 50 & projects >= 2) return 75;
    return 0;
}
```

# Experience

**QA Engineer**  
Performance lab  
_aug 2020 - Present_

# Education

Izhevsk State Technical University  
Bachelor of Computer Science  
_Feb 2022_

# Languages

Russian - Native speaker  
English - B2 Upper Intermediate
