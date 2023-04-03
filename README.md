# natours

**natours** is a sample page written with plain html and sass (from udemy advanced-css-and-sass Jonas Schmedtmann course).

Check it out at https://johncol.github.io/css-course-natours/

## development environment

To install packages, in a command line run

    npm install

Then run

    npm run start

Which will trigger a compile sass task and a live-reload server at port 8080.

Now you can write your sass rules, and it will automatically write the correspondig css and reload the browser tab to see the latest changes.

## production bundle

Run 

    npm run build:css

This will compile your sass code, concatenate it with the font styles file, auto-prefix it and minify it.
