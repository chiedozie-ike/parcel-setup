# parcel-setup
This repo is a structured guide to set up parcel for sass/scss and javascript

### Local setup
1. create a local repo.
2. Initialize the repo with `npm init -y`.
3. Create an `index.js` file.
4. Initialize git within the repo with `git init`.
5. Create a `.gitignore` file and add `node_modules` to it.
6. Install Sass as a dev-dependency with `npm i sass --save-dev`.
7. Install Parcel as a dev-dependency with `npm i parcel-bundler --save-dev`.
8. Create an `index.html` file. 
9. Create a `src` directory. 
10. Create a `style.scss` file within the `src` directory.
11. Create a simple html document in `index.html`.
12. Link the `style.scss` to the `index..html` file using `<link rel="stylesheet" href="./src/style.scss">`.
13. Link the `index.js` file to the `index.html` file using  `<script  src="./index.js"></script>`.
14. Modify the package.json file by adding the tasks scripts below: 
```` 
    "scripts" : {
			"dev" : "parcel index.html",
			"build" : "parcel build index.html"
		 }
````
15. Run the parcel dev server with `npm run dev`.
16. You can now make edits and parcel js would bundle your `sass` and `js` code in dev. Check my `index.html; index.js and style.scss` files to see my edits.
17. Finally, you can use `npm run build` when you are ready to push code to production.

### Remote setup
1. Create a github repo with a `.gitignore` file for node js.
2. Clone the github repo using `git clone (url)`. 
3. Edit the `.gitignore` file by commenting out the dist dir. Parcel uses the dist dir when you bundle your code.
4. Initialize the repo with `npm init`.
5. Create an `index.js` file.
6. Follow step 6 above through to step 17.
