# ETHEREUM - BEG 
This is my first solidity program which consists of a contract and 2 functions to  int and brun tokens.
# DEATILS 
In this my "mewMyToken" solidity contract implements a straightforward token system on the ETHEREUM BLOCKCHAIN . It defines essentail token attributes and provides basic functionalities to manage token supply and balances. Here are its main components and functionalities :
1 *TOKEN ATTRIBUTE *
- 'Token Name '=AMISHA
-  'Token Abbreviation'=SID
-  'total suppy'= nwTotalValue to have tracks the total number of tokens in circulation.
2 * BALANCE *
 The contract uses a mapping 'nwblaances' to keep track of each address's token balance,ensuring efficient storage and retrieval.
3 *MINTING TOKEN *
  The'nwmint'function allows the creation of new tokens. It taken an address
and a value as parameters , increase the total supply ,and credits the specified address with the new tokens.
4 *BURNING TOKENS *
   The 'nwbrun'function facilitates the destruction of tokens. It takes an address and a value as parameters and if the address has enough tokens, it decreases the total supply and the address's balance according.
5 *ACCESS AND MODIFICATION *
   Both the minting and burning functions are public , allowing any ures to interact with them.
# EXECUTION 
We ran this program using REMIX, an online IDE. We create a new file and name it whatever we want ,and save it as.sol extension. Copy and paste the code from thr ETH-BEG file and click on the complie from compiler tab. Go to deploy and deploy the contract and will find all the values. Copy the address from any of the supplied address from remix to use ans assign some value to balance mint some tokens using the address after you minted the tokens now you are buring them go to brun and use the same address as from mint and pick how many token to burn.
# SUMMARY
The newMyToken contract provides a foundational framework for creating and managing asimple custom token on the ETHEREUM BLOCKCHAIN .It can serve as a building block for more complex token system or decentralized application (dAPPS) that required a token based economy.


















