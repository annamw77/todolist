# todolist react app
_The goal of this project is to re-learn React, slowly but surely_

### todos... for todolist...
* mess around with ui components and learn what state means, think about styling options
* consider adding react router for multipage views
* consider using redux for "fun" to store global vars ex. logged-in user name 
* build backend, maybe express api connecting to sql db 

### React: ...but why though?
React only puts the "V" in "MVC" - its deep purpose is to render UI. It is not a full-service MVC web framework like Django, Rails or Spring. It is a Javascript library and alone it is not able to persist data beyond a browser session. 

I am personally stoked on learning more about building resuable components. Previously, I have churned out a lot of copy-pasted and shamefully un-DRY JS views. My focus has been on backend development with less care and love given to the frontend experience.

I'd like to look deeper into how to build testable components. Testing is routinely self-identified as an "area of growth" for me and additionally I haven't written a frontend test in 1.5+ years or possibly ever. Getting a bigger picture of the best practices surrounding component design and architecture should be helpful here so testability is kept in mind from the get-go rather than as a hurried afterthought. 

### Keywords and Concepts
#### DOM
Short for "Document Object Model". The DOM takes plain HTML and visualizes it as a tree of nodes, the nodes being the hierarchical structure of the HTML tags and their contents. The entire tree is considered a single "document" and is also an object.

At the cost of mixing up the acronym a little, the **DOM** **m**odels the contents of an HTML file as a single **d**ocument of **o**bjects. This modeling allows us to access and manipulate HTML elements in an object-oriented way, generally done using Javascript.

For example, take
```html
<html>
  <h1>Welcome!</h1>
  <div id="findMe"></div>
</html>
```

The DOM allows us methods to select and change the div element
```javascript
div = document.getElementById("findMe")
div.innerText = "Here I am!"
```

Resulting in the following
```html
<html>
  <h1>Welcome!</h1>
  <div id="findMe">Here I am!</div>
</html>
```

* Virtual DOM: 
* JSX:
* Element:
* Component:
  * Component lifecycle:
* State:  
* Props: 
  * Unidirectional data flow:
