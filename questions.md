## Personal details

Name: Tuan Nguyen

Country: Vietnameses

Hourly Rate: $11

Timezone: GMT+7

Skype Id: tuannguyen2042

## Availability

Are you able to work from 3PM to 7PM (GMT -2) ? In case you aren't, what's your availability?
Can't work at 3PM to 7PM (GMT-2), it is midnight here. I can work from 11AM to 3PM (GMT-2)
 
## Tech Skills

Assing yourself a score in the following technologies:


Object Oriented Programming (OOP) - 8/10

Git -  6/10

PHP 5 - 8/10

CakePHP framework - 8/10

MySQL -  8/10

Javascript - 6/10

jQuery - 6/10 

HTML - 7/10

CSS - 7/10

## Questions About OOP:

- How do you declare a function or method that you want to be accessed without instantiate the class?
- Answer: you can declare a static function or method.

- How do you create a child class of BaseClass ?
- Answer: class ChildClass extends BaseClase {}

 
## Questions about GIT:

- If you accidentally add the wrong files to be commited using git add, how do you unstage them?
- Answer: You can use this command: git reset HEAD path/to/file

- If you want to switch to another branch, what command you need to execute?
- Answer: use command: git branch branch_name

 
## Questions about PHP 5:

- Please write a conditional block of code that check if the variable $var exists, is not null and it's a number.
- Answer: if (isset($var) && !is_null($var) && is_numeric($var))

- Write a function that adds a line to a log file the current date and time with this format: "[2013-09-23 00:3 0:15] - Status OK"
- Answer: 
  function writeLog($text){
    $line = '['.date('Y-m-d H:i s:u.'] - '.$text;
    error_log($line); 
  } 

## Questions about CakePHP

- Which is the default path where you set up the configuration for the database?
- Answer: modify elements of property $default in /app/Config/database.php

- How you can get the value of a session variable with key "foo" using CakePHP ?
- Answer: $this->Session->read('foo');

## Questions about MySQL

- Write a single query to retrieve the information from 2 tables that are related( users and users_data) where the primary key on users is ID and the foreign key on users_data is USER_ID.
- Answer: SELECT * FROM users u LEFT JOIN users_data ud ON (ud.USER_ID=u.ID);

- Write a single query to retrieve all the queries that are currently running on the server .
- Answer: show processlist;

## Questions about Javascript

- How do access to the alt attribute of the following image element using javascript? <img src='http://example.com/image.jpg' id='some_img' alt='lol' />
- Answer: var attr = document.getElementById("some_img").getAttribute("alt");

- What is the protocol name behind ajax?
- It's Asynchronous JavaScript and XML

## Questions about jQuery

- Write a piece of javascript code using jQuery that make the el ement with id "someElement" to appear on the screen using a fade in effect after the DOM is loaded.
- Answer: 
$(document).ready(function(){
  $("#someElement").fadeIn("slow");
})

- How do you remove an element from the DOM using jQuery?
- Answer: $("#someElement").remove();
 
## Questions about HTML

- Which is the doctype syntax for HTML5?
- Answer: <!DOCTYPE html> 

- Which is the attribute and value required on forms to allow file uploads?
- Answer: <form method="post" enctype="multipart/form-data">

## Questions about CSS

- Which is the css property and its value to force to hide the scroll on any DOM element with fixed height when its content exceed its own height?
- Answer: overflow-y:hidden

- If you have to div elements next to each other with the property float:left, which CSS property do you need to add to the next element in order to get both of them to fill the same height on page and make the next one not a floating one?
- Answer: float:left; clear:both;

## Questions about Linux / Unix based OS

- Which protocol(s) you could use to connect to a server SHELL remotely?
- Answer: ssh

- Write a command to look for the word "ads" on all files with .ctp extension in the same directory
- Answer: grep "ads" *.ctp
