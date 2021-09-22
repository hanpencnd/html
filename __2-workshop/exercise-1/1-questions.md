# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [False] `<div><span>hello</div></span>`

b) [False]

```html
<ul>
<li>one</li>
</ol>
```

c) [False] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

Answer: It's for accessibility. Individuals with disabilities should also have a convenient means to access websites. Screenreader play an important role for the blind in reading out the contents of the web, labels, instructions, as well as correct pronunciation of words in a language that the HTML is set in. This much facilitates web navigation.
(Source: "https://accessibility.digital.gov/front-end/screen-reader/")

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

Answer: <img>, <h1> to <h6> if needed, <p> for text and perhaps <a> on the image to link to its location in google map.

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

Answer: <ul> and <li> for the list, <a href=".."> to link to their websites.

c) You want to sell designer hats. You need to receive orders from the user.

Answer: <form> and <input> tags so that the user order info gets submitted for you to handle

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

Answer: No, since a button's descendant cannot be a clickable element.

## Q5 - What is the most generic tag you can use?

Answer: <div>

## Q6 - What do the following achronyms stand for?

a) `a`: anchor tag

b) `ol`: ordered list

c) `ul`: unordered list

d) `li`: list item

e) `tr`: table row

f) `th`: table head

g) `td`: table cell(data)

## Q7 - Usually, `td` elements are children of what kind of elements?

Answer: <td> elements are children of <tr> element.

## Q8 - What is the difference between td and th?

Answer: <th> is for the header of table whereas <td> is for the actual table data.

## Q9 - Which tag makes the text appear bigger: h1 or h3?

Answer: <h1> tag text is bigger than <h3> text.

## Q10 - In which situation can you use self closing tags?

Answer: When there is no child to the element such as <img> tag.

## Q11 - What is autofilling and why is it important?

Answer: Autofiling automatically fills input values. When there are a lot of values to fill in, it's convenient.

## Q12 - Which attributes are always present in an img element?

Answer: "src" attr should always be present indicating the source of the image. "alt" attr also should be present for accessibility in case the image doesn't load up.

## Q13 - Which attribute is always present for an anchor tag?

Answer: "href" attr is always present indicating a link to the anchor
