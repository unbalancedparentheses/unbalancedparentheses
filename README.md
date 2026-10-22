# Hi, I'm Federico

I founded [LambdaClass](https://lambdaclass.com) and [Ergodic Group](https://ergodicgroup.com). LambdaClass does protocol engineering, compilers, and formal verification, mostly Rust, Erlang, and Lean. Ergodic Group is the holding company on top: we run software companies, a quant finance operation, an animation studio, a vineyard, and a sushi restaurant, among other things. I also work on the core of Ethereum, applied cryptography and cybersecurity.

I spend most of my time on formal systems, proofs, and verified kernels. I also read too much about uncertainty, fat tails, and the limits of knowledge. The two interests contradict each other and I'm fine with that.

Currently: building [stabileo](https://github.com/lambdaclass/stabileo) (structural analysis in the browser), [Concrete](https://github.com/lambdaclass/concrete), a language designed so programs can be proved correct in Lean, and [lean-extremevaluetheory](https://github.com/unbalancedparentheses/lean-extremevaluetheory), a machine-checked library of extreme value theory and heavy tails. Also working on [ethrex](https://github.com/lambdaclass/ethrex), [lambdaworks](https://github.com/lambdaclass/lambdaworks), a [native compiler backend in Lean](https://github.com/unbalancedparentheses/lean-compiler-backend), running crash detection signals on centuries of FX data, and building an [options backtester](https://github.com/lambdaclass/options_portfolio_backtester).

## Built at LambdaClass

- ⛓️ [ethrex](https://github.com/lambdaclass/ethrex). Ethereum execution client in Rust, both L1 and L2
- 🔐 [lambdaworks](https://github.com/lambdaclass/lambdaworks). Our SNARK/STARK prover library
- 🧱 [concrete](https://github.com/lambdaclass/concrete). A language we're building for scalable, verifiable systems
- 📊 [options_portfolio_backtester](https://github.com/lambdaclass/options_portfolio_backtester). Options backtester we use internally
- ⚙️ [cairo_native](https://github.com/lambdaclass/cairo_native). Compiles Cairo Sierra down to MLIR
- 🏛️ [cairo-vm](https://github.com/starkware-libs/cairo-vm). Cairo VM reimplemented in Rust, now maintained by StarkWare
- 🔮 [lambda_ethereum_consensus](https://github.com/lambdaclass/lambda_ethereum_consensus). Ethereum consensus client in Elixir, built on the BEAM for fault tolerance
- 🏗️ [stabileo](https://github.com/lambdaclass/stabileo). Open-source 2D & 3D structural analysis in the browser. Direct Stiffness Method, real-time solving, no installation
- 🎓 [erlings](https://github.com/lambdaclass/erlings). Erlang exercises, rustlings-style

## Personal Projects

**Formal Verification**
- 📉 [lean-extremevaluetheory](https://github.com/unbalancedparentheses/lean-extremevaluetheory). Extreme value theory and heavy-tailed probability in Lean 4: Fisher–Tippett–Gnedenko, regular variation, Karamata, Breiman. ~94k lines, 3,900 theorems, no `sorry`
- 🛠️ [lean-compiler-backend](https://github.com/unbalancedparentheses/lean-compiler-backend). Native compiler backend written in Lean 4, starting as a QBE 1.3 port. Builds and runs real C programs through cproc
- 🔩 [lean4-baremetal](https://github.com/unbalancedparentheses/lean4-baremetal). Lean 4 on bare-metal RISC-V, no OS and no libc. Verified SHA-256, a CAN 2.0 parser, and an automotive torque-enable gate, 167 theorems over the code that actually runs
- 🪤 [verified-still-broken](https://github.com/unbalancedparentheses/verified-still-broken). Five Lean proofs that type-check and still sit on real bugs. The bug lives in the spec, the model, or the trusted base

**Quantitative Finance**
- 💥 [fatcrash](https://github.com/unbalancedparentheses/fatcrash). Crash detection using LPPLS, EVT, Hill estimator, VRP, and a bunch of other signals. Rust core with Python/PyO3 bindings
- 💱 [forex-centuries](https://github.com/unbalancedparentheses/forex-centuries). Exchange rate data going back centuries. Useful for volatility research when you don't trust short samples
- 📈 [finance_research](https://github.com/unbalancedparentheses/finance_research). Notebooks on options backtesting, tail hedging, carry strategies

**Tools**
- 📖 [readtube](https://github.com/unbalancedparentheses/readtube). Turns YouTube videos into typeset ebooks
- 🗄️ [llm-archive](https://github.com/unbalancedparentheses/llm-archive). Ingests all my Claude Code and Codex conversations into SQLite, strips the code, keeps the thinking. Search and analysis over months of LLM usage
- 🎬 [media-server](https://github.com/unbalancedparentheses/media-server). Self-hosted media server, Docker Compose
- 🗣️ [stoa](https://github.com/unbalancedparentheses/stoa). Send the same prompt to multiple LLMs, compare side-by-side. Native app, Rust + GPU

## Books

- 🦀 [Cryptography in Rust for Hackers](https://cryptographyinrustforhackers.com). From the math foundations up to SNARKs and STARKs, with Rust implementations
- 🤝 [Distributed Consensus in Rust for Hackers](https://distributedconsensusinrustforhackers.com). Consensus from crash fault tolerance to Byzantine protocols and modern blockchain consensus
- 🔏 [Practical Cryptography and Distributed Ledgers](https://github.com/unbalancedparentheses/practical_cryptography_and_distributed_ledgers). Study guide to cryptography and ZK proving systems, with Pablo Deymonnaz and Diego Kingston
- 📐 [Data Science in Julia for Hackers](https://github.com/unbalancedparentheses/data_science_in_julia_for_hackers). Open book on applied data science

## Reading Lists

I keep curated reading lists for whatever I'm trying to learn.

- 🐚 [spawnedshelter](https://github.com/unbalancedparentheses/spawnedshelter). The best articles, talks, and books for learning Erlang and Elixir
- 🎲 [the_bayes_way](https://github.com/unbalancedparentheses/the_bayes_way). Bayesian statistics
- 🐘 [learning_leptokurtic](https://github.com/unbalancedparentheses/learning_leptokurtic). Fat tails and kurtosis
- 🔁 [learning_ergodicity_economics](https://github.com/unbalancedparentheses/learning_ergodicity_economics). Ergodicity economics lecture notes
- 💹 [learning_economics](https://github.com/unbalancedparentheses/learning_economics). Economics books, papers, and courses

<details>
<summary>More reading lists</summary>

- [learning_formal_verification](https://github.com/unbalancedparentheses/learning_formal_verification). Lean and TLA+
- [learning_programming_language_theory](https://github.com/unbalancedparentheses/learning_programming_language_theory). Type systems, semantics, compilers
- [learning_systems_and_security](https://github.com/unbalancedparentheses/learning_systems_and_security). Systems and security
- [learning_network_protocols](https://github.com/unbalancedparentheses/learning_network_protocols). Network protocols and RFCs
- [learning_information_theory](https://github.com/unbalancedparentheses/learning_information_theory). Entropy, coding theory, channel capacity
- [learning_mathematics](https://github.com/unbalancedparentheses/learning_mathematics). Mathematics
- [learning_decision_theory](https://github.com/unbalancedparentheses/learning_decision_theory). Rationality under uncertainty, growth-optimal strategies
- [learning_game_theory](https://github.com/unbalancedparentheses/learning_game_theory). Game theory and mechanism design
- [learning_complex_systems](https://github.com/unbalancedparentheses/learning_complex_systems). Emergence, power laws, networks
- [learning_statistical_mechanics](https://github.com/unbalancedparentheses/learning_statistical_mechanics). Statistical mechanics and thermodynamics
- [learning_data_science](https://github.com/unbalancedparentheses/learning_data_science). Data science
- [learning_biology](https://github.com/unbalancedparentheses/learning_biology). Molecular biology, genetics, neuroscience
- [learning_history_and_geopolitics](https://github.com/unbalancedparentheses/learning_history_and_geopolitics). Economic history and grand strategy
- [learning_history_and_philosophy_of_science](https://github.com/unbalancedparentheses/learning_history_and_philosophy_of_science). Epistemology and the history of ideas
- [learning_luxury](https://github.com/unbalancedparentheses/learning_luxury). Philosophy, business strategy, and craft of luxury

</details>

## Writing

- ✍️ [A Proof Is Only as Good as Its Spec](https://federicocarrone.com/articles/formal-verification-moves-trust/)
- ✍️ [At the Core of Finance Lies Geometry. In the End, It's All Jensen's Inequality.](https://federicocarrone.com/series/leptokurtic/at-the-core-of-finance-lies-geometry-in-the-end-its-all-jensens-inequality/)
- ✍️ [The Tail Hedge Debate: Spitznagel Is Right, AQR Is Answering the Wrong Question](https://federicocarrone.com/series/leptokurtic/the-tail-hedge-debate-spitznagel-is-right/)
- ✍️ [Friction as Luxury: What We Lose When AI Gives Us What We Want](https://federicocarrone.com/series/les-circuits-longs/friction-as-luxury/)
- ✍️ [Can I Prove Concrete Programs in Lean?](https://federicocarrone.com/series/concrete/proving-systems-code-in-lean/)
- ✍️ [The Death of the Inner Self](https://federicocarrone.com/series/les-circuits-longs/the-death-of-the-inner-self/)

## Connect

[X](https://x.com/federicocarrone) · [Blog](https://federicocarrone.com) · [Email](mailto:mail@fcarrone.com)
