# Wing - NFT-collateralized Borrowing Platform

## Why we need that

The main reason is that NFT are illiquid. 
Let's say, that your portfolio consists of NFTs. 
In fact, they cannot bring you income, and selling them right away can be problematic (it may take a long time).

Imagine having a platform, that will allow you to borrow liquidity against your NFTs. Therefore, it will give you the opportunity to "farm" with borrowed tokens (f.e. stake it).

There are also other reasons to make this platform. Imagine, that you are an NFT owner and you need money, but you do not want to sell NFT, because you know, that you will return money after short period of time. You can use this platform for that too.

## How that works

* Borrower creates a transaction, that gives approve to Wing smart-contract to transfer his NFT (as in marketplaces). 
He also sets the amount of NEAR tokens, he wants to borrow and the date of loan repayment. 

* Then the lender comes. And if he like this offer, he can give required amount of money to the borrower.

* When the lender agrees with this offer (by making a transaction), NEAR tokens will be transferred to the borrower, and borrower's NFT will be transferred to Wing smart-contract (escrow).

* The borrower must repay the loan before the deadline with fee.

* If the borrower is late - the lender can become the owner of this NFT.

## Disadvantages

* NFTs are often very volatile, so it can be risky for lenders (the approximate price of this NFT may decrease at some point), but of course, if you are lender, you can only pick a good offers from borrowers (f.e. if the borrower requires 20-30% of approximate price of his NFT).

* Described protocol is not as flexible as you can expect (f.e. it's not as Compound, because there are no pools for NFT's)
