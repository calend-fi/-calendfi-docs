# calendfi-docs
### product requirements document

front-end source code:Typescript or javascript

smartcontract source code:Cardano Haskell


Source code introduction: The system has no management backend, and the data is completely decentralized. All data is stored in the contract on the chain. Only the front end interacts with the contract. The contract can be deployed in any network environment and is compatible with all networks. All executable operations such as setting the lock-up period and output rate can be executed in the contract. The contract comes with Chinese documents and comments, source code compilation and all maintenance documents and developer documents are provided. The front-end supports wallet connection network judgment and prompts to connect to the appropriate network. It can adapt to multiple network environments and can also be set independently to support only a single network.

### pledge step:

1，Supports pledge of any token reward. A certain token can open the time limit for withdrawal of pledge or the time limit for withdrawal of income (single currency reward single currency)

2，Support for staking any LP reward A certain token can open the time limit for withdrawal of pledge or time limit for withdrawal of income (liquidity reward single currency)

3，Supports pledge of any token to reward a certain token + a certain token can open the time limit for withdrawal of pledge or the time limit for withdrawal of income (single currency reward dual currency)


### Single currency mining business logic

What does single coin mining mean?
Single-coin mining is called single-coin lossless mining. A simple understanding of single-currency pledge is to pledge a token, which can be locked and pledged, or withdrawn at any time. The annualized income varies in different ways.The characteristic is to hold a single encrypted asset and generate income after pledge. This kind of pledge is very low risk (most of the time there is no risk), and the operation is simple. If you only pledge encrypted assets, that is, borrow assets without lending assets, it is equivalent to single-coin mining. The biggest drawback is that the rate of return is not high enough.


