# Research Notes

- [Topics](#topics)
- [Lending](#lending)
  - [Compound](#compound)
  - [Aave](#aave)
   - [Euler](#euler)
- [AMM](#amm)
  - [Uniswap](#uniswap)
  - [Balancer](#balancer)
- [Chainlink](#chainlink)
  - [Price Feeds](#price-feeds)
- [Beacon Chain](#beacon-chain)
- [Account Abstraction](#account-abstraction)
- [EVM](#evm)
  - [General](#general)
  - [Specific](#specific)
- [L2s](#l2s)
- [ZK](#zk)



## Topics

- [Foundry Cheatsheet](/Foundry.md)
- [OP Stack](/OP%20Stack.md)

## Lending
General
- [Lending-Borrowing attacks](https://dacian.me/lending-borrowing-defi-attacks)
- [Vulnerable spot sof lending protocols](https://mixbytes.io/blog/vulnerable-spots-of-lending-protocols#rec536982058)

### Compound

- [Compound V3 Interest Per Second](https://www.rareskills.io/post/compound-finance-interest-rate-model)
- [Principal value and Present Value in Compound V3](https://www.rareskills.io/post/defi-interest-rate-indexes)
- [Collateral, Liquidations, and Reserves in Compound V3](https://www.rareskills.io/post/compound-finance-liquidation)
- [Compound Whitepaper](https://compound.finance/documents/Compound.Whitepaper.pdf)
- [Compound Security](https://docs.compound.finance/#security)
- [Risk Methodology](https://medium.com/gauntlet-networks/improved-var-methodology-9f4f0c4cdb6f)


### Aave
- [Aave V3 Flash Loans](https://docs.aave.com/developers/guides/flash-loans)
- [Rates Math in Aave V3](https://docs.aave.com/developers/guides/rates-guide)
- [Collateral, Liquidations, and Reserves in Aave V3](https://docs.aave.com/developers/guides/liquidations)
- [Compound Whitepaper](https://github.com/aave/aave-v3-core/blob/master/techpaper/Aave_V3_Technical_Paper.pdf)
- [Compound Security](https://docs.aave.com/developers/deployed-contracts/security-and-audits)

### Euler-v2
- [Accounting](https://docs.euler.finance/euler-vault-kit-white-paper/#accounting)
- [Interest Model](https://docs.euler.finance/euler-vault-kit-white-paper/#interest)
- [Liquidations](https://docs.euler.finance/euler-vault-kit-white-paper/#liquidation)
- [Price Oracles](https://docs.euler.finance/euler-vault-kit-white-paper/#price-oracles)
- [EVC Whitepaper](https://github.com/euler-xyz/ethereum-vault-connector/blob/f791f94e6e790dd82041908983b57412dc04fb84/docs/whitepaper.md)
- [EVK Whitepaper](https://github.com/euler-xyz/euler-vault-kit/blob/f6fd0ee3b454630abd961d6471beb0c7eaf1216a/docs/whitepaper.md)
- [Security](https://github.com/euler-xyz/ethereum-vault-connector/tree/master/audits)
- [Risk Management](https://docs.euler.finance/euler-vault-kit-white-paper/#risk-management)
- [Vault Exchange Rate Manipulation](https://www.euler.finance/blog/exchange-rate-manipulation-in-erc4626-vaults)
- [ERC-4626 Incompatibilities](https://docs.euler.finance/euler-vault-kit-white-paper/#erc-4626-incompatibilities)
- [ERC-20 Incompatibilities](https://docs.euler.finance/euler-vault-kit-white-paper/#erc-20-incompatibilities)

## AMM

### Uniswap

- [Uniswap V3 Math Part 1](https://blog.uniswap.org/uniswap-v3-math-primer)
- [Uniswap V3 Math Part 2](https://blog.uniswap.org/uniswap-v3-math-primer-2)
- [Uniswap V3 Whitepaper](https://uniswap.org/whitepaper-v3.pdf)
- [Uniswap V3 Liquidity Math](https://atiselsts.github.io/pdfs/uniswap-v3-liquidity-math.pdf)
- [Uniswap V3 TWAP Manipulation](https://chaoslabs.xyz/posts/chaos-labs-uniswap-v3-twap-market-risk#783c9150ebcf)
- [Uniswap-v2 Book](https://www.rareskills.io/uniswap-v2-book)
- [Uniswap-v3 Book](https://uniswapv3book.com/)

### Balancer

- [Balancer Weighted Pool Math](https://medium.com/balancer-simulations/understanding-balancer-pools-c2b877dcc082)

## Chainlink

### Price Feeds

- [Ackee](https://ackeeblockchain.com/blog/chainlink-data-feeds/)
- [Dacian](https://medium.com/cyfrin/chainlink-oracle-defi-attacks-93b6cb6541bf)
- [0xMacro](https://0xmacro.com/blog/how-to-consume-chainlink-price-feeds-safely/)

## Beacon Chain

General

- [ETH 2.0 Beacon Chain Explained](https://consensys.io/blog/the-ethereum-2-0-beacon-chain-explained)
- [Consensus Spec](https://github.com/ethereum/consensus-specs)
- [Annotated Consensus Spec](https://github.com/ethereum/annotated-spec)

ETH Staking

- [eth2book](https://eth2book.info/capella/part2/)
- [EIP 4895 - Withdrawals](https://eips.ethereum.org/EIPS/eip-4895)
- [EIP 4788 - Beacon block root in EVM](https://eips.ethereum.org/EIPS/eip-4788)
- [Beacon Chain Proofs](https://github.com/Layr-Labs/eigenlayer-contracts/blob/dev/docs/core/proofs/BeaconChainProofs.md)

Re-orgs

- [Investigating why reorgs happen in POS Ethereum](https://www.samlewis.me/2022/03/beacon-chain-reorgs/)
- [Statistical Analysis of Reorgs](https://ethresear.ch/t/the-second-slot-itch-statistical-analysis-of-reorgs/16333)
- [Etherscan - Reorged blocks](https://etherscan.io/blocks_forked)

Indexers

- [beaconscan](https://beaconscan.com/)
- [beaconcha.in](https://beaconcha.in/)

## Account Abstraction

- [EIP 4337 - Account Abstraction](https://eips.ethereum.org/EIPS/eip-4337)
- [EIP 7579 - Modules](https://eips.ethereum.org/EIPS/eip-7579)
- [EIP 7484 - Registry](https://eips.ethereum.org/EIPS/eip-7484)
- [Infinitism Repository](https://github.com/eth-infinitism/account-abstraction)
- [Checklist by aviggiano](https://github.com/aviggiano/security/blob/main/audit-checklists/ERC-4337.md)

## EVM

### General

- [evm.codes](https://www.evm.codes) and [evm.storage](https://evm.storage/)
- [EVM Handbook](https://noxx3xxon.notion.site/The-EVM-Handbook-bb38e175cc404111a391907c4975426d)
- [Understanding the EVM - Part I](https://leftasexercise.com/2021/09/12/understanding-the-ethereum-virtual-machine-part-i/)
- [Understanding the EVM - Part II](https://leftasexercise.com/2021/09/15/understanding-the-ethereum-virtual-machine-part-ii/)
- [Understanding the EVM - Part III](https://leftasexercise.com/2021/09/19/q-understanding-the-ethereum-virtual-machine-part-iii/)

### Specific

- [Gas costs after Berlin](https://hackmd.io/@fvictorio/gas-costs-after-berlin)

## L2s

- [EVM Diff](https://www.evmdiff.com/)
- [rollup.codes](https://www.rollup.codes/)
- [Cross-chain](https://jumpcrypto.com/writing/cross-chain/)

## ZK

- [ZK Bug Tracker](https://github.com/0xPARC/zk-bug-tracker)
- [Least Authority MoonMath](https://github.com/LeastAuthority/moonmath-manual)
- [zk-book](https://www.rareskills.io/zk-book)

