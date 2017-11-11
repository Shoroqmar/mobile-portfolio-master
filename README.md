## Website Performance Optimization portfolio project

- First I had to check the sccore of the website on PageSpeed insights for both pages index.html / pizza.html using ngrok ,
  both of them achived a score of 71/100 , which is bad . 
  
  ** a screen shot of the scrore :
  (https://imgur.com/HdINJVn)

- The great thing about page speed that it's give you some adives on how to do the optimiaztion . 

- I statred to read and study every code and write some notes on how to optimazie it and reading the google page speed insights advices . 

 - Eliminate the style.css file , and moved the css into the index.html file , moving js scripts into the end of index.html to make the last thing to render in the page to improve page respnse , in order to display the basic page without animation first then start to do the interactiviy. 
 
 - Resize pizaria.jpg as requird . 
 
 - Removing the code that bring the font from the internt . 
 
* Doing this the i got a score of 99/100 : 
(https://imgur.com/a/K3y0O)

- Moving to work on pizza.html file , and moving the css content into the pizza.html . 

_ Changes done to main.js included :

   * Changing querySelector into getElementById and getElementByClassName.
   
   * Moving some parameters and variables outside loops so it's called only one time not every iteration in order to improve the rendering .
   
   * Eliminate some functions and line of codes . 
   
   * Change document.body.scrollTop into  document.documentElement.scrollTop . 
   
   To view the index.html and Pizza.html page download all the files and open them in your browser . 
   Or use the Link for github pages : 
   
   