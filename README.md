# Authentication-Secrets
Basically It is a dog selling website.

HTML5 and CSS3: Semantic Elements, CSS Grid, Flexbox
- JavaScript: ES6+, Array Functions, Rendering System
- Node & Express: Web API, Body Parser, File Upload
- MongoDB: Mongoose
- Development: Git, Github,
- Deployment: Heroku
I have use oath for add authentication in init.

There are basically 
1.login page
   if user has account in it then they can directly login to home page of tindog
   else he/she has to regiter himself.
2.register page
  user can register through google or by manually providing email and password.

  Here,i have used backend to store the credentials of user at the server side.


  Run Backend
```
$ npm install
$ npm run build
$ npm start

and i have post the page on localhost 3000 for locl repo

3. tindog page
   user directly move to tindog page after above steps
   Here i hacve provided the 2 functionallity in navbar(logout or contact).
   if you click on logout then you will reach at home route i.e. login page.
4.contact page
   If you click on contact page then a new page will open that ask for some information of user like NAME,ADDRESS,PHONE NUMBER AND EMAIL.
   that it will store in the database and ypu will reach the tindog page.

 Install VSCode Extension
    1. JavaScript (ES6) code snippets
    2. Prettier - Code formatter
    3. HTML&LESS grammar injections

Load Products From Backend
   1. edit HomeScreen.js
   2. make render async
   3. fetch products from '/api/products' in render()
   4. make router() async and call await HomeScreen.render()
   5. use cors on backend
   6. check the result

For new repo
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/adils0123/tindogWithAuth.git
git push -u origin main

FOR OLD REPO
git remote add origin https://github.com/adils0123/tindogWithAuth.git
git branch -M main
git push -u origin main
