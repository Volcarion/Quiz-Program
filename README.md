# Quiz Program

This program will randomly select *students* and *questions* for a quiz

1. The begin button shows the intially picked student and question
2. It has two buttons to mark if they got it correct or incorrect
3. It has a button to show and hide scores

[Angularjs questions](https://www.codementor.io/angularjs/tutorial/angularjs-interview-questions-sample-answers)

```javascript
            $http.get("students.json").then(function (response) {
            qc.students = response.data.students;
            });
            
            $http.get("questions.json").then(function (response) {
            qc.questions = response.data.questions;
            });

```