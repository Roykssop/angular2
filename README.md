# angular2

Install node js 
  curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
  apt-get install nodejs
  
Install angular 2
  npm install -g angular-cli
  
Create a new folder to keep your projects
  mkdir a2proyects
  
Generate new project
  ng new first-app
  
Components
  Are the key piece of a2
  
Generate new component
  ng generate component firstcomp
  
  -Shortcut
  ng g c firstcomp -is -it (inline styles, inline template)
  -Tip
  Every time you add a new component you need to be sure to import it in app.module metadata , more specificly in "declarations"
  

