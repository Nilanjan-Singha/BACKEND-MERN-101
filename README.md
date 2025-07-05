## BACKEND WITH MERN AND PERN 101 

Hey everyone. I have been learning backend for some time now and being a writing enthusiast, I have thought of writing some shit ( consider it notes) for myself and anybody else viewing this repo. I will write 
in anything I find useful while learning or building projects to keep track of all things. So, that's it. Let's begin. But one last thing, that for now all of learnings will be jumpled up, like there will be no proper A-Z kinda
learning steep. I will write in anything and at last, I will build a proper series to teach you all. So let;s get started. 

### NODEMON 

Ok, started writing some NODEJS and EXPRESSJS code in your code editor. And are you running the code in the terminal using " node filename.js " every damn time. That is where nodemon comes in. Nodemon is a utility tool 
for your NodeJS development that automatically monitors your JS code and restarts the server if it detects changes in your code. Pretty handy. To install or use nodemon, you will need to get it from npm. Just type 
" npm install -g nodemon". Here -g stands for global. If you donot use -g, you will need to set the path for the nodemon package and then the errors in your terminal will go away. 

### How does Nodemon work ?
 - Nodemon watches the directory or files you specify and listens for changes such as file edits, additions, or deletions.
 - When a change is detected, Nodemon automatically restarts the Node.js process, reflecting the latest code without manual intervention.

Remember, the auto reloading and rendering after saving the files in react, the vite toolkit made it possible. Somewhat of a similar concept but there are critical differences though. Nodemon restarts the whole damn server 
if some changes are made, meaning memory states are lost. But Vite uses the concept of " hot reloading ", which means to reload and render only the updated shit, thus keeping the application states intact. 

> To use hot reloading concept in NODEJS, we gotta learn BUN.


