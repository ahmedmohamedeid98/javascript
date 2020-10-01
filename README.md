# javascript
<h1>Javascript Notes for Beginners</h1>
<br>
We are going to discuss about important Notes of Javascript and going to share important Links
<h2>What is Javascript</h2>
<br>
JavaScript is a dynamic computer programming language. It is lightweight and most commonly used as a part of web pages, whose implementations allow client-side script to interact with the user and make dynamic pages. It is an interpreted programming language with object-oriented capabilities.
<br>
<h2>Advantages of Javascript</h2>
<b>Less server interaction − </b>You can validate user input before sending the page off to the server. This saves server traffic, which means less load on your server.
<br>
<b>Immediate feedback to the visitors −</b> They don't have to wait for a page reload to see if they have forgotten to enter something.
<br>
<b>Increased interactivity − </b>You can create interfaces that react when the user hovers over them with a mouse or activates them via the keyboard.
<br>
<b>Richer interfaces −</b> You can use JavaScript to include such items as drag-and-drop components and sliders to give a Rich Interface to your site visitors.
<br>
<h2>Variables & Literals</h2>
A variable is a container which has a name. We use variables to hold information that may change from one moment to the next while a program is running.
<br>
A literal, by contrast, doesn't have a name - it only has a value.
<br>
<h2>Operators</h2>
Operators are a type of command. They perform operations on variables and/or literals and produce a result.
<b>
JavaScript understands the following operators:

+	Addition
-	Subtraction
*	Multiplication
/	Division
%	Modulus
</b>

<h2>JavaScript Function as First-class object</h2>

A function can:
<br>
Assigned to variables
Assigned to a property of an object
Passed as an paramter
Returned as function result
Created using literals
Function is not a named entity: function keyword creates a Function instance and assigned it to a window property if you delcare such at top-level. For example, the following two forms are the same:
<br><br>

<h2>JavaScript, Create Your Own Object</h2>

<b>3.1. Create a direct instance of an object</b>
with 3 properties, you can just assign it.
p = new Object();
p.firstName = "John"
p.lastName = "Oliver"
p.age = 50;
3.2. Create object template
function person(firstname, lastname, age)
{
    this.firstname = firstname;
    this.lastname = lastname;
    this.age = age;

    this.workhours = workhours;
}
Notice that:
<b>
An object tempalte is just plain function.
You can attach method workhours to it, by then you have to define it somewhere.
Once you have object template, you can create many instance of it now.
</b>

>## Important Souces to Learn javascript
<ul>
<li>https://javascript.info/ </li>
<li>https://www.tutorialspoint.com/javascript/javascript_quick_guide.htm </li>
</ul>

>## Best Book to Learn Javascript
<ul>
<li>JavaScript for Kids: A Playful Introduction to Programming” by Nick Morgan</li>
<li>“Eloquent JavaScript: A Modern Introduction to Programming” by Marijn Haverbeke<li>
<ul>












