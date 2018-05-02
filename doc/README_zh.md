# <center>EDCC</center>

> EDCC是一个基于以太坊的代币

1. 代币基于TokenERC20创建，满足TokenERC20格式

``` javascript
    function TokenERC20(uint256 initialSupply, string tokenName, string tokenSymbol, uint8 tokenDecimals) public {
        name = tokenName;
        symbol = tokenSymbol;
        decimals = tokenDecimals;
        totalSupply = initialSupply * 10 ** uint256(decimals);
        balanceOf[msg.sender] = totalSupply;
    }
```

2. EDCC 保证不再进行增发

3. EDCC 发行总量为一亿个

[English DOC](../README.md)
