# ft_transcendence

This repository houses our ongoing collaboration on the ft_transcendence project, the final project of the Common Core curriculum at 42School.

## Description

The ft_transcendence project is a multiplayer online gaming platform inspired by the classic game Pong. Our goal is to build a fully functional and visually appealing web app that allows users to engage in thrilling Pong matches with a twist. The project is divided into different components.

### Frontend

The frontend of our web app is made by Davide Delladio (github Stenterello), a friend and collegue of 42 international school, and it is developed using the Svelte framework. It's responsible for providing a seamless user interface and an immersive gaming experience. We are dedicated to designing an intuitive frontend that aligns with our Kill Bill-themed aesthetic. Users will have the opportunity to choose avatars inspired by iconic characters from Quentin Tarantino's movies, and they will receive achievements based on the remarkable feats of the protagonist, "The Bride".

### Backend and Database

The backend of our web app has been my main focus. Using the NestJS framework, I've build the server-side logic that enables communication between the frontend and the database. The backend handles matchmaking, real-time game updates, and player interactions, ensuring a smooth and enjoyable gaming experience.
I developed the authentication, giving the users the ability to enable the two factory authentication (using google authenticator), and the registration logic. All the communications between the server and the clients are done throught custom API. When real-time response is needed, I've used the websocket communication protocol. Everything run smooth and without delay, and we believe we did a good job in keeping everything simple and smooth.

We are utilizing a PostgreSQL database to store user information, game data, and achievements. The database will play a vital role in maintaining the integrity and persistence of our web app.
