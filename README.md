# Frontend Mentor - Todo app solution

This is a solution to the [Todo app challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/todo-app-Su1_KokOW). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Add new todos to the list
- Mark todos as complete
- Delete todos from the list
- Filter by all/active/complete todos
- Clear all completed todos
- Toggle light and dark mode
- **Bonus**: Drag and drop to reorder items on the list

### Links

- Solution URL: [Repo](https://github.com/naura1835/todo)
- Live Site URL: [Todo website](https://naura1835.github.io/todo/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- JavaScript

### What I learned

This was a fun experience creating a CRUD app, in doing so i learned how to use localstorage, using `getItem()` and `setItem()`. I also learned how to use drag event for the drag and drop to reorder feature

See below:

```js
//localstorage

localStorage.setItem("todos", JSON.stringify(lists));

localStorage.setItem("todos", JSON.stringify(lists));
```

```js
...
const draggables = list.querySelectorAll(".draggable");
  draggables.forEach((item) => {
    item.addEventListener("dragstart", dragStart);
    item.addEventListener("dragend", dragEnd);
  });
  list.addEventListener("dragover", dragOver);
```

### Continued development

I want to explore z-index more cause this project has taught me it is not as simple as i thought it was. And also exploring more ways to create linear gradient borders.

### Useful resources

- [How To Build Sortable Drag & Drop With Vanilla Javascript](https://www.youtube.com/watch?v=jfYWwQrtzzY&t=1177s) - This video by webDevSimplified help me with the drag and drop to reorder.

## Author

- Website - [Khadija Gwarzo](https://www.khadijagwarzo.com)
- Frontend Mentor - [@naura1835](https://www.frontendmentor.io/profile/naura1835)
- Twitter - [@NauraCodes](https://twitter.com/NauraCodes)
