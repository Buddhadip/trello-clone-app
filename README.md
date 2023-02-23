# Trello Clone With MERN Stack!

&nbsp;
# Purpose
My purpose of developing this project is to show what I can do both on the frontend and the backend. I would also like to point out that it is my first project as MERN stack.

&nbsp;
# Features

- Fully responsive design like Trello
- Register and Login
- Create multiple boards, select any background and add members
- Create multiple lists
- Create multiple cards
- Drag and drop lists or cards
- Change title and background of board
- Add description for board
- Change title of lists
- Add description, cover color, members, labels, start date, due date, multiple checklist and multiple attachements
- Delete boards, lists or cards
- Track all activity logs of cards and boards
- Comment on cards or boards
- Search boards or cards titles

&nbsp;
# Used Technologies

| Server Side    	| Client Side               	| Only Development 	|
|----------------	|---------------------------	|------------------	|
| expressjs      	| styled-components         	| nodemon          	|
| express-unless 	| reduxjs-toolkit           	|                  	|
| mongoose       	| react-beautiful-dnd       	|                  	|
| cors           	| material-ui                	|                  	|
| path           	| axios                     	|                  	|
| dotenv         	| date-fns                  	|                  	|
| jsonwebtoken   	| moment                    	|                  	|
| bcryptjs       	| atlaskit/css-reset        	|                  	|
|                  	| react-hook/mouse-position 	|                  	|
|                	| react-router              	|                  	|
|                	| react hooks                 	|                  	|

&nbsp;
## How to run?

- Download nodejs [here](https://nodejs.org/en/download/) 
- For database, you can use local mongodb or mongo atlas. See [here](https://www.mongodb.com/)

- Change directory:

  ```cd trello-clone-mern```

- Open second terminal same location:
    * Ubuntu: &nbsp; ```gnome-terminal```
    * Windows: &nbsp; ```start```

- Change directory of first terminal and install packages:

    ```cd server```

    ```npm install```

- Create .env file in server directory like .env.example and enter required variables

- Start the server:

    ```npm run start```

- Switch the second terminal

- Change directory of second terminal and install packages:

    ```cd client```

    ```npm install```

- Start the client:

    ```npm run start```
