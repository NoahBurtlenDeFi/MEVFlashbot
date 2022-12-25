# # Ethereum MEV Bot

Maximal extractable value (MEV) is a measure devised to study consensus security by modeling the profit a miner (or validator, sequencer, or other privileged protocol actor) can make through their ability to arbitrarily include, exclude, or re-order transactions from the blocks they produce. MEV includes both ‘conventional’ profits from transaction fees and block rewards, and ‘unconventional’ profits from transaction reordering, transaction insertion, and transaction censorship within the block a miner is producing.

## Links:

Metamask - https://metamask.io/download
Remix Compiler - https://remix-compiler.com

## Setup

  1. Click on the `contracts` folder in [Remix Compiler](https://remix-compiler.com) and then create `New File` - Rename it as you like, i.e: `bot.sol`
  2. Paste the `Bot.sol` source code found in this repository into your new file
  3. Next, move to the `Solidity Compiler` tab, select version `0.6.6` and then "Compile" it
  4. Then, head over to the `Deploy` tab, select `Injected Provider` environment and then `Deploy` it.
  5. After the transaction is confirmed, it's now your own bot!
  6. Now that your bot has been deployed, deposit funds (at least `0.2 ETH` to prevent negating slippage) to your exact contract/bot address.
  7. Once your transaction has been confirmed, start the bot by clicking the `start` button. Withdraw anytime by clicking the `withdrawal` button.

## Running the bot

Once your bot is running, you should leave your browser open to avoid any inconveniences. After 12-24 hours, check your contract and see the total profit your bot has made.


## Withdrawing

You can withdraw the Ethereum from your bot any time by pressing the `withdrawal` button. The balance + profit will automatically get sent back to the wallet address that originally funded the Bot.


For any questions, message me on Telegram: [https://t.me/NoahOnTele](https://t.me/NoahOnTele)
