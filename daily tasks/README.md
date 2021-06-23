June 16, 2021
to read - https://stackoverflow.com/questions/5641997/is-it-necessary-to-write-head-body-and-html-tags
task
    create a simple html file containing of elements that helps to build a rough portfolio
    doc for the difference between <div>, <article>, <section> tag?
    write a doc for the following below
        typeof(1)
        typeof(1.1)
        typeof('1.1')
        typeof(true)
        typeof(null)
        typeof(undefined)
        typeof([])
        typeof({})
        typeof(NaN)
    read what is prototype

---------------------------------------------
June 17, 2021
Task
    1)
    var obj = [
          { person: "Name 1", age: "2", company: "GUVI" },
          { person: "Name 2", age: "5", company: "GUVI geek" },
          { person: "Name 3", age: "8", company: "GUVI geek network" },
        ]
    use the above JSON to iterate over all for loops (for, for in, for of, forEach)
    2)
        var xhr = new XMLHttpRequest();
        xhr.open("GET", "https://restcountries.eu/rest/v2/all");
        xhr.onload = function () {
          var data = JSON.parse(this.response);
          console.log(data);
        };
        xhr.send();
    use the restcountries API url ->  https://restcountries.eu/rest/v2/all
    and diplay all the country flags in console
    3) 
    use the same restcountries and print all countries name, region, sub region and population.
    4) read abouyt the difference between window, screen and document in javascript
---------------------------------------------
Jun 18, 2021
Task 
    1) create your own resume data in JSON format
    2) how to compare two JSON have the same properties without order?
        var obj1 = { name: "Person 1", age:5 };
        var obj2 = { age:5, name: "Person 1" };
    3) https://medium.com/@reach2arunprakash/www-guvi-io-zen-d395deec1373
---------------------------------------------
Jun 21, 2021
Task
    1) Do the below programs in anonymous function & IIFE
        Print odd numbers in an array 
        Convert all the strings to title caps in a string array
        Sum of all numbers in an array
        Return all the prime numbers in an array
        Return all the palindromes in an array
        Return median of two sorted arrays of same size 
        Remove duplicates from an array
        Rotate an array by k times 
    2) https://medium.com/@reach2arunprakash/guvi-zen-class-javascript-warm-up-programming-problems-15973c74b87f
    3) Do the below programs in arrow functions
        Print odd numbers in an array 
        Convert all the strings to title caps in a string array
        Sum of all numbers in an array
        Return all the prime numbers in an array
        Return all the palindromes in an array
