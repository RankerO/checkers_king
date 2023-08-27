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

### home page light theme

![home page light theme](https://drive.google.com/file/d/1tke8TXeiDNS_s_CQkFvWltgzFhtFMpUz)

### home page dark

![home page dark theme](https://drive.google.com/file/d/1WFVY86uwbcvTD8_f_oblCemGs7ID7Vo1)

### game creation options

![game create options](https://drive.google.com/file/d/1Q93Acj7roCd3jikDuaV0BxA71WSUT-n5)

### profile section

![profile](https://drive.google.com/file/d/1TmSXLCPQukJHDUdhQWJ9VZQZB_5Ybqa3)

### previous matches

![matches](https://drive.google.com/file/d/1c9jV3nk-_31ZylK5xQHzVPbbU0KzC39o)

### match replay

![replay](https://drive.google.com/file/d/1PerV3YNnfSdVKHZoLr-wLj4eC3nbO5Bz)

### gameplay

![gameboard](https://drive.google.com/file/d/18HMfgQFBI-Kvb9OOXh82GI9hbzlCfC7T)

### friend request

![friend request modal](https://drive.google.com/file/d/1t0tIwd6Hhjp5voqREIq4RwppTReFmA2n)

### draw modal

![draw modal](https://drive.google.com/file/d/1zlVoPyiZI027J2Hv61XIKkmCsLRV7InC)

### online friends list

![online friends list](https://drive.google.com/file/d/129R61FWFl48A-81mtE_xYHb2GkJO-73N)

## contributors

this is a team project made under the annual event **HACK_36** of MNNIT Allahabad.

# TEAM `HACKER_OR_WHAT`

[Ankit Pandey](https://github.com/RankerO/)

[Ayush Singh](https://github.com/)

[Shiv Kumar Gond](https://github.com/)

## License

[MIT](https://choosealicense.com/licenses/mit/)
