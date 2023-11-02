## Framendavefþróun 
Þar sem við smíðum notendaviðmót fyrir vefinn með JavaScript, CSS og HTML. [Handbók](https://frontendmasters.com/books/front-end-handbook/2019/) um framendavefþróun.



### Vefhönnun 
* [Awwards](https://www.awwwards.com/) _vefsíður með áherslu á hönnun_
* [Material Design](https://material.io/)
* [Design resources for developers](https://github.com/bradtraversy/design-resources-for-developers)
* [Laws of UX](https://lawsofux.com/)
* [UX Project Checklist](https://uxchecklist.github.io/)

---

### CSS 
* [Top 20 Best CSS Frameworks for Front-End Developers in 2023](https://hackr.io/blog/best-css-frameworks)
* [How to Organize Your CSS with a Modular Architecture
(OOCSS, BEM, SMACSS)](https://snipcart.com/blog/organize-css-modular-architecture)
* [Tailwindcss](https://tailwindcss.com/)
   * [Get started with Tailwind CSS](https://tailwindcss.com/docs/installation)
   * [Utility-First Fundamentals](https://tailwindcss.com/docs/utility-first)
   * [Tailwind CSS tutorial](https://tsh.io/blog/tailwind-css-tutorial/)



---

### JavaScript
- [The Most Popular JavaScript Frameworks in 2023](https://theme-selection.medium.com/the-most-popular-javascript-frameworks-in-2021-a2fe62174df6)
- [Typescript](https://www.typescriptlang.org/)- [React](https://react.dev/)
- [Learn React (Scrimba)](https://scrimba.com/learn/learnreact)
- [React (vefforritun II, HÍ)](https://github.com/vefforritun/vef2-2023/tree/main/namsefni/17.react#readme)
- [React (Vefskólinn, Tækniskólinn)](https://io.vefskoli.is/guides)


> [Deep Dive Into Modern Web Development](https://fullstackopen.com/en/)



<!--
  - [Preact](https://preactjs.com/)
  - [Vue.js](https://v3.vuejs.org/) (Version 3)
  - [Svelte](https://svelte.dev/) tiny framework.
  - [Vue Routing](https://v3.vuejs.org/guide/routing.html#official-router)
  - [Vue Router for Everyone (myndband)](https://vueschool.io/courses/vue-router-for-everyone?friend=vuejs)
-->


<!--
### Routing í JavaScript (vanilla)

- [How I Implemented my own SPA Routing System in Vanilla JS](https://medium.com/@bryanmanuele/how-i-implemented-my-own-spa-routing-system-in-vanilla-js-49942e3c4573)
- [Tiny Express-inspired client-side router](https://github.com/visionmedia/page.js)



- Template: [Build a state management system (pub/sub) with vanilla JavaScript](https://css-tricks.com/build-a-state-management-system-with-vanilla-javascript/)
- [Web Components, (Templates)](https://medium.com/javascript-in-plain-english/web-components-crash-course-b0a2feb11be1)
-->

<!--

## Template engines
- [Create Frontend framework](https://mfrachet.github.io/create-frontend-framework/intro.html)
- [Web Components Crash Course (Templates)](https://medium.com/javascript-in-plain-english/web-components-crash-course-b0a2feb11be1)



---

## [Tagged templates](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals#Taggedtemplates)

Tags allow you to parse template literals with a function. 

1.  make a function
1.  put the name of function in front of the string you want to run against.

```JavaScript
/* The first argument of a tag function contains an array of string values. The remaining arguments are related to the expressions. 
The tag function can then perform whatever operations on these arguments you wish, ex. return the manipulated string.
*/
const div = (strings, ...args) =>
  strings.reduce(
    (acc, currentString, index) => acc + currentString + (args[index] || ""),
    ""
  );

const firstName = "Marvin";
const lastName = "Frachet";

const template = div`Hello ${firstName} ${lastName} !`;
console.log(template); // prints `Hello Marvin Frachet !`
```

Tagged templates allow developers to create a domain specific language (DSL) that let users only have to worry about writing a string while the library authors deal with the rest


---

## [&lt;template&gt;](https://javascript.info/template-element) 

&lt;template&gt; allows you to keep content that’s not rendered but will be used in JavaScript later on.

A built-in &lt;template&gt; element serves as a storage for HTML markup templates. The browser ignores it contents, only checks for syntax validity, but we can access and use it in JavaScript, to create other elements.

Í index.html skrá:

```html
<body>

<template id="tmpl">
    <div class="message">Hello, world!</div>
 </template>    

</body>
```

Í app.js skrá:

```JavaScript
  // create fragment to hold template
  const fragment = document.createDocumentFragment();
  // Clone the template content to reuse it.
  fragment.append(tmpl.content.cloneNode(true));
  // render tempkate to html
  document.body.append(fragment);
```

---

## JavaScript Templates söfn
- [Mustache (simple)](https://mustache.github.io/)
- [Handlebars (complex)](https://handlebarsjs.com/)

---
-->
