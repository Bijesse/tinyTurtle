JS Functions: Tiny Turtle
==========
![image](http://i.imgur.com/dFYyMbH.png)

## Before class
The teacher should become familiar with the Tiny Turle library and how to create functions within it.


### Objective

Students will able to call and create functions in JavaScript.

### Key points

* We use functions so that we do not have to rewrite code over again.
* A function is a block of code that performs a task. To use a function, you must call it. 
* A parameter is a value or variable that is passed into a function. The function uses this variable to help perform its task.

### Assessment

Students will show progress toward reaching the objective based on their ability to manipulate the Tiny Turtle about the console.

### Vocabulary

* Function
* Algorithm
* Library
* Call
* Open/close curly brace
* Parameter
* Console
* Debug
* Canvas Tag 



### Resources

* [API documentation](https://github.com/toolness/tiny-turtle#api)  
* [Tiny Turtle Tutorial](http://toolness.github.io/tiny-turtle/tutorial/)  
* [Global Objects Reference:](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects)
* [Tiny Turtle Library .js file](http://toolness.github.io/tiny-turtle/tiny-turtle.js)

## During class

### Do-now

1. Attendance: Teacher takes student attendance 
2. On paper: Write step by step directions of how to walk in a square. Remember to be very specific.

### Opening

Today we will use Javascript to create functions. Functions are used to package large amounts of code into a simple line.  

JavaScript functions are similar to the functions you us in math class in that they save time by storing a lot of information.

### Introduction of new material ("I do")
Tiny Turtle is a library which allows us to quickly visualize JavaScript functions. Our code will be written in a .js file while the visualizations will appear in the console. The teacher should show a finished model of Tiny Turle moving about the console without allowing students enough time to fully study the code.

Tiny Turtle is a **library**, so we will need to link to the file in our HTML. Let's create that script tag now.

```
<body>  
  <script src="http://toolness.github.io/tiny-turtle/tiny-turtle.js">
  </script>
</body>
```
Encourage students to open the library link in a seperate tab to explore the 50 line library.

We are also going to need to give our Tiny Turtle a stage to move around on. We are going to do this using the canvas tag.

```
<body>  
    <canvas width="300px" length="300px" style="border:1px solid">
    </canvas>
  <script src="http://toolness.github.io/tiny-turtle/tiny-turtle.js">
  </script>
</body>
```
Can someone please tell me what the purpose of the canvas tag is? Can someone else tell was the purpose of the script tag is?

### Guided practice ("We do")
The first line of JavaScript we need to write will tell the Tiny Turtle to move inside the canvas:

```
	TinyTurtle.apply(window); 
```

The next thing we will write is our first function which will move the Tiny Turtle 30 steps.

```
	forward(30);
```
You will now see the line in your canvas. In this line of code, the function is called forward and the parameter, or the value which is passed through the function is 30. 

Next we are going to show which direction the turtle is pointing and turn it 90 degrees. This can be done by doing the following:      
1. write a function called right with a parameter of 90  
2. write a function called stamp with no parameter (this function will show the arrow head)

```
	forward(30);
	right(90);
	
	stamp();
```
![Image](http://i.imgur.com/cvzfj9c.png)

Now that you have moved the Tiny Turtle, Let's try and make it move in a square. From here the teacher may work with the students on creating this square or the teacher may elect to allow students to solve on their own. 

### Independent practice ("You do")
Great! The Tiny Turtle can now move in a square but there is only one problem. This code is too long. In order to clean this code up we are going to create a **function.** 

1. On line two create the function`function square (length);{}`
2. Within the curly brackets place the code used earlier to move tiny turtle in a square.
3. After the curly brackets are closed call on the square function like so `square(40);{}`
4. Now that you have one square written, create art by using various rotations and creating functions for all sorts of shapes. you may use the [Tiny Turtle Tutorial](http://toolness.github.io/tiny-turtle/tutorial/) as a reference.



### Closing

A function stores information. In the example of the square function, how were we able to save time and confusion by using the function?

#### Homework
Students are encouraged to take a lcose look at the Tiny Turtle Library and see if they can manipulate any part of it.


## After class

* Prepare for next lesson / hand off to next teacher in rotation.

