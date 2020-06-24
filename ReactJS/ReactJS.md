## Differentiate between Real DOM and Virtual DOM.

1. Real DOM
   -It updates slow.
   -Can directly update HTML.
   -Creates a new DOM if element updates.
   -DOM manipulation is very expensive.
   -Too much of memory wastage.

2. Virtual DOM
   -It updates faster.
   -Can’t directly update HTML.
   -Updates the JSX if element updates.
   -DOM manipulation is very easy.
   -No memory wastage.

## What is React?

-React is a front-end JavaScript library developed by Facebook in 2011.
-It follows the component based approach which helps in building reusable UI components.
-It is used for developing complex and interactive web and mobile UI.
-Even though it was open-sourced only in 2015, it has one of the largest communities supporting it.

## What are the features of React?

1. Major features of React are listed below:
   -It uses the virtual DOM instead of the real DOM.
   -It uses server-side rendering.
   -It follows uni-directional data flow or data binding.

## List some of the major advantages of React.

1. Some of the major advantages of React are:
   -It increases the application’s performance
   -It can be conveniently used on the client as well as server side
   -Because of JSX, code’s readability increases
   -React is easy to integrate with other frameworks like Meteor, Angular, etc
   -Using React, writing UI test cases become extremely easy

## What are the limitations of React?

1. Limitations of React are listed below:
   -React is just a library, not a full-blown framework
   -It's library is very large and takes time to understand
   -It can be little difficult for the novice programmers to understand
   -Coding gets complex as it uses inline templating and JSX

## 6. What is JSX?

-JSX is a shorthand for JavaScript XML.
-This is a type of file used by React which utilizes the expressiveness of JavaScript along with HTML like template syntax.
-This makes the HTML file really easy to understand.
-This file makes applications robust and boosts its performance.
-Below is an example of JSX:

render(){
return(

<div>             
<h1> Hello World from Edureka!!</h1>
 
         </div>
 
    );
}
