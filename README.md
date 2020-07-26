# Multi-Token-Walllet-

Problem:
Previously in Ethereum Network, additional tools were required in order to transfer many ERC20 tokens at once. Many people still do this manually, one transaction at a time. This process is time consuming and prone to an error.

Solution:
This Dapp allows a user to send thousands of token transfers in a very effecient way by batching them in groups of 145 token transfers per Ethereum transaction. This automation saves time by automatically generating transactions to MetaMask. Finally, this tool allows a user to maintain security of their account by delegating the trust of their private keys to a secure MetaMask wallet.

Example JSON:

[
  {"0xDSA018De6b2b6F89d84A1F5A68953f07554765e":"12"},
  {"0xdRdsf0bd230867c870eF13631D7EFf1AE8Ab85c9":"1123.45645"},
  {"0x9ygd28905DEA1a67940093fFeaCeee58cA91Ae":"1.049"},
  {"0xstf9F38bAf0dE21E1fee5AC4648Bc885c1d774":"14546"}
]
Example CSV:

0xDSA018De6b2b6F89d84A1F5A68953f07554765e,12
0xdRdsf0bd230867c870eF13631D7EFf1AE8Ab85c9,1123.45645
0x9ygd28905DEA1a67940093fFeaCeee58cA91Ae,1.049
0x00fC79F38bAf0dE21E1fee5AC4648Bc885c1d774,14546


Proof of work:
https://ropsten.etherscan.io/tx/0xd5fd9873b5a21b39b339ef6397d4b0a3256fb2e17e866a18ce79f0ef3746e0b1



