# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [false] `<div><span>hello</div></span>`

b) [false ]

```html
<ul>
<li>one</li>
</ol>
```

c) [true] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

A software which renders written content/an operating system into speech, namely for people with visual or learning disabilities.
sources https://www.nomensa.com/blog/2005/what-screen-reader
        https://en.wikipedia.org/wiki/Screen_reader 

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

<img></img>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
<ol></ol> or <ul></ul> to have all museums in a list
<li></li> for each item in the list
<a> </a> for external links to their respective websites

c) You want to sell designer hats. You need to receive orders from the user.

<form></form> & <input></input> for the client to input their orders & personal info. 
A <button></button> to submit the order. 

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
No, a button cannot have a child that is interactive in nature. 
 source: https://html.spec.whatwg.org/multipage/form-elements.html#the-button-element 

## Q5 - What is the most generic tag you can use?

<div></div>

## Q6 - What do the following achronyms stand for?

a) `a`  anchor - reference to a hyperlink 

b) `ol` ordered list

c) `ul` unordered list

d) `li` list item

e) `tr` row in an HTML table

f) `th` header cell in HTML table

g) `td` data cell in HTML table

source : https://www.w3schools.com/tags/

## Q7 - Usually, `td` elements are children of what kind of elements? 
<tr> </tr>

source : https://developer.mozilla.org/en-US/docs/Web/HTML/Element/td

## Q8 - What is the difference between td and th?
td is used to contain data (in a cell) and th adds a header attribute to a column in a table.
source : https://www.w3schools.com/tags/tag_th.asp
https://www.w3schools.com/tags/tag_td.asp 

## Q9 - Which tag makes the text appear bigger: h1 or h3?

h1 will be the most important (bigger) header but font size should be determined in CSS, not HTML

## Q10 - In which situation can you use self closing tags?
for void items such as images <img> or links <a> which cannot contain anything but the content they are referencing. 

## Q11 - What is autofilling and why is it important?
A feature which allows a browser to store commonly entered values in a given field, to potentially be reused in the future, which saves time. ex: if a user were to fill out a form for which the values for 'name', 'address', 'email' were already entered in a previous form, (and saved by the browser) that information is recognized by the browser and is automatically applied to the form being filled. 

Basically the browser fills in the gaps with data it has already stored from previous entries. 

source: https://cloudfour.com/thinks/autofill-what-web-devs-should-know-but-dont/

## Q12 - Which attributes are always present in an img element?

src and alt

## Q13 - Which attribute is always present for an anchor tag?

href
