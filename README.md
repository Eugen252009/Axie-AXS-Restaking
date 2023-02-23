# This is a Docker Container which restakes AXS every 24hrs.

 # About

  This is a Docker Container for Automatic restaking of staking rewards.

# Future Implementations:

Land Staking claim: **WIP**

Katana Staking claim: **WIP**

 # Installation Guide:

**clone Repository**

>git clone https://github.com/Eugen252009/Axie-AXS-Restaking.git

**Import your wallet in the "encryptKey.js" file**

>vi encryptKey.js

**Choose your Password .env file**

>cp .env-Example .env

>vi .env

**only when last Staking >24hrs.**
  **edit lastClaimedBlock to the actual last claimed Block**

>vi index.js


**Run Wallet encryption**

>run "node encryptKey.js"

**Build your Docker Container**

>"docker build -t AutoRestake ."

**Run your Docker ContainerencryptKey.js**

>"docker run AutoRestake"

  
# Info 

*i made an Automatic Fee of 0.1 RON every Time an Restake Event happens*

Feel Free to send me a coffee!

**Ronin**

ronin:4fe53c4e4b52a3229095646ee0192c6e0a9c8c2d

**Ethereum:**

0x4fe53c4e4b52a3229095646ee0192c6e0a9c8c2d
