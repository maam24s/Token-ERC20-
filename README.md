Create your own Ethereum Token ERC20 and Verified

Step 1: 
In order to create an ERC20 token, you need the following:

    The Token’s Name
    The Token’s Symbol
    The Token’s Decimal Places
    The Number of Tokens in Circulation

For The Most Private Coin Ever , I chose:

    Name: The Most Private Coin Ever
    Symbol: ???
    Decimal Places: 0
    Amount of Tokens in Circulation: 100,000

The decimal places is where things can get tricky. Most tokens have 18 decimal places, meaning that you can have up to .0000000000000000001 tokens.

When creating the token, you’ll need to be aware of what decimal places you’d like and how it fits into the larger picture of your project.

For me, I wanted to keep it simple and wanted people to either have a token, or not. Nothing in between. So I chose 0. But you could choose 1 if you wanted people to have half a token, or 18 if you wanted it to be ‘standard’.

Step 2: 

So that means, change:

    The token name
    The token symbol (I'd go no more than 4 characters here)
    The token decimal places
    How much you as the owner want to start off with
    The amount of tokens in circulation (to keep things basic, make this is the same amount as the owner supply)

Some things to keep in mind:

    The supply that you set for the token is correlated to the amount of decimal places that you set.

For example, if you want a token that has 0 decimal places to have 100 tokens, then the supply would be 100.

But if you have a token with 18 decimal places and you want 100 of them, then the supply would be 100000000000000000000 (18 zeros added to the amount).

    You set the amount of tokens you receive as the creator of the contract.

That’s what this line of code is:

balances[msg.sender] = NUMBER_OF_TOKENS_HERE;  

Step 3: 
So you’d hit ‘Create’ under ‘TutorialToken’.
What will happen is MetaMask will pop up asking you to hit ‘Submit’ to pay for the transaction.

Remember, this is the Ropsten test net, so it’s not real Ether. You can double check to make sure you’re on the test network in MetaMask before you hit submit just to be sure.

Step 3.5. 

Please go to add that to MetaMask ‘Tokens’ tab:

When I click the “+” button, I can paste it in there and it’ll automatically insert the information of the token
Let’s hit ‘Add’.

Sweet! It says I have the 100 tokens that I created - it worked!

Now I can send those tokens, or sell them on a market if I decide to do so.

Step 4. 
This is going to be important for various reasons, mainly verifying the validity of your token to the public.

It doesn’t technically matter, and your token will still be usable if you don’t do it, but it’s good practice to verify it so people know that you’re not doing anything shady.

When you’re on the Transaction screen from the previous step, click where it says [Contract xxxxxx Created] in the To: field. That’s the Contract we just published.
Step 5. Get it on The Main Net

Now that everything’s working, it’s time to deploy it on the MainNet and let other people use it.

Step 6

This step is not required, but it adds to the validity of your token if you get it verified by them.
Congrats! 

.
