## A quick intro to my webapp 
Hello Everyone! Welcome to my phase 1 project :) 

I honestly can’t believe how far I have come and finally made it to the end of phase 1. 

For this project, I will be combining my love for two things, Pokemon and JavaScript. I have built a Pokemon Team Builder App that displays a pokedex for the original 151 pokemon using vanilla HTML, CSS, and JavaScript. The users are capable of viewing each pokemon’s information and adding the pokemon they want to their team. 

### My Thought Process
I started this project with the basic concept of -  `I have a list of pokemon, and I want to display each of them in an individual card.` So right away, I knew I needed to create a container that would be able to hold a list of information from the data. 

I didn’t want to create something that would be too simple like a plain search bar that filters through the list of pokemons. I wanted to create something more interactive that contains features that would allow users to manipulate with each individual card. Instead of over thinking on what I need to do, let me just start on the build and see how it goes. 

## Fetch Pokemon Data Using the PokeAPI
The first thing I did to start my project is to use `.fetch ()` requests to obtain the data from the [PokeAPI](https://pokeapi.co/). There is a lot of information in the API that I didn’t really need. It was a struggle trying to understand what exactly I am fetching. I used `.to_json` method to grab the values from the data. It took me a good amount of time to fully understand what data is coming back and how to retrieve the specific information that I need. 

[pic]

Once I got everything that I needed, that was when I began to plan my next step on how to display all this information under a container. 

## Display Data
Let me warn you. I did not anticipate the amount of elements needed to be created under a single container. Each pokemon contains information that includes their `name, id, type, height, and weight.` And each of these information are created with their own `div` under its own unique `id`. 
That is not all! There are other elements created to help display the features that I'm trying to implement. I created various buttons, headers, and containers to make the pokemon cards more interesting. Believe me when I say I’ve spent **HOURS** creating elements before I even got the chance to write a simple function. 
[pic] 

Remember I said I wanted the pokemon cards to be interactive. Well, I created an `add` and `remove` button that allows the user to select and remove the pokemon they want. I thought what better way for the user to interact with each card than actually physically select the card they want. I thought by allowing the user to choose the pokemon they like, it allows them to actually review the information on the card. And by adding the pokemon to their team, it lets them keep track of the information they have chosen and be more familiar with the content on the list. I went beyond my knowledge trying to make my WebApp “fun”. I created a drop down option to reveal more information on the pokemon so the user can have more activity to do as they go down the list. 
[pic]

At the end of the day, I think my hard work was well worth it :)

## What I Made This Experience Enjoyable 
I really had fun doing the styling and coming up with different designs for the layout of my WebApp. I have terrible OCD, so I have to make sure everything fits to my liking. I spent several hours googling and looking up different CSS methods that I can incorporate into my project. 

[pic]

One thing that I am definitely proud of in my design is incorporating the bounce animation when I hover over a pokemon card.  

## Features that will be added in the future 
One thing I would definitely add to this project is a search bar. I think it would definitely improve the user experience in this project. Where the user won’t have to constantly scroll up and down on the webpage but instead they are able to search and filter out the information they want. 

## Dream Team!
There is nothing more fun than getting to build an application about Pokemon. It is pretty satisfying to see the final product and get to build a team of your own. 

### Here is mine Gen 1 team: 
![Dream Team](/Users/jefflin/Development/code/Flatiron-Blogs/Image/Dream_Team.jpg)

