# Waves智能合约

智能合同是任何区块链平台的一个重要机制，它们的实现对人们来说应该是方便和易于理解的。

## 智能合约对Waves平台的效益

智能合约将为Waves生态系统带来新的附加功能和附加优势，如图1：

1. 智能合约将允许 **多重签名** 钱包，不能由一个人单独控制。 要进行交易，所有必要的参与方必须同时提供其私钥。 这是一个非常重要的安全功能，使团队可以安全地管理自己的财务状况，而无需将控制权仅交到其中一人手里。 这对于代币销售尤其有用，因为在部署之前资金可以安全地被保存。
2. 与其他类似的区块链不同的是，Waves智能合约 **不使用gas** 来完成非图灵完备智能合约——这意味着我们会预先知道固定成本。与以太坊相比，这使得Waves更加简化、高效且具有成本效益，同时仍可提供基本相同的服务。
3. 跨链原子互换也将被添加，而智能合约也将允许 **代币冻结** ——这意味着用户将能够引入一些参数，以防止买家在某个时限内出售或转让其地址的代币。这包括向用户发送一个代币，但确保它在一段时间内保持不可转发和消费。最明显的用例就是作为一种归属机制，或者在ICO后为团队/承包商付款。
4. Waves代币就像Waves本身，这意味着它们的处理方式完全相同，并保存在您的地址中 - 而平台仍支持在核心和标准Waves钱包中创建代币。 实质上，这使得终端用户的生活变得更加轻松。 此外，您创建的代币可以立即在Waves去中心化交易所DEX进行分配和交易，无需进一步的工作。
5. 基于图灵完备智能合约的去中心化应用程序\(DApps\) 将能够在Waves区块链上完成复杂的流程，满足各种不同的标准要求。
6. 余额管理，用户可能希望设定每月定期付款，而又需确保其账户不低于某个余额。 又或者他们可能希望在一个地址上保留一定数量的资金，并将多余的资金都转移到另一个账户中。

![](/_assets/Benefits-of-Waves-Smart-Contracts.png)图1，在Waves平台实行智能合约的效益

智能合约将为Waves平台带来什么？

**多重签名验证钱包**
- 双重因素认证
- 不能一人单独控制
- 所有参与方需同时提供私钥才能执行

**跨链原子交换**
- 在不同的区块链上可以无需信任的转换加密货币

**代币冻结**
- 防止买家在某个时限里售卖或者传送代币

**去中心化应用程序**
- 去中心化应用程序 \(DApps\) 将会基于“图灵完备”智能合约，将会根据不同的运行条件处理区块链上的复杂流程


## Waves智能合约的实施阶段

分为两个阶段，如图2:

1. 非图灵完备智能合约涵盖大部分使用案例，包括智能账户和智能代币。

2. 图灵完备智能合约可允许在区块链上创建去中心化的应用程序并自行发送交易。

![](/_assets/Stages-of-Waves-Smart-Contracts-Implementation.png)图2，Waves智能合约的实施阶段。

**Waves智能合约如何实践**

**第一阶段**	     “非图灵完备”智能合约

•	RIDE编程语言
•	使用智能资产和智能账号实践轻便简易版本的智能合约

**第二阶段**     “图灵完备”智能合约

•	RIDEON编程语言
•	根据不同的运行条件处理区块链上的复杂流程
•	开发人员将能够在区块链上执行任何前卫复杂的逻辑来解决几乎所有的计算任务


## 智能账户

智能账户的用意如下：

在交易提交列入下一个区块之前，该账户会检查交易是否符合脚本中定义的某些要求。将该脚本附加到该账户，以便该账户可以在确认每个交易之前验证它。 我们智能账户的主要要求是，它们可以按照预定的费用以正常交易的价格运行，而 **不需要** 额外的 **“gas”** 或其他成本。

智能账户不能私自发送交易或根据特定的条件转移资金，但可以从区块链中读取数据\(例如区块的高度或交易的签名\)，并依据数据的基础获得的谓词结果。

## 智能资产

如果我们计划对特定资产的所有操作应用限制条件，则不能使用智能账户。 在我们的范例中，我们拥有用于此目的的智能资产：脚本将被附加到资产并且将以类似的方式进行工作。 只有当脚本返回True\(正确\)时，这些资产的交易才有效。 例如，脚本可以验证交易证据，检查公证人/第三方托管人是否批准交易，以及资产操作是否在指定时间内不会被锁定。 使用资产时，代币的脚本在以下操作中被调用：

* 转让交易
* 大规模转让交易
* 重新发行交易
* 销毁交易

**提示.** 点击[**这里**](/technical-details/waves-contracts-language-description.md) 你找到更多有关我们智能合约实施的技术细节。