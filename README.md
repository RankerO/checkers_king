![homepage](https://drive.google.com/uc?export=view&id=1VPf18ntL3SL5NUkAfre3Kc1jH8Zf_rSw)

# checkers king

checkers king is an online checkers playing platform where you can play checker game with your friend, random players as well as bot

## Installation

the project has two components

- frontend, made in reactjs
- backend in nodejs

```bash
git clone https://github.com/RankerO/checkers_king.git
```

```bash
cd checkers_king
```

## setting up frontend

```bash
#currently inside the checkers_king folder
cd client
npm i
```

run `npm start` and frontend will start

## setting up backend

```bash
#currently inside the checkers_king folder
cd server
npm i
touch .env
#above command will create a env file , put the necessary keys in there
```

backend setup done, now hit the most favourite command `npm start`

##### for better understatnding of project see [socket documentation](/server/src/socket/Documentation.md) and [API documentation](/server/README.md)

## Features :-

### Basic

- [x] login/signup
- [x] implement two player game play as per rules
- [x] mandatory move / non-mandatory move
- [x] propose draw / accept draw
- [x] send invite link to play with others
- [x] store previous matches played by user
- [x] play as guest with random online players
- [x] easy-level bot
- [x] background music, moves & animations
- [x] chat system
- [x] **live video feed while playing**

### Advanced

- [x] login with google, facebook each platform
- [x] implement a rating system (eg. ELO rating etc)
- [x] for logged-in users. play with random online players with matching ratings
- [x] provision of league
- [x] medium-level-bot
- [x] dark mode
- [x] site tour
- [x] **run simulation of a recorded game with play/pause functionality**

### Additional Features

- [x] make friends (send and receive request)
- [x] **spectator mode** , you can invite someone to watch you game
- [x] see online friends status and send invites/watch their game
- [x] graph in user profile
- [x] possible moves prediction to player
- [x] handled corner cases like multiple device detection and trying to play multiple games
- [x] emoji support in chat
- [x] user search with autosuggest

### images

### Home page light theme
![1](https://github.com/RankerO/checkers_king/assets/91595780/bbeaa2fc-f8df-408a-8ed0-9deccb5f3d69)

### home page dark
![2](https://github.com/RankerO/checkers_king/assets/91595780/921da1cc-7c13-411f-b338-a82c9f01b97c)

### Game creation options

![3](https://github.com/RankerO/checkers_king/assets/91595780/db43fdd1-d8ae-4e51-866b-07d903f1674e)

### profile section

![4](https://github.com/RankerO/checkers_king/assets/91595780/812d0b20-ac14-49d5-83d3-38695606ada3)

### previous matches

![5](https://github.com/RankerO/checkers_king/assets/91595780/38162ecb-acca-4153-b215-abd90b5c1019)

### match replay

![6](https://github.com/RankerO/checkers_king/assets/91595780/da05f00c-0dfc-42bc-a82d-f77c239a50c2)

### gameplay

![7](https://github.com/RankerO/checkers_king/assets/91595780/fac67213-70d8-4004-a9ae-90e53b2ac038)

### friend request

![8](https://github.com/RankerO/checkers_king/assets/91595780/a52dbf3a-e0e1-4cf7-b9ee-33b8ff8e8795)

### draw modal

![9](https://github.com/RankerO/checkers_king/assets/91595780/9a047b8e-1351-4fd8-ace2-ed6180d7cf6e)

### online friends list

![10](https://github.com/RankerO/checkers_king/assets/91595780/99c5b693-adba-4b4d-9fc2-8ec49893358e)
## contributors

this is a team project made under the annual event **HACK_36** of MNNIT Allahabad.

# TEAM `HACKER_OR_WHAT`

[Ankit Pandey](https://github.com/RankerO/)

[Ayush Singh](https://github.com/)

[Shiv Kumar Gond](https://github.com/)

## License

[MIT](https://choosealicense.com/licenses/mit/)
