_________________________________________________________________________

Startup installation:
_________________________________________________________________________

Type as following in terminal:

- "npm create vite@latest"
    - "./" ( Ignore files and continue )
    - Choose "React"
    - Choose "JavaScript"

- "npm install sass react-router-dom react-icons" (Add Libraries)

_________________________________________________________________________

What to change?
_________________________________________________________________________


- Delete index.css
    - Remove import in main.jsx

- Clean up App.jsx
    - Remove "count" UseState
    - Empty the return so it's just "return (<></>)"
    - Remove all imports except App.css
    - Rename App.css to App.scss

- Change title in index.html

- Remove react.svg from assets folder

_________________________________________________________________________

- When running the application, type "npm run dev" in terminal