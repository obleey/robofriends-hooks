
## # RoboFriends-hooks
A simple React App, that filters through fetched data with a search bar and displays it on Card components. This implementation was made using React hooks and functional components. 
![Robofriends](https://i.imgur.com/goWtZ03.png)
[Demo](https://obleey.github.io/robofriends/)

## How I worked on this project  

This is a upgrade of my previous [Robofriends](https://github.com/obleey/robofriends) App
- The goal here was to refactor my original Robofriends app to using hooks and functional components
## How to navigate this project  
- The `src`folder contains two separate folders, one is `components`, which stores all the reusable components of the appliaction and `containers` which stores the page layout.
- The project uses [Tachyons CSS toolkit](https://tachyons.io/) for styling: [Card component example](https://github.com/obleey/robofriends-hooks/blob/main/src/Components/Card.js)
- The application fetches data from the [JSON placeholder](https://jsonplaceholder.typicode.com/users) for data and [RoboHash](https://robohash.org/) for images, then stores it into state. From there on, we wok with the stored data via useEffect and useState for the searchbar component,  which filters the data from user input: [Code here](https://github.com/obleey/robofriends-hooks/blob/main/src/Containers/App.js)

## Why I built the project this way  
- A upgrade of my existing [Robofriends](https://github.com/obleey/robofriends) App
- I used hooks and functional components here on purpose, since i wanted to learn it.
- Tachyons is a good library for fast styling.  
- My plan is to become a full-stack developer eventually. But for the beginning I focus on the  
frontend. That's why I decided to use an existing API rather to create a custom server. I have  
basic backend knowledge as well.  

## If I had more time I would change this  
- Write all tests using Jest
- Since I realized that more and more projects don't use Redux anymore, i would implement GraphQL or  
react-query for data managment.
 
## Available Scripts  
First of all clone or fork this repo and install all the needed dependencies using `npm` or `yarn`

**Dev build:**

run  `nmp start`

**Prod build:**

run  `nmp run deploy`

## Authors
[Miha Oblišar - @mihaoblisar](www.linkedin.com/in/miha-obli%C5%A1ar-8b177610a)

## Licence
This project is open-sourced under the [MIT license](https://opensource.org/licenses/MIT).

