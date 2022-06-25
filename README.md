### GESTIONS DE MUSIQUES AVEC PLAYLISTS ET FAVORIS 

mise en place d'un serveur node.js avec express,
  • ajout des différentes routes dans un dossier router 
  • ajout des controller dans un dossier controller
  • ajout des managers dans un dossier manager
  • possibilité aux utilisateurs de se logger
  
mise en place d'une base de données avec mysql

  • avec table de jointure
  
mise en place d'une application front avec react

  • mise en place de routes avec react router dom
  • utilisation de axios pour les requetes aux back
  • utilisations de bootstrap pour un formulaire de connexion
  • utilisations useEffect, useState, useParams ... 
  
## Setup & Use
### Available Commands

- `setup` : Initialization of frontend and backend, as well as all toolings
- `dev` : Starts both servers (frontend + backend) in one terminal
- `dev-front` : Starts the React frontend server
- `dev-back` : Starts the Express backend server
- `lint` : Runs validation tools, and refuses unclean code (will be executed on every _commit_)
- `fix` : Fixes linter errors (run it if `lint` growls on your code !)

### Tools

- _Concurrently_ : Allows for several commands to run concurrently in the same CLI
- _Husky_ : Allows to execute specific commands that trigger on _git_ events
- _Vite_ : Alternative to _Create-React-App_, packaging less tools for a more fluid experience
- _ESLint_ : "Quality of code" tool, ensures chosen rules will be enforced
- _Prettier_ : "Quality of code" tool as well, focuses on the styleguide
- _ Airbnb Standard_ : One of the most known "standards", even though it's not officially linked to ES/JS
- _Nodemon_ : Allows to restart the server everytime a .js file is udated
