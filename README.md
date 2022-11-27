# TokenizedBallot
As part of the EncodeClub Solidity Bootcamp, in one of the so-called Weekend Projects, I build
a blockchain application consisting of an Angular frontend (tokenizedBallot_client) and a
nest.js backend (tokenizedBallot_server). 

# What is this?
In this application, a user can interact with any deployed instance of the TokenizedBallot contract (on Goerli).

He is then able to...

1. claim tokens (i.e voting power)
2. delegate his voting power to any address
3. vote for a proposal
4. get the ballots winner

as well as connect to another TokenizedBallot via its contract address.

This project was my first time working with angular as a frontend framework, as well as nest.js as a backend framework.

# How to use?
1. <code>git clone --recurse-submodules https://github.com/Fiodos/tokenizedBallot.git</code>
2. Inside the tokenizedBallot_client, call <code>yarn start</code>.
3. Inside the tokenizedBallot_server, call <code>npm start</code>.
4. Head to localhost:4200 inside your browser and explore!
