## Steps to Reproduce

This code demo shows the basics of using npm and setting up a node project. Tools like NextJS will automate a lot of these tasks but this helps you understand the what and why.

1. Create a new project folder
2. in it write `npm init -y` from the command line
3. write some js in an `index.js` file
4. run the file with `node index.js`
5. create a script in the `package.json` to run it
    - `npm run dev` from the command line
6. install a dependency like express with `npm i express`
7. hide the node_modules from git by adding to `.gitignore`
8. copy server code from express and use it in your `index.js` file [express server demo](https://expressjs.com/)
9. Try running it
10. Push code to github (make sure node_modules is greyed out)