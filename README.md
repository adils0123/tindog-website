# Authentication-Secrets
Basically It is a dog selling website.

HTML5 and CSS3: Semantic Elements, CSS Grid, Flexbox
- JavaScript: ES6+, Array Functions, Rendering System
- Node & Express: Web API, Body Parser, File Upload
- MongoDB: Mongoose
- Development: Git, Github,
- Deployment: Heroku
I have use oath for add authentication in init.
![Screenshot (130)](https://user-images.githubusercontent.com/87599586/200961010-ebf969f2-8ca5-4f5e-9fa6-cce5aa935080.png)
![Screenshot (129)](https://user-images.githubusercontent.com/87599586/200961017-73511e1d-16a8-4ec8-ba74-da247efbefe4.png)
![Screenshot (128)](https://user-images.githubusercontent.com/87599586/200961018-6a9d54d6-e037-45eb-990f-3e425ea4fc15.png)
![Screenshot (127)](https://user-images.githubusercontent.com/87599586/200961021-a8d135ed-0068-4386-be9a-059646f92f33.png)
![Screenshot (126)](https://user-images.githubusercontent.com/87599586/200961022-d29e6c3a-9ac7-4879-9165-95072b2cff43.png)
![Screenshot (125)](https://user-images.githubusercontent.com/87599586/200961026-29eb7002-d97b-4899-ab8d-a4a1f006eb4e.png)
![Screenshot (124)](https://user-images.githubusercontent.com/87599586/200961029-ba8fcd45-8247-4eba-b54d-7b11a701d1d3.png)
![Screenshot (123)](https://user-images.githubusercontent.com/87599586/200961034-37163771-2e1c-41b7-8f2a-dd0620c8b4df.png)
![Screenshot (122)](https://user-images.githubusercontent.com/87599586/200961036-f19af6c2-cc7b-452d-b1ba-3aaa3122d2dd.png)
![Screenshot (121)](https://user-images.githubusercontent.com/87599586/200961038-af0efbfb-6b1d-4f81-923d-c0be7582656e.png)
![Screenshot (120)](https://user-images.githubusercontent.com/87599586/200961040-93971477-6339-40d6-b45c-5473b1a92d2c.png)
![Screenshot (119)](https://user-images.githubusercontent.com/87599586/200961042-19344f52-3891-4b21-b0a1-28fdf0f3e83d.png)
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
