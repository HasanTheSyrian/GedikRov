# Gedik Rov 

### A repository for one of Gedik Univeristy's robotics teams' website. 
 
 ---
 
 #### Installation process:
 
 1- Make sure you have [Node.js](https://nodejs.org/en/) installed.

 2- If you're using VSCode, make sure to download: [Live Server Extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) and [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=glenn2223.live-sass).

 3- Open the directory in your terminal and run:

 ```
 $ npm install
 ```

 4- To build and watch for changes run:

 ```
 $ npm run build
 ```

 5- To make sure everything works, click on "Watch Sass" and "Go Live" in the bottom right if you're on VSCode (do the equivalent if you're not).
 Then, go to `./index.html` and try removing one of the Tailwind classes `<... class="underline" ...>`. If the website changes it means TailwindCSS works. 
 
 Next, go to `./Project/Styling/index.scss` and make some changes, if the site changes that means SCSS works. Remember to ALWAYS run `npm run build` everytime you want to change anything in the `./Project/Styling/` folder.

