# React Checklist
A simple `ReactJS` todo checklist that allows you to add tasks and mark them as complete.  

## Components and Use
- `App.js` - The root component, with states such as `todoList: array` that stores the todo list items, `finished: number`, `percendDone: number`.
- `AddItemBox.js` - Input component that calls the add function of the `App` onInputEnter.
- `ItemsList.js` - The `<ul>` component that calls the `.map` function and creates a list `Item`.
- `Item.js` - The `<li>` component that stores the todo list task along with `ItemOptions`.
- `ItemOptions.js` - Div component that has delete button to remove task from the todo list.
- `TodoStats.js` - Series of `<p>` tags in the `<div>` component that displayed total tasks, completed task, and percent of completed tasks.
