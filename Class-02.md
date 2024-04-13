# Websites and Key Elements to Make it Work

Websites can be very useful tools that allow you to gather valuable information. But, what does it take to get this information prepared and out to the viewr. This section will go through key points and element that will help paint a brighter picture as to how these great websites are created and executed for the consummer to view.


## Deeper Dive into HTML

HTML is nothing without having meaning. The **Semantics** is the element that does this for HTML. What is the purpose of your code, what role is it playing or effect is it having. And there are mmultiple semantics that help do this, one being *headings*.  

**Headings** are representation of section headings. There are 6 levels of headings each having a different level, H1 being the highest and H6 being the lowest.

## Superscript and Subscript

There are times when you will need to place a date or a mathematical problem on you page and you will have to use two element *Superscript* (sup), or a *Subscript* (sub).
A **sup** is what you would use for a date like birthday:  <p>My birthday is on the 15<sup>th</sup> of March 2007.</p>.

An a **sub** is what you would use for the math equation: <p>If x<sup>2</sup> is 9, x must equal 3 or -3.</p>.

Another common element used on websites are **Abreviations**(abbr), which are used to wrap around an abbreviation or acronym <*abbr*>. A full explaination of the abbreviation should follow the <*abbr*> to mark up the abbreviation.

An example of this would be: We use <*abbr*>NASA<*/abbr*>, Nation Aeronautics and Space Administration, to learn more about what's going on in outer space.

It would render like this: We use <abbr>NASA</abbr>, National Aeronautics and Space Administration, to learn what's going on in outer space.

## CSS

CSS (Cascading Style Sheets) is a design or styling language that helps make websites more appealing.   

The purpose of CSS is to take plain text documents and turn them in to eye catching and inspiring websites. The language applies CSS rules that create the ability to style the document by adding pictures, changing the color and size of the text as well as backgound color. All of this so you're able to see the great websites you see today.

## Three ways to insert CSS into a project

There are three ways to insert Cascading Style sheets into a project. 

* External CSS
* Internal CSS
* Inline CSS

### *External CSS*: 
 Gives the ability to change the look of an entire website by changing one file! To do this you must include a reference to the external style sheet file by adding a link element in the Head section that looks like this: *link rel="stylesheet" href="Style.css"*. And now you're able to style in different manners using the external style sheet.

### *Internal CSS*:  
The Internal Style sheet may be used if one single HTML page has a unique style. The internal style is defined inside the style> element, inside the head section, that looks like this body background color update:


*!DOCTYPE html>  
html  
head>  
<style*  
    body {  
        background-color: linen;  
    }

H1 {  
    color: maroon;  
    margin-left: 40px;  
}

### *Inline CSS*:  
Are used to style a single element. To use you must add the style attribute to the relevant element, like this:


!DOCTYPE html>  
html>  
body>

H1 style="color:blue;text-align:center;">This is a heading</>
p style="color:red;">This is a paragraph.</p>

/body>  
/html> 

We should try and not use this type of style due to it is not best practise, it's the least efficient implementation of CSS. One styling might require multiple edits within one page.


## Block of code Questions

1. What is representing the Selector? color: black; and padding: 5px;
2. Which components are the CSS declarations? color: black; and padding: 5px;
3. Which components are sonsidered properties? Color and padding

## Javascript questions

1. What data type is a sequence of text enclosed in single quote marks? string
2. List 4 types of JavaScript operators. addition, subtraction, multiplication and division.
3. Describe a real world Problem you could solve with a Function. How many people are coming to an event. 

## Code making Decisions

1. An if statement checks a **condition** and if it evaluates to **true**, then the code block will execute.
2. What is the use of an else if? It opens up for more choices for example: If a question is asked that could possibly have multiple answers or outcomes the **else..if** allows for more responses for those answers.
3. List 3 different types of comparison operators. **Quoted from MDN web doc** 
The following are three comparison operators:
    * === and !== : test if one value is identical to, or not identical to, another
    * < and > : test if one value is less than or greater than another
    * <= and >= : test if one value is less than or equal to, or greater than or equal to, another

4. What is the difference between the logical operator && and ||? **Quoted from MDN web doc**

    **AND (&&)**: allows you to chain together two or more expressions so that all of them have to individually evaluate to true for the whole expression to return true.

    **OR (||)**: allows you to chain together two or more expressions so that one or more of them have to individually evaluate to true for the whole expression to return true.


## Things I want to Know more About

1. I am running behind so I want to know more about it all!!

