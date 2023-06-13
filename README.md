# Wetube Reloaded
--

--

## index

- [folder tree](#folder-tree)
- [start set-up](#1-set-up)
- [first : Routers & Controllers](#2-router)

### folder-tree

## To do

### 1. Set up

1. Install NodeJS.

2. Install Express : minimalist web framework for Node.js.

3. Learned about Dependencies in 'package.json'

4. Install Babel(core, node, preset-env) : puts a soft cushion between a web application and the many cool new file formats.

5. Nodemon : automatically restarting the node application when file changes in the directory are detected.

### 2. Router

1. Used express

2. Created a list of routers    
    
   / -> Home    
   /join -> Join    
   /login -> Login    
   /search -> Search    
    
   /users/:id -> See user    
   /users/logout -> Log Out    
   /users/edit -> Edit My Profile    
   /users/remove -> Delete My Profile  

   /videos/:id -> See Video    
   /videos/:id/edit -> Edit Video    
   /videos/:id/remove -> Remove Video   
   /videos/upload -> Upload Video    
    
3. Cleaning the Code :
    
   - Divide folder (/routers, /controllers)
   - Exports & Imports ( default or not )    
         
4. Architecture    
    
   - Planning Routes : Add directory => Export & Import
   - URL Parameters : learn about ':id'  
      Declare variables inside URL

### 3. TEMPLATES

1. Returning HTML

   - Install & Configuring Pug    
   - New file 'home.pug'    
   - Write in HTML    
   - process.cwd() + '/views' default property modify.
      
2. Partials    
    
   - make folder 'partials' and partials file.    
   - include partials file.    
   - Extending Templates ( inheritance : base HTML template)
      https://pugjs.org/language/inheritance.html

   + MVP Styles

   - Template :
      a. conditionals : if, if else, else..
         https://pugjs.org/language/conditionals.html
      b. iteration : each, while.. showing list of elements 
         https://pugjs.org/language/iteration.html
      c. mixins : Mixins allow you to create reusable blocks of Pug.
         Mixin is like a partial, but is a partial that receive data.
   
### 4. Database ( MongoDB )

1. See only one video

   - change on my 'see' controller    
   - Upload & Edit video    

2. Edit video page

   - POST Method    
   - Add urlencoded(extended) in server.js !middleware-before Routers
      https://expressjs.com/ko/4x/api.html#express.urlencoded

3. Upload video page

   - Add controller & push new Video in array

4. Install Database

   - MongoDB    
   - Mongoose

5. CRUD Introduction

   - CRUD Real Html page
      Create
      Read
      Update
      Delete

   

----- finish🔺 🔰 🔻next -----    
    
   #6.10 Video Model (01:37)