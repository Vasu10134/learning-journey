## What is React?
- React is a **JavaScript library** used to build **Single Page Applications (SPA)**
- It uses **JSX** to combine JavaScript and HTML
- No full-page reload during navigation
- Most development happens inside the `src` folder

## Components
- A **component** is a small, reusable block of UI
- Helps break the website into manageable pieces
- Components return **JSX**

```bash
function Header() {
  return <h1>Hello</h1>;
}
```

## Props
properties sent from parent to child  
Used to pass data between components  
Props control what a component displays  

```bash
function Welcome(props) {
  return <h2>Welcome, {props.name}!</h2>;
}
```
  
## React Router DOM
Used for navigation in React apps  
Helps switch between pages without page reload  
Enables smooth transitions in SPAs  
  
✅ Check Node.js Setup
```bash
node --version
npm --version
npx --version
```
  
## JSX (JavaScript + HTML)
JSX lets you write HTML inside JavaScript  
All elements must be wrapped in one parent tag  
  
```bash
return (
  <>
    <h1>Title</h1>
    <p>Subtitle</p>
  </>
);
```
  
## React Folder Structure
src/ → Main app code lives here  
public/ → Static files like images, icons, favicon  
index.js → Entry point of the app  
package.json → Project dependencies and scripts  
  
## Bootstrap with React
Bootstrap is a CSS framework  
Use React-Bootstrap to integrate easily with React  
npm install react-bootstrap bootstrap  
  
import 'bootstrap/dist/css/bootstrap.min.css';  
📥 Import Types in React  
✅ Default Import  
  
import Header from "./Header";  
✅ Named Import  
  
import { useState } from "react";  
🔁 Using .map() in React  
  
```bash
const names = ["A", "B", "C"];
names.map((n) => <p>{n}</p>);
```
  
.map() is used to loop through arrays and return elements  
  
## React Hooks
Importing hooks:  
```bash
import React, { useState, useEffect } from "react";
```
  
## Common Built-in Hooks
useState – for managing local state  
useEffect – for side effects like fetching data  
useContext – for accessing global state  
useCallback – for memoizing functions  
useReducer – for complex state logic  
  
## Conditional Rendering
Use conditions to decide what to show:  
    
// if-else with ternary  
```bash
{isLoggedIn ? <p>Welcome</p> : <p>Please log in</p>}
```
  
// with &&  
```bash
{count > 0 && <p>You have notifications</p>}
```
