# tree-sitter
":1,"tokenId":"_","balance":"10176","tokenName":"trx","tokenDecimal":6,"tokenAbbr":"trx","tokenCanShow":1,"tokenType":"trc10","vip":false,"tokenLogo":"https://static.tronscan.org/production/logo/trx.png"}],"unfreezeV2":0,"feedbackRisk":false,"voteTotal":20,"totalFrozen":0,"latest_operation_time":1694077236000,"frozenForBandWidth":0,"reward":0,"addressTagLogo":"","address":"THQ9BUpHecJdtzojsSLtorSR11qL2zV2Wm","frozen_supply":[],"bandwidth":{"energyRemaining":0,"totalEnergyLimit":90000000000,"totalEnergyWeight":5354911065,"netUsed":0,"storageLimit":0,"storagePercentage":0.0,"assets":{"1004920":{"netPercentage":0.0,"netLimit":1,"netRemaining":1,"netUsed":0},"1004952":{"netPercentage":0.0,"netLimit":0,"netRemaining":0,"netUsed":0},"1004917":{"netPercentage":0.0,"netLimit":0,"netRemaining":0,"netUsed":0},"1004935":{"netPercentage":0.0,"netLimit":0,"netRemaining":0,"netUsed":0}},"netPercentage":0.0,"storageUsed":0,"storageRemaining":0,"freeNetLimit":600,"energyUsed":0,"freeNetRemaining":201,"netLimit":20,"netRemaining":20,"energyLimit":0,"freeNetUsed":399,"totalNetWeight":41259219699,"freeNetPercentage":0.665,"energyPercentage":0.0,"totalNetLimit":43200000000},"date_created":1682231847000,"acquiredDelegatedFrozenV2BalanceForEnergy":0,"accountResource":{"frozen_balance_for_energy":{}},"blueTag":"","witness":0,"freezing":20000000,"delegateFrozenForBandWidth":0,"activated":true,
[![CICD badge]][CICD]
[![DOI](https://zenodo.org/badge/14164618.svg)](https://zenodo.org/badge/latestdoi/14164618)

[CICD badge]: https://github.com/tree-sitter/tree-sitter/actions/workflows/CICD.yml/badge.svg
[CICD]: https://github.com/tree-sitter/tree-sitter/actions/workflows/CICD.yml

Tree-sitter is a parser generator tool and an incremental parsing library. It can build a concrete syntax tree for a source file and efficiently update the syntax tree as the source file is edited. Tree-sitter aims to be:

- **General** enough to parse any programming language
- **Fast** enough to parse on every keystroke in a text editor
- **Robust** enough to provide useful results even in the presence of syntax errors
- **Dependency-free** so that the runtime library (which is written in pure C) can be embedded in any application

## Links

- [Documentation](https://tree-sitter.github.io)
- [Rust binding](lib/binding_rust/README.md)
- [WASM binding](lib/binding_web/README.md)
- [Command-line interface](cli/README.md)
