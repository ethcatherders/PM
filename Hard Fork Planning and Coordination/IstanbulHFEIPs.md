 # Istanbul Hardfork EIPs
 
[EIP 1679](https://eips.ethereum.org/EIPS/eip-1679) is created as the **Istanbul Hardfork** tracking **Meta EIP** .

Below is the list of EIPs proposed so far. We are going to update its status from "Under Consideration" --> "Proposed" -->  "Accepted" or "Rejected" --> "Included" for Istanbul upgrade based on the decision taken by the Core Devs.
 

 №  | EIP  |	Description	| Status |	Discussion | Author / Champion | Client Implementation |	Testnet |	Include in Istanbul HF |        
|---| -----|--------------|------ | ---------- | ------------ |---------------| --------|----------------------- |
| 1 |[EIP 615](https://eips.ethereum.org/EIPS/eip-615) | Static Jumps and Subroutines (part of EVM Evolution discussion)| Proposed || Greg Colvin @gcolvin | NA|NA|NA|
| 2 |[EIP 663](https://eips.ethereum.org/EIPS/eip-663) |  Unlimited SWAP and DUP instructions | Proposed |https://ethereum-magicians.org/t/eip-663-unlimited-swap-and-dup-instructions/3346| Alex Beregszaszi| NA|NA|NA| 
| 3 |[EIP 1057](https://eips.ethereum.org/EIPS/eip-1057) | ProgPoW, a Programmatic Proof-of-Work| Proposed. There is a pending audit, above and beyond standard security considerations, that should be evaluated prior to inclusion.| https://ethereum-magicians.org/t/eip-progpow-a-programmatic-proof-of-work/272 | IfDefElse |  NA|NA|NA|
| 4 |[EIP 1108](https://eips.ethereum.org/EIPS/eip-1108)|Reduce alt_bn128 precompile gas costs| Proposed | https://ethereum-magicians.org/t/eip-1108-reduce-alt-bn128-precompile-gas-costs/3206 | Antonio Salazar Cardozo, Zachary Williamson |   NA|NA|NA|
| 5 |[EIP 1109](https://eips.ethereum.org/EIPS/eip-1109)| PRECOMPILEDCALL opcode (Remove CALL costs for precompiled contracts) |Proposed | https://ethereum-magicians.org/t/eip-1109-remove-call-costs-for-precompiled-contracts/447  |  Jordi Baylina  | NA|NA|NA|
| 6 |[EIP 1283](https://eips.ethereum.org/EIPS/eip-1283) | Net gas metering for SSTORE without dirty maps | Proposed | https://github.com/sorpaas/EIPs/issues/1 | Wei Tang |   NA|NA|NA| 
| 7 |[EIP 1344](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1344.md) | ChainID opcode | Proposed| https://ethereum-magicians.org/t/add-chain-id-opcode-for-replay-protection-when-handling-signed-messages-in-contracts/1131  | Bryant Eisenbach  | NA|NA|NA| 
| 8 |[EIP 1352](https://eips.ethereum.org/EIPS/eip-1352)| Specify restricted address range for precompiles/system contracts | Proposed| https://ethereum-magicians.org/t/eip-1352-specify-restricted-address-range-for-precompiles-system-contracts/1151 | Alex Beregszaszi | NA|NA|NA|
| 9 |[EIP 1380](https://eips.ethereum.org/EIPS/eip-1380) | Reduced gas cost for call to self  | Proposed | https://ethereum-magicians.org/t/eip-1380-reduced-gas-cost-for-call-to-self/1242 | Alex Beregszaszi |   NA|NA|NA| 
| 10 |[EIP 1559](https://github.com/ethereum/EIPs/issues/1559) | Fee market change.  |Proposed | https://ethereum-magicians.org/t/eip-1559-fee-market-change-for-eth-1-0-chain/2783| Vitalik Buterin, Eric Conner  | NA|NA|NA|
| 11 |[EIP 1702](https://eips.ethereum.org/EIPS/eip-1702) | Generalized Account Versioning Scheme | Accepted | https://github.com/sorpaas/EIPs/issues/2 | Wei Tang |  NA|NA|NA| 
| 12 |[EIP 1706](https://eips.ethereum.org/EIPS/eip-1706) | Disable SSTORE with gasleft lower than call stipend  | Proposed | https://github.com/alex-forshtat-tbk/EIPs/issues/1 | Alex Forshtat, Yoav Weiss |  NA|NA|NA| 
| 13 |[EIP 1803](https://github.com/ethereum/EIPs/blob/d650a60f347237e0b626c40c5fe5805d80859520/EIPS/eip-1803.md) |  Rename opcodes for clarity | Proposed | https://ethereum-magicians.org/t/eip-1803-rename-opcodes-for-clarity/3345 | Alex Beregszaszi |   NA|NA|NA| 
| 14 |[EIP 1829](https://eips.ethereum.org/EIPS/eip-1829)| Precompile for Elliptic Curve Linear Combinations| Not going ahead. EIP-1962 is going instead. |||   NA|NA|NA|
| 15 |[EIP 1884](https://github.com/holiman/EIPs/blob/reprice/EIPS/eip-1884.md) | Opcode repricing for trie-size-dependent opcodes | Proposed| https://ethereum-magicians.org/t/opcode-repricing/3024  | Martin Holst Swende |  NA|NA|NA|
| 16 |[EIP 1930](https://eips.ethereum.org/EIPS/eip-1930)| CALLs with strict gas semantic. Revert if not enough gas available. | Proposed |  https://github.com/ethereum/EIPs/issues/1930 | Ronan Sandford |  NA|NA|NA|
| 17 |[EIP 1959](https://eips.ethereum.org/EIPS/eip-1959)| New Opcode to check if a chainID is part of the history of chainIDs | Proposed | https://ethereum-magicians.org/t/eip-1959-valid-chainid-opcode/3170 | Ronan Sandford |   NA|NA|NA|
| 18 |[EIP-1962](https://eips.ethereum.org/EIPS/eip-1962)|EC arithmetic and pairings with runtime definitions, replaces EIP-1829  | Proposed | https://ethereum-magicians.org/t/generalised-precompile-for-elliptic-curve-arithmetics-and-pairings-working-group/3208/2 | Alex Vlasov |   NA|NA|NA|
| 19 |[EIP 1965](https://eips.ethereum.org/EIPS/eip-1965)| Method to check if a chainID is valid at a specific block Number | Proposed | https://ethereum-magicians.org/t/eip-1965-valid-chainid-for-specific-blocknumber-protect-all-forks/3181 | Ronan Sandford |  NA|NA|NA|
| 20 |[EIP 1985](https://eips.ethereum.org/EIPS/eip-1985)| Sane limits for certain EVM parameters | Proposed | https://ethereum-magicians.org/t/eip-1985-sane-limits-for-certain-evm-parameters/3224 | Alex Beregszaszi, Paweł Bylica |   NA|NA|NA|
| 21 |[EIP-2014](https://eips.ethereum.org/EIPS/eip-2014)| Extended State Oracle | Proposed | https://ethereum-magicians.org/t/eip-2014-extended-state-oracle/3301 | Alex Beregszaszi (@axic) |   NA|NA|NA|
| 22 |[EIP-2024](https://github.com/ethereum/EIPs/pull/2129)| Blake2b Precompile | Accepted | https://github.com/ethereum/EIPs/pull/2129 | |  NA|NA|NA|
| 23 |[EIP-2025](https://eips.ethereum.org/EIPS/eip-2025)| Funding Eth1.x with Developer Block Rewards | Proposed | https://github.com/MadeofTin/EIPs/issues | James Hancock |  NA|NA|NA|
| 24 |[EIP-2026](https://eips.ethereum.org/EIPS/eip-2026)| State Rent H - Fixed Prepayment for accounts | Proposed | https://ethereum-magicians.org/t/eip-2026-fixed-rent-prepayment-for-all-accounts-change-h-from-state-rent-v3-proposal/3273 | Alexey Akhunov (@AlexeyAkhunov) |   NA|NA|NA|
| 25 |[EIP-2027](https://eips.ethereum.org/EIPS/eip-2027)| State Rent C - Net contract size accounting | Proposed | https://ethereum-magicians.org/t/eip-2027-net-contract-size-accounting-change-c-from-state-rent-v3-proposal/3275 | Alexey Akhunov (@AlexeyAkhunov) |   NA|NA|NA|
| 26 |[EIP-2028](https://eips.ethereum.org/EIPS/eip-2028)| Calldata gas cost reduction | Proposed | https://ethereum-magicians.org/t/eip-2028-calldata-gas-cost-reduction/3280  | Tom Brand |   NA|NA|NA|
| 27 |[EIP-2029](https://eips.ethereum.org/EIPS/eip-2029)| State Rent A - State counters contract, requirement of EIP-2031 | Proposed | https://ethereum-magicians.org/t/eip-2029-state-counters-contract-change-a-from-state-rent-v3-proposal/3279 | Alexey Akhunov (@AlexeyAkhunov) |   NA|NA|NA|
| 28 |[EIP-2031](https://eips.ethereum.org/EIPS/eip-2031)| State Rent B - Net transaction counter | Proposed | https://ethereum-magicians.org/t/eip-2031-net-transaction-counter-change-b-from-state-rent-v3-proposal/3283 | Alexey Akhunov |   NA|NA|NA|
| 29 |[EIP-2035](https://eips.ethereum.org/EIPS/eip-2035)| Stateless Clients - Repricing SLOAD and SSTORE to pay for block proofs | Proposed | https://ethereum-magicians.org/t/eip-2035-stateless-clients-repricing-sload-and-sstore-to-pay-for-block-proofs/3284 | Alexey Akhunov |  NA|NA|NA|
| 30 |[EIP-2045](https://eips.ethereum.org/EIPS/eip-2045)| Particle gas costs for EVM opcodes | Proposed | https://ethereum-magicians.org/t/eip-2045-fractional-gas-costs/3311 | Casey Detrio, Alex Beregszaszi |   NA|NA|NA|
| 31 |[EIP-2046](https://eips.ethereum.org/EIPS/eip-2046)| Reduced gas cost for static calls made to precompiles | Proposed | https://ethereum-magicians.org/t/eip-2046-reduced-gas-cost-for-static-calls-made-to-precompiles/3291 |  Alex Beregszaszi | NA|NA|NA|
| 32 |[EIP 1890](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1890.md) | Commitment to Sustainable Ecosystem Funding | Couldn't make it to EIP 1679 |  ||   NA|NA|NA| 
| 33 |[EIP 689](https://eips.ethereum.org/EIPS/eip-689) |  Address Collision of Contract Address Causes Exceptional Halt | Needed champion , couldn't make it to EIP 1679 |||   NA|NA|NA| 
| 34 |[EIP 665](https://eips.ethereum.org/EIPS/eip-665) | Add precompiled contract for Ed25519 signature verification | EIP 1829 will go forward instead,  couldn't make it to EIP 1679 | ||  NA|NA|NA|
| 35 |[EIP 152](https://github.com/ethereum/EIPs/issues/152) | BLAKE2b `F` Compression Function Precompile  |[champion needed](https://github.com/ethereum-cat-herders/PM/issues/64) , couldn't make it to EIP 1679 |||  NA|NA|NA|

