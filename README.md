# Blockchain todo application setup
A basic decentralized blockchain todo application or Dapp on Ethereum Network.

Follow the steps below to download, install, and run this project.

**Dependencies:**
Install these prerequisites  
NPM: https://nodejs.org  
Truffle: https://github.com/trufflesuite/truffle  
Ganache: http://truffleframework.com/ganache/  
Metamask: https://metamask.io/  

**Step 1.** Clone the project  
```git clone https://github.com/techieguydev/blockchain-todo-app```

**Step 2.** Install dependencies  
```
$ cd blockchain-todo-app
$ npm install
```

**Step 3.** Start Ganache  
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance.

**Step 4.** Compile & Deploy Dapp  
```
$ truffle compile
$ truffle migrate
```

**Note:** You must migrate the Dapp smart contract each time your restart ganache 
```$ truffle migrate --reset```

Connect metamask to your local Etherum blockchain provided by Ganache.
Import an account provided by ganache.

**Step 6.** Run the Front End Application  
```$ npm run dev``` Visit this URL in your browser: ```http://localhost:3000```

If you get stuck, shoot an email at ```techieguydev@gmail.com``` or tag me on Twitter ```@iamqadirtechie``` we will reply to you as soon as possible.
