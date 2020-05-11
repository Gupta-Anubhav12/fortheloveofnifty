---
layout: post
title: Block chain and Bitcoin
author: Anubhav Gupta
comments: true

---
<style>
   header{
      
     background-color: rgba(249, 241 ,241 , 0.7);
         font-weight: bolder;
         font-size: larger;
         font-family: fantasy;
        }
      </style>


We've seen the Evolution of money in regular Posts and we've seen how it evolved from Barter system to coins then to Fiat currency and so, But there's more to it and it took me to write this Fun-fin-Bit, We'll explore about Bitcoin and blockchain, How it evolved and what is the basic logic behind it's working.<br/>

It all started from 2008 subprime Crisis in USA, there a Debt cycle crashed due to exessive lending to subprime borrowers (Those who don't have enough capacity to repay),<br/>
This crisis led to a Global Crash and recession. The distrust in Fiat currency was dissolving away and just then A person Named satoshi Nakamoto, Shocked the world with a new breakthrough called Bitcoin<br/><br/>

The Basic logic behind the bitcoin was to create a decentralized and trustfull transaction environment.In a daily tansaction say a POS swipe at your grocery store is a centralised and a trust secured transaction involving your bank, the merchant's bank and the pos network as intermediaries and facilitators.<br/>
But this is a centraized approach.<br/>
There is an important factor in a transaction called **trust** without it a transaction that is cashless, is impossible. Now in existing systems the *trust* is provided by centralised institutions like Banks. <br/>
In a block chain this is provided by Powerful and secure algorithms that do the hashing but what is a blockchain ??<br/><br/>
let's see<br/>
A block chain is a chain of blocks that have some transactions stored into it. The blockchain works on the basis of a public ledger (a record of transactions). 
it's better to be understood by an Example<br/><br/>
Laddo wants to give Bunty a sum of 10,000 rupees and he gives him those in a closed envelope. Now ladoo has his ledger where he records a transaction, Bunty also records the transaction in his ledger, But both are very smart.<br/>
Laddoo records the transaction of 11,000 whereas Bunty enters rupees 9000. This is the greed that spoils the data and the use of ledger becomes useless. What if they both had same ledger and there was a single entry?? the process would have been transparent.<br/>
Same is the Idea behind a Blockchain, A blockchain is nothing but a Global single Public ledger which is immutable (can not be changed).<br/>
So blockchain is made up of blocks that are connected to each other using Hash (leave this for us "**IT**" guys focus on concept say hash is a code). now each transaction has Input and output refrence numbers called UTXO's and these allow peer to peer fund transfer, and enters the transaction to a block which then joins the chain. This becomes Transparent and trustful decentralized system.<br/>

Now the chain must grow to validate new transactions because the transactions can be sucessfull only if the block containing the transactions is added to the Block Chain.<br/>
Also the chain can grow in only one direction and can not form a web so there is a competition to add new blocks into the chain. There comes the fuss about **Bitcoin Mining**....<br/>
the system sets a strong computational puzzle for each block and people around the world "**Miners**" solve that puzzle to get their block added to the growing chain. Once a miner solves that puzzle , He/She broadcasts the block to global community and the block is added. The miner get a fees for his work which is a reward for his/her contribution to the growth of chain.<br/>
The Bitcoin has no underlying asset but trust genereated by the algorithms like the famous ECC algorithm used for hashing,and the efforts of miners to generate the bitcoin.<br/>
Bitcoin and other crypto currencies like ether use Encryption which uses public private pair of keys. hence provide security on the factors like:<br/>
 1. The sender is correct
 2. reciever is correct
 3. No one else can get money hence no transaction failure

Bitcoin just has the ability to transfer the funds but it can't execute any logical argument or comtract.<br/>
Example you are hosting an auction and require the clients to be older than 18 but bitcoin won't have provision to execute the logic to reject the bids of clients under 18.<br/>
There comes the new cryptocurrency called Ether which uses a specially designed OOP language called **Solidity** which can create classes based on user defined logics called **Smart Contracts**. These can be like rejecting underage buyers, getting Time delays and initiate deffered payments etc.<br/><br/>

A bitcoin or a cryptocurrency block looks like the snip shown below. The first block of any cryptocurrency is called the genesis Block and is independent of parent hash, because no block Existed before it.<br/>
the image below shows the latest block of bitcoin and it has 2066 transactions added to the public immutable ledger. In laymans terms Hash is a code which links the previous block to this one.
<img style="float:left;"src="https://i.postimg.cc/vHnC9D9g/Screenshot_2020-05-11-20-20-12-04.jpg">


  












{% if page.comments %}

<div id="disqus_thread"></div>
<script>
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = 'https://https-gupta-anubhav12-github-io-fortheloveofnifty.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>

{% endif %}