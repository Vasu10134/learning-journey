# Typical React Application Workflow

## index.html  
- Every app starts with a `.html` file, because the browser needs a `.html` extension to start running an application.
- That's why we have the `index.html` file in our structure.
- This `index.html` mounts **root** and tells React to go to `src/main.tsx`.

## main.tsx
- This `main.tsx` loads packages and libraries like `App.tsx` & `index.css`.
- React usually goes to `App.tsx` from `main.tsx`.  

## App.tsx
- The `App.tsx` is the root component of the app : Entry point for components & pages.  
- The main hub of your React application.
  
---

## Workflow of Application in React
<div style="background-color: #000000; color: #FFFFFF; font-family: monospace; padding: 1.5em; line-height: 1.5;">
    index.html --- starting point of application<br>
    &nbsp;&nbsp;&nbsp;&nbsp;| <br>
    &nbsp;&nbsp;&nbsp;&nbsp;| <br>
    main.tsx ------ App.tsx<br>
    &nbsp;&nbsp;&nbsp;&nbsp;| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|---- index.css<br>
    &nbsp;&nbsp;&nbsp;&nbsp;| <br>
    App.tsx ------- Main Hub (consist of pages and components)<br>
</div>
