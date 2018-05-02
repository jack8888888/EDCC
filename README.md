# <center>EDCC</center>

> A token based on the etheric square

1. the token created from TokenERC20

``` javascript
    function TokenERC20(uint256 initialSupply, string tokenName, string tokenSymbol, uint8 tokenDecimals) public {
        name = tokenName;
        symbol = tokenSymbol;
        decimals = tokenDecimals;
        totalSupply = initialSupply * 10 ** uint256(decimals);
        balanceOf[msg.sender] = totalSupply;
    }
```

2. EDCC guarantees that it will not be added again

3. EDCC token total is one hundred million

[中文版说明](./doc/README_zh.md)
