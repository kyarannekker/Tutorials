## 什么是区块链？
从字面上看：区块链是由一个个记录着各种信息的小区块链接起来组成的一个链条，类似于我们将一块块砖头叠起来，而且叠起来后是没办法拆掉的，每个砖头上面还写着各种信息，包括：谁叠的，什么时候叠的，砖头用了什么材质等等，这些信息你也没办法修改。

从计算机上看：区块链是一种比较特殊的分布式数据库。分布式数据库就是将数据信息单独放在每台计算机，且存储的信息的一致的，如果有一两台计算机坏掉了，信息也不会丢失，你还可以在其他计算机上查看到。

区块链是一种分布式的，所以它是没有中心点的，信息存储在所有加入到区块链网络的节点当中，节点的数据是同步的。节点可以是一台服务器，笔记本电脑，手机等。你要知道的是这些节点的存储的数据都是一模一样。

![](https://i.imgur.com/sLg0r49.jpg)

## 区块链特性
去中心化：因为它是分布式存储的，所以不存在中心点，也可以说各个节点都是中心点，生活中应用就是不需要第三方系统了（银行、支付宝、房产中介等都属于第三方）。

开放性：区块链的系统数据是公开透明的，每个人都可以参与进来，比如租房子，你可以知道这个房子以前的出租信息，有没出现过问题，当然这里头的一些个人私有信息是加密的。

自治性：区块链采用基于协商一致的规范和协议（比如一套公开透明的算法），然后各个节点就按照这个规范来操作，这样就是所有的东西都有机器完成，就没有人情成分。 使得对"人"的信任改成了对机器的信任，任何人为的干预不起作用。

信息不可篡改：如果信息存储到区块链中就被永久保存，是没办法去改变，至于 51% 攻击，基本不可能实现。

匿名性：区块链上面没有个人的信息，因为这些都是加密的，是一堆数字字母组成的字符串，这样就不会出现你的各种身份证信息、电话号码被倒卖的现象。

## 区块结构
区块包含两个部分：
1、区块头（Head）：记录当前区块的元信息

2、区块体（Body）：实际数据

![](https://i.imgur.com/k8r3BOf.jpg)

## 区块链如何工作
我们以转账为例:
目前我们转账都是中心化的，银行是一个中心化账本，例如 A 账号里有 400 块钱，B 账号里有 100 块钱。
当 A 要转 100 块钱给 B 时，A 要通过银行提交转账申请，银行验证通过后，就从 A 账号上扣除 100 块，B 账号增加 100 块。
计算后 A 账号扣除 100 后余额为300元，B 账号加上 100 后余额为 200 元。

![](https://i.imgur.com/7xCYugt.png)

区块链上转账的步骤则是：A 要转账给 B 100 块钱，A 就会在网络上把要转账的这个信息告诉大家，大家会去查看 A 的账户上是否有足够的钱去完成这个转账，如果验证通过后，大家就把这个信息都记录到自己的电脑上区块链中，且每个人记入的信息都是同步一致的，这样 A 就顺利将 100 块钱转移到了 B 的账户上。可以看到这中间并没有银行啥事。

![](https://i.imgur.com/lQwTgEu.png)