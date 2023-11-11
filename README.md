# React + Vite

1.  > npm create vite@latest client
2.  choose framework - react & choose variant JS+SWC
3.  goto folder client... >npm install ... to install dependency and dev dependency
4.  install tailwind css with vite:
    > npm install -D tailwindcss postcss autoprefixer

5)  > npx tailwindcss init -p : generate tawind.config.js & vite.config.js

6)  add this to tailwind.config.js
    content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
    ],

7)  Add the Tailwind directives to your CSS
    @tailwind base;
    @tailwind components;
    @tailwind utilities;

8)  clean up: delete app.css, public/vite.svg, assets/react.svg
9)  create pages
10) npm i react-router-dom to enable routing functionality
