# Nodejs
Nodejs is an environment to run javascript outside the browser. It is built on Chrome's V8 Js engine 

## Installing Nodejs
Just go to google, type nodejs installation, continue and agree to all the steps. Make sure your environment variables are declared.

## Repl CLI
We can run javascriptby typing node in our terminal, if we have a greater than symbol then, we are in REPL cli.
But for complex projects we need something more, so we go IDE like vs code and run our projects from there.

## In VScode
make an app.js or any .js file in VS code , write a small logical code in there. Run it with node app.js after taking terminal to that path.
We can use Vscode terminal which will save the sstep of taking cmd into the path and also sits closer while running.

## Globals
We don't have window or any DOM structire that let's us access elements. We rather have some Global variables.
![image](https://github.com/NishitaErvantikar9/Nodejs/assets/120945994/8344cd16-99ec-4489-9634-539fbb42f68f)
SetInterval , setTimer etc are available javascript functions too.

![image](https://github.com/NishitaErvantikar9/Nodejs/assets/120945994/2f9fd2d2-0367-4e78-af3f-4d9ff2b84326)

## Modules
NodeJs uses CommonjS library  which basically makes every Js file into a module.
importing => use require function

       const data = require("./data.js")
       
exporting => set module.exports with everything you wanna share with others. 

       module.exports={john, nish}
       
every module object has a key called expoerts. 
we are updating the value of the key or adding more objects to that key when we write 

        module.exports.items = ["item1", "item2"]
![image](https://github.com/NishitaErvantikar9/Nodejs/assets/120945994/20ea6ad7-f0fe-423b-a482-5be5c7d887c6)


