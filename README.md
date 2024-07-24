
# Taiko BCR Protocol Bug Bounty Program

## Overview

Welcome to the Taiko BCR Protocol Bug Bounty Program. We appreciate the efforts of security researchers and developers who help us maintain the security and integrity of the Taiko ecosystem. This program is designed to reward individuals who identify and report vulnerabilities in the Taiko BCR Protocol.


## About Taiko BCR Protocol

The Taiko BCR (Based Contestable Rollup) Protocol is a configurable, multi-proof rollup system that allows for efficient and secure scaling of decentralized applications. It leverages zkRollups and Optimistic Rollups to ensure security and scalability.

For detailed information, please refer to the following resources:
- [Taiko BCR Protocol Overview](https://taiko.mirror.xyz/Z4I5ZhreGkyfdaL5I9P0Rj0DNX4zaWFmcws-0CVMJ2A)
- [Taiko BCR Contracts on GitHub](https://github.com/taikoxyz/taiko-mono/tree/main/packages/protocol)

## Scope

### In-Scope

The following components are in scope for this bug bounty program:

1. **[BCR Contracts](https://github.com/taikoxyz/taiko-mono/tree/main/packages/protocol)**

### Out-of-Scope

The following components are out of scope:

- User applications built on top of the Taiko BCR Protocol.
- Third-party dependencies and services.
- Social engineering attacks against Taiko employees or contractors.

## Severity and Reward Classification

### Smart Contract

- **Critical:** 50,000 - 100,000 TKO tokens
- **High:** 25,000 - 50,000 TKO tokens
- **Medium:** 10,000 - 25,000 TKO tokens
- **Low:** 5,000 - 10,000 TKO tokens

## Impact and Scope

### In-Scope Impacts


| Severity | Impact Description |
| -------- | ------------------ |
| **Critical** | Direct theft of any user funds, whether at-rest or in-motion, other than unclaimed yield |
| **Critical** | Permanent freezing of funds |
| **Critical** | Protocol Insolvency |
| **High** | Temporary freezing of funds |
| **Medium** | Smart contract unable to operate due to lack of token funds |
| **Medium** | Block stuffing for profit |
| **Medium** | Griefing (e.g., no profit motive for an attacker, but damage to the users or the protocol) |
| **Medium** | Theft of gas |
| **Medium** | Unbounded gas consumption |
| **Low** | Contract fails to deliver promised returns, but doesn't lose value |


### Out-of-Scope Impacts

These impacts are out of scope for this bug bounty program.

#### All Categories:

- Impacts requiring attacks that the reporter has already exploited themselves, leading to damage
- Impacts caused by attacks requiring access to leaked keys/credentials
- Impacts caused by attacks requiring access to privileged addresses (governance, strategist) except in such cases where the contracts are intended to have no privileged access to functions that make the attack possible
- Impacts relying on attacks involving the depegging of an external stablecoin where the attacker does not directly cause the depegging due to a bug in code
- Mentions of secrets, access tokens, API keys, private keys, etc. in Github will be considered out of scope without proof that they are in-use in production
- Best practice recommendations
- Feature requests
- Impacts on test files and configuration files unless stated otherwise in the bug bounty program

#### Smart Contract Specific:

- Incorrect data supplied by third party oracles
- Not to exclude oracle manipulation/flash loan attacks
- Impacts requiring basic economic and governance attacks (e.g. 51% attack)
- Lack of liquidity impacts
- Impacts from Sybil attacks
- Impacts involving centralization risks

## Previous Audits
Taiko's completed audit reports can be found [here](https://github.com/taikoxyz/taiko-mono/tree/main/packages/protocol/audit). Any unfixed vulnerabilities mentioned in these reports are not eligible for a reward.


## Submission Guidelines

1. **Proof of Concept (POC):** Submissions must include a proof of concept (POC) demonstrating the vulnerability. The POC should include step-by-step instructions to reproduce the issue. All web and app bug reports must come with a POC. All bug reports submitted without POC will be rejected with instructions to provide POC.
2. **Detailed Report:** Submissions must include a detailed report outlining the vulnerability, its impact, and potential mitigation strategies.
3. **Restrictions:**
   - Do not perform any tests that could disrupt the network or services.
   - No testing on mainnet or public testnet deployed code; all testing should be done on local-forks of either public testnet or mainnet.
   - No testing with pricing oracles or third-party smart contracts.
   - No phishing or other social engineering attacks against our employees and/or customers.
   - No testing with third-party systems and applications.
   - No denial of service attacks that are executed against project assets.
   - No public disclosure of an unpatched vulnerability in an embargoed bounty.
   - No actions prohibited by the Taiko Rules.

## Budget

- **Total Budget:** 1,000,000 TKO tokens.
- **Reward per Valid Bug:** 50,000 - 100,000 TKO tokens.
- **Additional Notes:** The program is ongoing and auto-renewed. We will top up more TKO tokens if some have been rewarded to participants.


## Submission Process

- **Email for Submission:** All bug reports must be submitted via email to [security@taiko.xyz](mailto:security@taiko.xyz).
- **Disclosure Policy:** Disclosure of these bugs before we fix them will disqualify the reporters from receiving any reward.

## Resources

- [BCR Protocol Whitepaper](https://taiko.mirror.xyz/Z4I5ZhreGkyfdaL5I9P0Rj0DNX4zaWFmcws-0CVMJ2A)
- [GitHub Repository](https://github.com/taikoxyz/taiko-mono/tree/main/packages/protocol)
- [Documentation](https://docs.taiko.xyz)


## Legal

By participating in this program, you agree to comply with all applicable local and international laws. 