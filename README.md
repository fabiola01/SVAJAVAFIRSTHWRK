SVAJAVAFIRSTHWRK
================

SVA BASIC INTRO TO JAVA SCRIPT

<!doctype html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>FirstCode</title>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
<meta name="author" content="The Chopping Block, Inc." />
<meta name="geo.country" content="US" />
<meta name="dc.language" content="en" />
<meta name="description" content="" />
<meta name="keywords" content="" />
<link rel="stylesheet" href="styles.css" type="text/css" media="screen" charset="utf-8" />
<style type="text/css" media="screen">
/*local styles if any (quick tests and local only overrides)*/
</style>
</head>
<body>
<div class="wrap" >
Project: FirstCode/State
<ul>
<li>Display the prompt</li>
<li>Take the value from the prompt and display on the screen</li>
<li>Make 2 prompts, add the strings together and display them on the page</li>
<li>Make a madlibs
  	Ask the user for noun
		Ask the user for a verb
		Ask the user for an adjective
		Place those entries into a sentence that has been prewritten
		Display that on the screen
		
</li>		
</ul>

<p> I always knew Santa Claus existed but I didnt know he drove a</p> 

<p> Story 1: Alice is the name of my dog, and she loves to play with everyone, but most of all, he loves loves to chew on my shoes, and he knows those are not bones!!! </p>

<p> Story 2: Alice is the name of my dog, and she loves to play with everyone, but most of all, he loves loves to chew on my shoes, but the other day I gave her an ultimatum so she chew my dad's shoes! </p>

<p> Story 3: Alice is the name of my dog, and she loves to play with everyone, but most of all, he loves loves to chew on my shoes, after a long walk and my dads and mine shoes destroyed I decided I would buy shoes just for Alice to chew, and we fixed the shoe problem! </p>



<p id="paragraph" class="">

</div>

<script type="text/javascript" charset="utf-8">
	
	//To diplay in screen as "NewYorkLIC"
	
	//var state = "state" + "city"; 
	
	//var noun = "noun" + "verb" + "adjective"; // they display togather but in the same line of the sentence. what am I supposed to add/edit to have them display in the same line with the sentence?
	
	//Variables hold some value->first define the variable
	//var state = "state"; //The value of state is state
	//var city = "city"; //The value of city is city
    

	//Conditionals
	// If something is true then do some actions else do some other actions
    
		var one = 1;
		
		if(one == 1){ 
			console.log("That's 1");
		}else{
			console.log("That's not 1");
		}

    		// six == 6 evaluates to true
			// six == 7 evaluates to false

			// == (2 equal signs) means equality
			// != means not equals
			// > greater than
			// < less than
			// >= greater than or equal to
			// <= less than or equal to


			//six does equal 6, this evaluates to false
			if(one != 1){ 
				console.log("That's 1");
			}else{
				console.log("That's not 1");
			}		
	


   //Prompts

  //var state = prompt("Enter Your State and city"); // this is the only way I was able to get the state and city on the same line paragraph

   //var state = prompt("Enter Your State");
   //var city = prompt("Enter Your City");
 

    //var noun = prompt("Enter a noun, verb, and an adjective"); 

    var one = prompt("Choose a number from 1 - 3"); 

    //Snippets
   
    //This is an easy code snippet to acccess an element on the page
   
    // document.getElementById("state").innerHTML = variable;
    // document.getElementById("city").innerHTML = variable;
   
   //document.getElementById("state").innerHTML = state;
   //document.getElementById("city").innerHTML = city;

   //document.getElementById("paragraph").innerHTML = state;
   //document.getElementById("paragraph").innerHTML = city;
   
   //document.getElementById("paragraph").innerHTML = noun;
   
   document.getElementById("paragraph").innerHTML = one;

</script>
</body>
</html>