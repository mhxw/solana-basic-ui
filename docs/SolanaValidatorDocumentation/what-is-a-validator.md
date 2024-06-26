# 什么是验证者?



验证者是一台帮助运行 Solana 网络的计算机。每个验证者都会执行一个程序来跟踪 Solana 集群上的所有账户，并验证添加到网络的交易。没有验证者，Solana 将无法运行。

运行验证者的独立实体越多，集群就越不容易受到攻击或灾难的影响。

> 要更深入了解 Solana 网络的健康状况，请参阅 [Solana 基金会验证者健康报告](https://solana.com/news/validator-health-report-march-2023)。

通过成为验证者，您不仅在帮助壮大网络，还能亲身了解 Solana 集群在最底层是如何运作的。您将成为热衷于 Solana 生态系统的活跃运营者社区一部分。

## 共识 vs RPC

在详细讨论验证者之前，我们先做一些区分。使用相同的验证者软件，您可以选择运行投票/共识节点或运行 RPC 节点。RPC 节点帮助 Solana 开发者和其他人与区块链互动，但出于性能原因，不应进行投票。我们将在下一节中详细讨论[什么是 RPC 节点](https://docs.solanalabs.com/what-is-an-rpc-node)。

在本文档中，当提到验证者时，我们指的是投票/共识节点。现在，为了更好地理解您的验证者在做什么，了解 Solana 网络如何运行会有所帮助。

## 权益证明（Proof Of Stake）

权益证明是 Solana 使用的区块链架构。之所以称为权益证明，是因为代币持有者可以将他们的代币质押给他们选择的验证者。当某人质押他们的代币时，该人仍然拥有这些代币，并且可以随时撤回质押。质押的代币代表了他们对该验证者的信任。质押代币给验证者时，作为帮助运行和保护网络的奖励，该人会获得一定数量的代币回报。您质押给验证者的代币越多，您获得的回报就越多。质押代币数量较多的验证者在共识中拥有更大的投票份额。因此，验证者在网络中生产区块的机会与其质押的代币数量成比例。目前在网络中生产区块的验证者称为领导者。

## 工作量证明（Proof Of Work）：作对比

Solana 不是一个工作量证明系统。工作量证明是一种不同的区块链架构，其中一台计算机（通常称为矿工）在网络上其他任何人解决之前，努力解决一个密码学问题。计算机解决这些问题的次数越多，矿工获得的奖励就越多。由于先解决复杂计算问题的激励，矿工通常会同时使用许多计算机。用于解决这些问题的计算机数量导致了大量的能量消耗和由此产生的环境挑战。

相比之下，Solana 不会激励验证者使用多台计算机来解决计算问题。由于验证者希望拥有更多的质押，因此独立验证者使用多台不同的计算机没有真正的优势。在此，您可以看到 [Solana 对环境影响](https://solana.com/news/solana-energy-usage-report-november-2021)的对比。

## 历史证明（Proof Of History）

历史证明（PoH）是 Solana 中的一个关键创新，使交易能够非常快速地完成。从高层次上看，PoH 允许集群中的验证者就一个可重复的加密时钟达成一致。上述的权益证明和工作量证明架构都是使集群达成共识的架构。换句话说，这些算法决定了哪些区块应被添加到区块链中。历史证明不是一种共识架构，而是 Solana 中的一项功能，使得在权益证明系统中区块的完成速度更快。

理解 PoH 的工作原理对于运行一个好的验证者并不是必须的，但可以参考这篇 [Medium 文章](https://medium.com/solana-labs/proof-of-history-explained-by-a-water-clock-e682183417b8)中通俗易懂的讨论。此外，[Solana 白皮书](https://solana.com/solana-whitepaper.pdf)对技术精通的人来说也很好地解释了这一算法。

## 身为验证者的你

作为验证者，您通过生成和投票区块来帮助保护网络，并通过运行独立节点来提高去中心化程度。您有权参与网络变更的讨论。同时，您也有责任保持系统正常运行，确保系统安全，并使其保持最新的软件版本。当越来越多的人将代币质押到您的验证者节点时，您可以通过运行高性能和可靠的验证者节点来回报他们的信任。希望您的验证者节点大多数时间都表现良好，但您还应有系统策略来应对任何时候的宕机。如果您的验证者在深夜未响应，需要有人（您或其他团队成员）能够调查并解决问题。

运行一个验证者是一项[技术性和重要的任务](https://docs.solanalabs.com/operations/prerequisites)，但它回报也十分丰厚。祝您好运，欢迎加入社区。