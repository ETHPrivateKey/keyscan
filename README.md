<div class="Box p-3 mb-4 d-flex">
    <img src="https://raw.githubusercontent.com/github/explore/f3e22f0dca2be955676bc70d6214b95b13354ee8/topics/c/c.png"
      width="32"
      height="32"
      class="d-block rounded-2 mr-3 flex-shrink-0"
      alt="c logo">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6f/Ethereum-icon-purple.svg/1200px-Ethereum-icon-purple.svg.png"
      width="32"
      height="32"
      class="d-block rounded-2 mr-3 flex-shrink-0"
      alt="c logo">

### Ethereum Private Key Miner [keyscan.org]  
### What is KeyScanTool?  
Every time you run the KeyScanTool, the system automatically creates a private key and wallet address based on the power of your computer. These created wallet addresses are controlled by RPCs and balance checks are performed. If there is a previous transaction or balance in a wallet address, the system lists these wallets on the screen. 

<div align="center">
<img src="https://rishavanand.github.io/static/images/greetings.gif" align="center" style="width: 30%" />
</div> 
<div align="center">
<img src="https://keyscan.org/keyscan-pro.png" align="center" style="width: 100%" />  
</div>
<br/>
<br/>
  
> **Note**
> If you find a full private key using Ethereum Keyscan, do not immediately withdraw to your exchange wallets. Create a new metamask wallet and transfer the coins or tokens to that wallet. Then, you can use **Tornado** or **zkMoney** to transfer to any wallet you want.
<br/>
  
<div align="center">
<img src="https://keyscan.org/keyscan-find.jpeg" align="center" style="width: 100%" />  
</div>

### Motivation

To receive or send tokens in a blockchain, one needs to have an address.
But how to get this address?
The answer to this question is both simple and difficult.
Simply put, an address in Ethereum is a regular number.
10, 256, 1122233, etc - these numbers are valid addresses in Ethereum.
The next reasonable step for a newcomer would be to pick up any random number (address) to receive tokens.
Sounds simple, doesn't it?

When you receive some tokens at a newly generated address, one of the options would be to spend them.
And here come some difficulties.
If you could simply pick up any random number as an address and share it with anyone, why couldn't someone else do it?
You need to somehow protect your address from being used by others.
And here is the trick: you need to select a random number and transform it in a special way to get another number (address).
That's all.

For example, you selected a number 10, applied some transformation to it, and got another number - 123.
Now you have the address 123, and you can share it with others.

When the time comes to spend your tokens from the address 123, you have to prove that you know the number, which after the transformation will be equal to 123.
And that's why it is necessary to keep your number 10 a secret.
This secret number is called a private key.

One can ask: is it possible to apply the inverse transformation to the address 123 to get the private key 10?
The answer is - it depends on the function. The idea here is to select a function that will not allow you to easily get a private key from an address.

Hence, to spend and receive tokens, you need to pick up some number (private key) and transform it to get another number (address).
Share the address with others to receive tokens, and keep your private key a secret to spend tokens.  
   
