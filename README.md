# Skill-Verification-Using-BlockChain

This is a Project developed for showing BlockCahin Transactions. Feel free to use it.

Description of each files:
1. migrations Folder: Used for "truffle migrate " command while using Truffle.
2. node modules: Consists of all the node modules required for running the Project.
3. public and src Folder: Consists of all the pages for the DApp in ReactJs.
4. test Folder: Used for the testing of smart Contracts.
5. seed-phrase.js: This file will consist of the MNEMONIC of Your BlockChain(Dummy or test).
6. truffle-config.js: this file will be used for configuring Ganache Blockchain. 

Inside src folder:
1. abis: Used with Smart Contracts on the Front-End Pages.
2. components: Used in React Pages.
3. contracts: Consists of all Smart contracts used in the Project.
4. firebase: Consists of Firebase Configuration and api used in the Project.
5. pages: Consists of all React Pages.
6. App.js and index.js: Used for running the React Pages.
7. MetaMaskGuide.js: Used for testing the MetaMask Wallet in the Browser.

How to run this Project: 
1. Extract the zip file of the Project in your PC and run "npm install" command in the terminal to download all the required node modules.
2. Download Ganache from https://trufflesuite.com/ganache/ for your respective OS.
3. Start your Ganache Server on the UI and create a new Workspace in Ganache.
4. To Create a new Ganache Workspace: 
Click on "New Workspace"< type in your Workspace name and select the "truffle-config" file under truffle Projects < Click on Save workspace.
Once done you should see the dummy Accounts for testing the Project.

NOTE: The first Account in the List with index 0 will be used for the Admin Account, rest all can be used for Employee and Organizations respectively.

5. Go into the root folder where you can see "truffle-config" file and run "truffle migrate" command in the terminal to compile and run your Smart Contract.
6. On compiling the Contracts successfully, go to your Browser and install MetaMask Extension.
7. Add a new network with:
    
    Network Name: <"anything you wish">

    New RPC URL: http://127.0.0.1:7545  (This will also be available in the Ganache UI)
    
    Chain ID: 1337
    
    Currency symbol: ETH

8. After adding the network, Add the first Account of the Ganache Blockchain as Admin in the Wallet.
9. Add Other Accounts for Testing as Employee or Organization.
10. Once thee all are set up, go into the src folder and run the command: npm start

For the video Demo: https://vimeo.com/629030779/cb18ff23a5