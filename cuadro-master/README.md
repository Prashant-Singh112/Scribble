
# Cuadro

A Cross Platform - Web, Android & iOS App multiplayer doodling & guessing game.


## Tech Stack

**Client:** Flutter, socket_io_client

**Server:** Node, Express, Socket.io, Mongoose

  
## Features

- Creating Room
- Joining Room
- Waiting Lobby
- Doodling Features (Everyone In Room Can see)
    - Changing Width of Pen
    - Changing Colour of Pen
    - Clearing off the Screen
    - Drawing
- Generating Random Words
- Chatting In Room
- Identifying Correct Words
- Switching Turns
- Changing Rounds
- Calculating Score
- LeaderBoard
  
## Environment Variables

- To run this project, you will need to add the following environment variables to your .env file

- `MONGODB_URL`: `Your MongoDB URI Generated from MongoDB Atlas`

- Make sure to replace <yourip> in `lib/screens/paint_screen.dart` with your IP address.

  
## Run Locally

- Clone the project


     - git clone https://github.com/PrashantSingh112/cuadro


- Go to the project directory

     - cd cuadro


- Install dependencies (Client Side)

     - flutter pub get


- Install dependencies (Server Side)

- cd server && npm install


- Start the server

    - npm run dev
