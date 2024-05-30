# metaethbegin
This smart contract defines a simple token system on the Ethereum blockchain. It includes features for minting (creating) and burning (destroying) tokens.

**Public Variables:**

tokenName stores the name of the token.
tokenAbbrv stores the abbreviation of the token.
totalSupply stores the total supply of the token.

**Mapping:**

balances maps addresses to their corresponding token balances.

**Mint Function:**

The mint function takes an address _to and a value _value.
It increases the totalSupply by _value.
It also increases the balance of the _to address by _value.

**Burn Function:**

The burn function takes an address _from and a value _value.
It checks if the balance of _from is greater than or equal to _value using require.
If the condition is met, it decreases the totalSupply by _value.
It also decreases the balance of the _from address by _value.
