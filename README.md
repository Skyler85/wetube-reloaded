# Wetube Reloaded
--

--

# index

- [folder tree](#folder-tree)
- [start set-up](#1-set-up)
- [first : Routers & Controllers](#2-router)

### folder-tree

## I do..

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
   - Exports & Imports  
     ( default or not )    
         
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
       
----- finish🔺 🔰 🔻next -----    
    
   #5.2 Extending Templates

