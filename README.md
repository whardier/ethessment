# Ethessment

Ethessment is a simple client side client to the etherscan API and several open exchange APIs that will show a current snapshot of your holdings and estimated ethereum, erc20 token, and total value.

Multiple wallets addresses are supported.

# Getting Started

Visit https://whardier.github.io/ethessment/ to get started.  You will be presented an initial form that will generate a URL that you can use, or share, as you wish.

# The URL

Take the following example:
```https://whardier.github.io/ethessment/?KiddoCollegeFund=0x29BBE4a7960fef776C9f1a8a2055Aa551D91a1B9&0xc0FfEEFF79F9C1F2579F0E071b96768c75695fe9```

The first query argument is a Key/Value pair where the key is your personal name for a specific address (```KiddoCollegeFund```) and the value is the address itself (```0x29BBE4a7960fef776C9f1a8a2055Aa551D91a1B9```).

You can also simply list a bare address (```0x29BBE4a7960fef776C9f1a8a2055Aa551D91a1B9```).

Last but not least you can list an optional url fragment which will bring focus to a specific wallet address as well as add it to the avialable wallet list if it isn't already specified (```#0x29BBE4a7960fef776C9f1a8a2055Aa551D91a1B9```).

# Security

Only public keys are in use.

This program only looks at publically available information and will never ask you for a private key.

# Links

Me: https://whardier.github.io/whardier/
