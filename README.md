
## Intro

This is an opensource blockchain prototype project that aims to solve some blockchain issues using simple methods, feel free to contribute 😊


## Folder Structure

-base-blockchain

  - base-blockchain
      - AddNet : add decentralization and fault tolerance 
      - AddPersistence : data persistence 
      - AddPoS : Proof of Stake concensus algorithm
      - Simple : First and Simple implementation (No data persistence: Data disapears after reload)

  - frontend : Reactjs frontend App

## Prerequisites

- go installed
- nodejs installed
 
## Run it

- git clone https://github.com/meanking/base-blockchain
- cd base-blockchain/frontend
- npm i
- cd base-blockchain/base-blockchain/Simple : for the first implementation
- go build
- run 
- run ./blockchain : this will run the app on port 3002 ( may shut down any app running on that port)
- open the frontend folder, search for https://bch-simple.herokuapp.com in Utils/Apis.js and replace it with http://localhost:3002
- go to http://localhost:3002/api to see your api running.
- cd base-blockchain/frontend 
- npm start : this will open the reactjs app in your local browser. Test and improve it.


### This project is an improvement of this article https://medium.com/swlh/is-it-hard-to-build-a-blockchain-from-scratch-2662e9b873b7

You can read it for basic understanding.


## Any contribution will be appreciated

Fork the repo, pull requests to contribute to this project.












