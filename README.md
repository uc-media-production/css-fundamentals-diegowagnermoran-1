# CSS Fundamentals

The second layer of a webpage is CSS (Cascading Style Sheets). While HTML is all about semantics and foundation, CSS 
is all about _presentation_. After you markup your content, you will want to present that information to the user in 
a user friendly and aesthetically pleasing way. 

Remember, CSS loads from the **top** to **bottom**, **left** to **right**. The whole point of _cascading_ style 
sheets is that the styles cascade down. Meaning, style rules will overwrite any rules with the same selector that 
came before it. It's also important to consider the order at which the style sheets are loaded on your webpage.

Ex:

```css
p {
  margin-bottom: 1rem;
}

p {
  margin-bottom: 2rem;
}
```

If you have two style rules that adjust the `margin` of `p`, the bottom most rule will be applied. In this case, `p` 
will have a `margin-bottom` of `2rem`.



## Assignment

You are a web developer at a marketing agency. The agency that you work for has been contracted out by Nintendo to 
develop a few webpages for some of their IPs. A UI/UX designer at the agency has provided you with some wireframes 
for you to follow. Your job is to take the assets and content provided by the client (Nintendo) and follow the 
wireframes provided by the UI/UX designer.

It's important to remember that there are other people on your team that may work on this in the future. So it is 
incredibly important that your code is reusable and scalable. Be sure to separate your code with comments and use 
`class` and `id` names that make sense.

You will also be graded for everything that you have learned up to this point. Just because this is a CSS-based 
assignment, doesn't mean that HTML semantics don't matter here.

## Requirements
- Create a "homepage" following the wireframe provided (see below)
- Create 4 internal pages following the wireframe provided (see below)
- Every page must include...
  - A title, description
  - A reset stylesheet
  - A custom external stylesheet
- Your external stylesheet must have comments separating the different sections of the webpage (header, content, 
  footer, typography, etc.)

I have provided two HTML files for you to use to jump start your project. Please add to these files to follow the requirements above.

How you structure your webpages and stylesheets is up to you. Just make sure that your classes and ids make sense. Remember, classes can be reused and should be _generic_ in nature. While ids must be unique and should be 
specific to "identify" an element on a webpage.

> HINT: Be sure to complete one of the internal pages first. You can always duplicate the page, rename it, and 
> replace the content with that page.

### Wireframes

Below are some wireframes for you to reference while working on the assignment.

#### Hompage
<img width="1105" alt="Screen Shot 2022-08-15 at 10 05 40 PM" src="https://user-images.githubusercontent.com/15350920/184786038-765650c3-9778-41ac-af09-6676a9dc8e4b.png">

### Interior Page
<img width="1029" alt="Screen Shot 2022-08-17 at 10 12 54 PM" src="https://user-images.githubusercontent.com/15350920/185277785-13169b6c-d7c8-456b-9c49-48c77d8d43e9.png">
