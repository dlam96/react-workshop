# Introduction
React Workshop for Tech Knights on March 21, 2019 by Spectre (dlam96)

Link to [slides](https://docs.google.com/presentation/d/1XP2AXH_0nhHemkj7K3UXIFsotj6R8AIS_g1bPCINxvQ/edit?usp=sharing)

### Notes:

To get your API key from [Open Weather Map](https://home.openweathermap.org/), please register an account with them.

To make coding in React easier I highly recommend installing these packages in VSCode

1. Simple React Snippets by Burke Holland

2. Prettier - Code formatter by Esben Petersen

    2a. If you are using VSCode, enter the editor settings using [ctrl + ,], and type save in the search bar
    
    2b. Make sure the Editor:Format on Save tickbox is checked. This will prettify your code when you save.

# Setup:

We will be using the [create-react-app](https://github.com/facebook/create-react-app) from the guys over at Facebook

[If you are using *Windows*, download the LTS executable from [NodeJS](https://nodejs.org/en/) and then open up the NodeJS terminal and skip step 1.]

1. First check to see if you have NPM installed

`npm --version`

If not then simply install it by running

`sudo apt install nodejs npm`

2. Let's install create-react-app | -g for global

`npm install create-react-app -g`

Verify it's installed

`create-react-app --version`

3. Now we can finally create a React app!

Start by going into your Desktop directory
  
  `cd Desktop`

then type `create-react app [app name]`. Note that the braces [ ] are not included.

4. Now that we've created the app folder simply cd to it and start

`cd app name`

`npm start`
 
 While we're at it let's open up the directory in our text editor (I recommend VSCode)
 
 `code .`

5. We'll be using Bootstrap later during the workshop 

`npm install --save bootstrap`

or 

`yarn add bootstrap`

# Extra Bits and Credits:

1. More about [Async Await](https://www.valentinog.com/blog/how-async-await-in-react/)
2. Hamza Mirza - [Youtube](https://www.youtube.com/watch?v=204C9yNeOYI)
3. Read more about [React](https://www.w3schools.com/whatis/whatis_react.asp)

