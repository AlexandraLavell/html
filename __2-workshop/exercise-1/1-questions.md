# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?


Type true/false in the provided [ ].

a) [FALSE] `<div><span>hello</div></span>`

<div>
    <span>Hello</span>
<div>

b) [FALSE]

```html
<ul>
    <li>one</li>
</ol>
```

<ul>
    <li>one</li>
</ul>

or

<ol>
    <li>one</li>
</ol>



c) [TRUE and FALSE it works but doesn't make sense] `<ul></ul><img/><ol><li>one</li></ol>`

<ul>
    <li>
        <img src = "image"/>
    </li>
<ul>
<ol>
    <li>one</li>
</ol>





## Q2 - What is a screenreader and why should we care about them?
A screenreader is an assistive technology that reads websites aloud. It uses the tags to interpret the site.

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
The image tag is used to add photos, <img src="my photo here" />

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
The lists can be created with the ol, ul and li tags. The links with the anchor tag, a with the destination address, href.

c) You want to sell designer hats. You need to receive orders from the user.
To receive information from the user we use the form tag along with input tags.

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
A button cannot be a child of a button because it's behaviour would be unpredictable. 

## Q5 - What is the most generic tag you can use?
div

## Q6 - What do the following achronyms stand for?

a) `a` - anchor

b) `ol` - ordered list

c) `ul` - unordered list

d) `li` - list item

e) `tr` - table row

f) `th` - table head

g) `td` - table data

## Q7 - Usually, `td` elements are children of what kind of elements?
td is usually the child of a tr element

## Q8 - What is the difference between td and th?
td is a cell of a table, th is the header row of the table. It is the row of header cells of the columns.

## Q9 - Which tag makes the text appear bigger: h1 or h3?
h1

## Q10 - In which situation can you use self closing tags?
for elements that have no children

## Q11 - What is autofilling and why is it important?
autofilling is when the browser automantically fills a form. It's convenient for the user.

## Q12 - Which attributes are always present in an img element?
the image source (src) and label/title (alt)

## Q13 - Which attribute is always present for an anchor tag?
the destination address (href)
