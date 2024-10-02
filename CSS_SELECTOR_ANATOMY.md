# A Complete Guide to CSS Selectors

> CSS selectors are a mechanism that selects a unique set of elements and applies CSS designs to them. This can be achieved using generic HTML properties or manually attaching an identifier to the elements while coding them.

A web page is an organized arrangement of many individual elements. Most of these elements incorporate similar characteristics to maintain a planned design and a consistent palette on the software application. We can either repeat all that code for each element or apply a selecting logic that automatically grabs selected elements and performs actions on them.

However, the requirements for different CSS rules are different, and therefore, selectors should be efficient enough to cater to all these developers’ needs. CSS selectors are a great way to refine and concise your code and save much of your valuable time.

## TABLE OF CONTENTS

- What are CSS Selectors
- Types of CSS Selectors

## What are CSS Selectors?

CSS selectors help **target the elements on a web page to apply CSS stylings**. They are required to eliminate repetitive styling and enjoy greater control over defined HTML elements.

**_For example_**, let’s consider a simple scenario where a web application has 100 elements on the page that display information in textual form. In the initial coding phase, the developer can write all the styling code inline to each element.

But what if a requirement changes to increase the font size one point larger in the future? Making a small change a hundred times is not feasible when the web applications are so complex already.

_CSS_ selectors provide various mechanisms to handle the selection procedure. This may include targeting _HTML_ elements directly or working with one or more identifiers to refine the selection. For instance, if there are three < p > elements on a page, we can target two of them using the same ID as follows:

```HTML
<p id =”changeMe”>I need change. </p>
<p> I don’t need change. </p>
<p id =”changeMe”>I need change as well. </p>
```

_Selectors_ are part of the CSS rule structure and are written at the beginning of the rule:
![Explaining selectors syntax](https://www.lambdatest.com/blog/wp-content/uploads/2023/10/my-css-rule-class-1-1.png)

## Types of CSS Selectors

CSS selectors can be applied differently to target elements. Having knowledge about them will help in choosing the best selector according to the requirement and designing the code concisely.

1. Type selector: Targets the HTML element directly.

```CSS
p {
// CSS styling
}
```

2. ID selector: Targets the ID element directly.

```CSS
#uniqueID {
 // CSS styling
}
```

For the full article please visit
[lambdatest](https://www.lambdatest.com/blog/css-selectors/#:~:text=CSS%20selectors%20are%20a%20mechanism,arrangement%20of%20many%20individual%20elements.)
