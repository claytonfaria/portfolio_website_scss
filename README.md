# HTML/CSS Portfolio Website

Website built with HTML and SCSS

## How to use:

Initialize and create the package.json: 

`npm init -y`

Install SCSS/SASS compiler "node-sass": 

`npm install node-sass`

Inside package.json, make sure to add "sass" inside "scripts":

```
"scripts": {
    "sass": "node-sass -w scss/ -o dist/css --recursive"
  },
 ```

Run "node-sass" and it will compile the .scss into .css on save: 

`npm run sass`
