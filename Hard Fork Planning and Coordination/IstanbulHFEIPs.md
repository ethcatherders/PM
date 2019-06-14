  # Istanbul Hardfork EIPs
 
[EIP 1679](https://eips.ethereum.org/EIPS/eip-1679) is created as the **Istanbul Hardfork** tracking **Meta EIP** .

Below is the list of EIPs proposed so far. We are going to update its status from "Under Consideration" --> "Proposed" -->  "Accepted" or "Rejected" --> "Included" for Istanbul upgrade based on the decision taken by the Core Devs.
 

 №  | EIP  |	Description	| Status |	Client Implementation |	Testnet |	Include in Istanbul HF |        
|---| -----|--------------|------- | -----------------------| --------|----------------------- |
| 1 |[EIP 615](https://eips.ethereum.org/EIPS/eip-615) | Static Jumps and Subroutines (part of EVM Evolution discussion)| Proposed | NA|NA|NA|
| 2 |[EIP 663](https://eips.ethereum.org/EIPS/eip-663) |  Unlimited SWAP and DUP instructions | Proposed | NA|NA|NA| 
| 3 |[EIP 1057](https://eips.ethereum.org/EIPS/eip-1057) | ProgPoW, a Programmatic Proof-of-Work| Proposed. There is a pending audit, above and beyond standard security considerations, that should be evaluated prior to inclusion.| NA|NA|NA|
| 4 |[EIP 1108](https://eips.ethereum.org/EIPS/eip-1108)|Reduce alt_bn128 precompile gas costs| Proposed | NA|NA|NA|
| 5 |[EIP 1109](https://eips.ethereum.org/EIPS/eip-1109)| PRECOMPILEDCALL opcode (Remove CALL costs for precompiled contracts) |Proposed  | NA|NA|NA|
| 6 |[EIP 1283](https://eips.ethereum.org/EIPS/eip-1283) | Net gas metering for SSTORE without dirty maps | Proposed | NA|NA|NA| 
| 7 |[EIP 1344](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1344.md) | ChainID opcode | Proposed.  | NA|NA|NA| 
| 8 |[1352](https://eips.ethereum.org/EIPS/eip-1352)| Specify restricted address range for precompiles/system contracts | Proposed | NA|NA|NA|
| 9 |[EIP 1380](https://eips.ethereum.org/EIPS/eip-1380) | Reduced gas cost for call to self  | Proposed | NA|NA|NA| 
| 10 |[EIP 1559](https://github.com/ethereum/EIPs/issues/1559) | Fee market change.  |Proposed. Participate in discussion at https://ethereum-magicians.org/t/eip-1559-fee-market-change-for-eth-1-0-chain/2783  | NA|NA|NA|
| 11 |[1965](https://eips.ethereum.org/EIPS/eip-1965)| Method to check if a chainID is valid at a specific block Number | Proposed | NA|NA|NA|
| 12 |[EIP 1702](https://eips.ethereum.org/EIPS/eip-1702) | Generalized Account Versioning Scheme | Proposed | NA|NA|NA| 
| 13 |[EIP 1706](https://eips.ethereum.org/EIPS/eip-1706) | Disable SSTORE with gasleft lower than call stipend  | Proposed | NA|NA|NA| 
| 14 |[EIP 1803](https://github.com/ethereum/EIPs/blob/d650a60f347237e0b626c40c5fe5805d80859520/EIPS/eip-1803.md) |  Rename opcodes for clarity | Proposed | NA|NA|NA| 
| 15 |[EIP 1829](https://eips.ethereum.org/EIPS/eip-1829)| Precompile for Elliptic Curve Linear Combinations| Proposed | NA|NA|NA|
| 16 |[EIP 1884](https://github.com/holiman/EIPs/blob/reprice/EIPS/eip-1884.md) | Opcode repricing for trie-size-dependent opcodes | Proposed. participate in discussion at https://ethereum-magicians.org/t/opcode-repricing/3024 | NA|NA|NA|
| 17 |[EIP 1930](https://eips.ethereum.org/EIPS/eip-1930)| CALLs with strict gas semantic. Revert if not enough gas available. | Proposed | NA|NA|NA|
| 18 |[EIP 1985](https://eips.ethereum.org/EIPS/eip-1985)| Sane limits for certain EVM parameters | Proposed | NA|NA|NA|
| 19 |[EIP 1959](https://eips.ethereum.org/EIPS/eip-1959)| New Opcode to check if a chainID is part of the history of chainIDs | Proposed | NA|NA|NA|
| 20 |[EIP-1962](https://eips.ethereum.org/EIPS/eip-1962)|EC arithmetic and pairings with runtime definitions, replaces EIP-1829  | Proposed | NA|NA|NA|
| 21 |[EIP-2014](https://eips.ethereum.org/EIPS/eip-2014)| Extended State Oracle | Proposed | NA|NA|NA|
| 22 |[EIP-2026](https://eips.ethereum.org/EIPS/eip-2026)| State Rent H - Fixed Prepayment for accounts | Proposed | NA|NA|NA|
| 23 |[EIP-2027](https://eips.ethereum.org/EIPS/eip-2027)| State Rent C - Net contract size accounting | Proposed | NA|NA|NA|
| 24 |[EIP-2028](https://eips.ethereum.org/EIPS/eip-2028)| Calldata gas cost reduction | Proposed | NA|NA|NA|
| 25 |[EIP-2029](https://eips.ethereum.org/EIPS/eip-2029)| State Rent A - State counters contract, requirement of EIP-2031 | Proposed | NA|NA|NA|
| 26 |[EIP-2031](https://eips.ethereum.org/EIPS/eip-2031)| State Rent B - Net transaction counter | Proposed | NA|NA|NA|
| 27 |[EIP-2035](https://eips.ethereum.org/EIPS/eip-2035)| Stateless Clients - Repricing SLOAD and SSTORE to pay for block proofs | Proposed | NA|NA|NA|
| 28 |[EIP-2045](https://eips.ethereum.org/EIPS/eip-2045)| Particle gas costs for EVM opcodes | Proposed | NA|NA|NA|
| 29 |[EIP-2046](https://eips.ethereum.org/EIPS/eip-2046)| Reduced gas cost for static calls made to precompiles | Proposed | NA|NA|NA|
| 30 |[EIP 1890](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1890.md) | Commitment to Sustainable Ecosystem Funding | Couldn't make it to EIP 1679 | NA|NA|NA| 
| 31 |[EIP 689](https://eips.ethereum.org/EIPS/eip-689) |  Address Collision of Contract Address Causes Exceptional Halt | Needed champion , couldn't make it to EIP 1679 | NA|NA|NA| 
| 32 |[EIP 665](https://eips.ethereum.org/EIPS/eip-665) | Add precompiled contract for Ed25519 signature verification | EIP 1829 will go forward instead,  couldn't make it to EIP 1679 | NA|NA|NA|
| 33 |[EIP 152](https://github.com/ethereum/EIPs/issues/152) | BLAKE2b `F` Compression Function Precompile  |[champion needed](https://github.com/ethereum-cat-herders/PM/issues/64) , couldn't make it to EIP 1679 | NA|NA|NA|

