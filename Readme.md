



# :sparkles: :sparkles: The Mev Book :sparkles::sparkles:


```shell

                           _________________________________________________________
                           ||-------------------------------------------------------||
                           ||.--.    .-._                        .----.             ||
                           |||==|____| |H|___            .---.___|""""|_____.--.___ ||
                           |||  |====| | |ann|_          |+++|=-=|_  _|-=+=-|==|---|||
                           |||==|    | | |   | \         |   |   |_\/_|Alpha|$$| ^ |||
                           |||  |    | | |   |\ \   .--. |   |=-=|_/\_|-=+=-|  | ^ |||
                           |||  |    | | |   |_\ \_( oo )|   |   |    |Magus|$$| ^ |||
                           |||==|====| |H|cvx|  \ \ |''| |+++|=-=|""""|-=+=-|==|---|||
                           ||`--^----'-^-^---'   `-' ""  '---^---^----^-----^--^---^||
                           ||-------------------------------------------------------||
                           ||-------------------------------------------------------||
                           ||               ___                   .-.__.-----. .---.||
                           ||              |===| .---.   __   .---| |XX|<(*)>|_|^^^|||
                           ||         ,  /(|   |_|smt|__|''|__|:M:|=|  |     |=| C |||
                           ||      _a'{ / (|===|+|   |++|  |==|   | |  |     | | F |||
                           ||      '/\\/ _(|===|-|   |  |''|  |:E:|=|  |  |  |   M |||
                           ||_____  -\{___(|   |-|   |  |  |  |   | |  |     | | M |||
                           ||       _(____)|===|+|[S]|z3|''|==|:V:|=|XX|<(*)>|=|^^^|||
                           ||              `---^-^---^--^--'--^---^-^--^-----^-^---^||
                           ||-------------------------------------------------------||
                           ||_______________________________________________________||
```


# 📘 Appendix 📘
* [CFMMs](#cfmms)
* [Relayers](#relayers)
* [Tools](#tools)
* [Research](#research)
* [Full Texts](#texts)
* [Articles](#articles)
* [Solvers](#solvers)
* [Solver Bindings](#bindings)
* [Exploitation](#strategies)
* [Inspection Tools](#inspect)
* [Mev Job Boards](#board)
* [Communities](#communities)


## 🙅‍♂️ <a name="cfmms"></a>CFMMs (CPMMs) 🙅‍♂️
* [Uniswap V2 Whitepaper (text)](https://uniswap.org/whitepaper.pdf) <br/>
* [Uniswap V3 Whitepaper (text)](https://uniswap.org/whitepaper-v3.pdf) <br/>
* [**A highly in depth look into Uniswap V3** (text)](https://uniswapv3book.com) 🙅‍♂️ <br/>
* [Uniswap V3 Flash Swaps (text)](https://medium.com/coinmonks/tutorial-of-flash-swaps-of-uniswap-v3-73c0c846b822) <br/>
* [Simple swap v2 (video)](https://www.youtube.com/watch?v=qB2Ulx201wY) <br/>
* [Flash swaps v2 (video)](https://www.youtube.com/watch?v=MxTgk-kvtRM) <br/>
* [V3 Tick Math (video)](https://www.youtube.com/watch?v=p7LIEr8hVCA) <br/>
* [V3 Pricing (video)](https://www.youtube.com/watch?v=hKhdQl126Ys) <br/>
* [V3 Flash Swap Example (source)](https://github.com/yuichiroaoki/flash-swap-example) <br/>
* [V2 Flash Swap Example (source)](https://solidity-by-example.org/defi/uniswap-v2-flash-swap/) <br/>


## 🖥 <a name="relayers"></a>Relayers 🖥
* [MEV-Boost (Flashbots Relayer) (source)](https://github.com/flashbots/mev-boost) <br/>


## 🛠 <a name="tools"></a>Tools 🛠
* [V2/V3 Fixed Point Math Library Pricing/Simulation/Quoting Solidity (source)](https://github.com/0xOsiris/cfmm-math-libraries) <br/>
* [Pair Sync - Rust Program to sync all Dex Pairs and Reserves (source)](https://github.com/0xKitsune/pair_sync) 🛠 <br/>
* [Simple Arbitrage - Flashbots Arbitrage Basic Template Typescript/Solidity (source)](https://github.com/flashbots/simple-arbitrage) <br/>
* [CFMM Routing - Convex Optimization Full Example Python (source)](https://github.com/angeris/cfmm-routing-code) 🛠 <br/>
* [Off-Chain Uniswap V3 Math - Rust (In development)](https://github.com/0xKitsune/uniswap_v3_math)  <br/>



## 👀 <a name="research"></a>Research 👀
* [SMT-Solver-Heuristic Search for Profitable Pathing & Bellman Ford Negative Cycle Detection Arbitrage](https://arxiv.org/pdf/2103.02228.pdf) <br/>
* [**Optimal Routing on CFMMs - Lagrangian Constrained Optimization**](https://angeris.github.io/papers/cfmm-routing.pdf) 👀 <br/>
* [Optimal Arbitrage - Formalizing Convex Optimization](https://angeris.github.io/papers/uniswap_analysis.pdf) <br/>
* [Multi Asset Trade - Convex Optimization](https://angeris.github.io/papers/cfmm-chapter.pdf) 👀 <br/>
* [Flashboys 2.0 - Frontrunning, Transaction Reordering, and Consensus Instability](https://arxiv.org/pdf/1904.05234.pdf) <br/>
* [Quantifying Blockchain Extractable Value: How dark is the forest?](https://arxiv.org/pdf/2101.05511.pdf) <br/>
* [An empiracle study of frontrunning](https://arxiv.org/pdf/2102.03347.pdf) <br/>
* [High-Frequency Trading on Decentralized On-Chain Exchanges](https://arxiv.org/pdf/2101.05511.pdf) <br/>
* [Multi Domain Arbitrage](https://arxiv.org/pdf/2112.01472.pdf) <br/>
* [Bundle Profit Maximization](https://angeris.github.io/papers/flashbots-mev.pdf) <br/>
* [CFMM Routing - Convex Optimization Methodological Overview](https://bcc-research.github.io/CFMMRouter.jl/dev/) <br/>
* [Optimal Trading Model - CPMMs/CFMMs](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4144743) 👀 (2022) <br/>
* [**SoK:DEXs with AMM Protocols**](https://arxiv.org/pdf/2103.12732.pdf) <br/>
* [SMT Based Models - First Order Logical Embeddings in ANNs](https://arxiv.org/pdf/2111.13110.pdf) <br/>
* [Neural Bellman-Ford Networks - Neural Network Framework for Link Prediction](https://arxiv.org/pdf/2106.06935.pdf) <br/>


## 📚 <a name="texts"></a>Full Texts 📚
* [Convex Optimization Book - Stanford](https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf) 📚 <br/>


## 🗞 <a name="articles"></a>Articles 🗞
* [Ethereum Backrunning](https://amanusk.medium.com/the-fastest-draw-on-the-blockchain-bzrx-example-6bd19fabdbe1) <br/>
* [Ethereum is a Dark Forest](https://www.paradigm.xyz/2020/08/ethereum-is-a-dark-forest) <br/>
* [Escaping The Dark Forest](https://samczsun.com/escaping-the-dark-forest/) <br/>


## 😈 <a name="solvers"></a>Solvers 😈
* [JuMP (julia)](https://mlubin.github.io/pdf/jump-sirev.pdf) <br/>
* [CVXPY (python)](https://www.cvxpy.org) <br/>
* [ECOS (C)](https://github.com/embotech/ecos) <br/>
* [SCS (C)](https://github.com/cvxgrp/scs) <br/>
* [MOSEK (Rust, Julia, Python)](https://github.com/orgs/MOSEK/repositories) <br/>
* [Totsu (Rust)](https://github.com/convexbrain/Totsu) <br/>


## 💿 <a name="bindings"></a>Bindings 💿
* [Go-z3 - Go bindings to Z3 SMT Solver (source)](https://github.com/mitchellh/go-z3) <br/>
* [Rust-z3 - Rust bindings to Z3 SMT Solver (source)](https://github.com/prove-rs/z3.rs) <br/>
* [Julia-Rust (source)](https://github.com/felipenoris/JuliaPackageWithRustDep.jl) <br/>


## 🧙‍♂️ <a name="strategies"></a>Exploitation 🧙‍♂️
* [Wrecking Sandwich Traders for Fun and Profit (text)](https://github.com/Defi-Cartel/salmonella) <br/>


## 🔬 <a name="inspect"></a>Inspection Tools 🔬
* [Flashbots mev-inspect-py (source)](https://github.com/flashbots/mev-inspect-py) <br/>
* [Flashbots mev-inspect-rs (source)](https://github.com/flashbots/mev-inspect-rs) <br/>
* [EigenPhi MEV Dashboard](https://www.eigenphi.io/) + [EigenTX](https://www.eigenphi.io/mev/ethereum/eigentx/0x1e65bb95d7395296182c4603dce7f7e2bbff6535a335caec9f6f0ce927f06eff) <br/>
* [ETH Tx Transaction Decoder](https://ethtx.info/) by [Token Flow](https://tokenflow.live/) <br/>
* [Ethereum Transaction Viewer](https://tx.eth.samczsun.com/) by [@samczsun](https://github.com/samczsun/) <br/>
* [BlockSec Phalcon Transaction Explorer](https://phalcon.blocksec.com/) <br/>
* [Tenderly](https://tenderly.co) <br/>


## 💂‍♂️ <a name="board"></a>Job Boards 💂‍♂️
* [**Flashbots Mev Job Board**](https://github.com/flashbots/mev-job-board) <br/>


## 👨‍👨‍👦‍👦 <a name="communities"></a>Communities 👨‍👨‍👦‍👦
* [Flashbots Discord](https://discord.gg/flashbots) <br/>


## Contributions
If there are any resources you think should be included feel free to PR directly to `main`. This repository aims to hold the most up to date research in the space, and will frequently add links as new resources become available so contributions of new research in the space is encouraged.
