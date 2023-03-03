# Crowdfunding-smart-contract
A smart contract executing basic functionalities of a crowdfunding organisation for ethereum network.
This program is written in Solidity, and compiled and executed on remix IDE.
Inpute are taken in the cryptocurrency of Wei or Ether and calculations are done accordingly.
It includes methods such as:
1) sendEth() - responsible for sending Ethers from each network member to the collective fund.
2) refund() - responsible for returning the collected funds from each member of the network.
3) createRequest() - responsible for collecting relevant data and creating a request for funds for a social cause.
4) voteRequest() - responsible for storing the votes to each request.
5) makePayment() - (accessible solely by manager) responsible for paying the collected amount to the receiving party.
