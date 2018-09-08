# GAMEOS

## Draw Number
American Roulette is a game of a wheel and 38 slots(0, 00, 1~36). After each game's round finished, the lottery program will send a lottery action to the smart contract, The winning number is the remainder of the block id and 38 of the transaction.  

Examples are as follows 
```
Transaction ID: 2dc024fc967031e28890be36cb3ab0b17c0b66e3419b1df43fcb04540c9fd297
Block Time    : Sep-04-2018, 11:02:43 PM	
Draw Action   : eosdeveosdev - drawing {gameId: 1, round_index: 1}
Block Number  :	14700773
Block ID      : 00e050e5287463d6c0da013819399fd3e1b5d761dacf27ba3893e718d07e0c3c

Compute: (Block ID Last 8 Byte)  Mod 38  => ‭3497921596‬(0xd07e0c3c) Mod 38 => 12
The draw lottery number  is 12

* When the number was 37, as 00
```


## 开奖号码
在美式转轮盘游戏的转盘内一共有38个不同的小方格(0, 00, 1~36). 在每局游戏结束后，抽奖程序将向智能合约发送抽奖动作，中奖号码是交易的块ID与38的余数.

举例如下
```
交易iD      : 2dc024fc967031e28890be36cb3ab0b17c0b66e3419b1df43fcb04540c9fd297
块当前时间   : Sep-04-2018, 11:02:43 PM	
投资动作    : eosdeveosdev - drawing {gameId: 1, round_index: 1}
块号码      :	14700773
块ID        : 00e050e5287463d6c0da013819399fd3e1b5d761dacf27ba3893e718d07e0c3c

计算方式: (块ID最后8字节)  取余 38  => ‭3497921596‬(0xd07e0c3c) 取余 38 => 12
中奖号码是 12

* 当号码是37时, 作为 00
```
Block Explorer:
- https://eosflare.io/account/eosdeveosdev
- https://bloks.io/account/eosdeveosdev
----
* Telegram Chat:  https://t.me/GAMEOS1
