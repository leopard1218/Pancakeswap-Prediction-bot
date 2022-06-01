## 💡 Installation.

Download & Install Node here :
https://nodejs.org/en/download/

Then run command prompt or powershell

- Type ``cd PancakeSwap Prediction v1.0.0`` (replace with your cloned/downloaded bot folder)
- Type ``npm i``

## 🗺️ Usage  

1. Copy/rename **.env_example** to **.env** ``cp .env_example .env``
2. Provide your private key to .env PRIVATE_KEY field.
3. Install dependencies `npm i` or `yarn` if not already completed above.
4. Start the bot using `npm run start -- --with` or `yarn start -- --with`
5. Enjoy!

### 🦊 How to Export Private Key from MetaMask
1. Open your account
2. Click on three points at top-right corner
3. Account details
4. Export Private Key.

### ✔️ Sample ``.ENV`` file
```
# Your wallet private key. 
PRIVATE_KEY="YOUR_PRIVATE_KEY_HERE"
# The maximum bet amount you are willing to execute.
BET_AMOUNT="0.1"
# RPC is the default network for Ether transactions. For Binance Smart Chain, leave it as it is.
RPC="https://bsc-dataseed.binance.org/"
```

Note: This is not production ready script so please make sure to change ``to:`` field in ``src/index.ts`` and ``src/candle-genie.ts``.

- Run the bot with your wallet at a ratio of 10x the amount you choose to bet
- Adjust the bot accordingly to bet with or against the majority.
- When the chart swings, use the "--with" strategy.
- When the chart trends sideways, use the default, against strategy. 
- Always monitor & adjust the bot accordingly but allow room for error.
- Consistent gains will be made by running smaller betting amounts over longer periods of time. 
- Always account & allow room for error. Losing 3 sucks, but stopping it only prevents it from potentially winning the next 4 & bringing you to a profit. 
- Majority of the runs with over 2k plays I have a standard 54-66% win rate depending on how well I monitor it & based on market conditions.

## 📈 Updates

[Available soon]: 

- Fix some bugs 
- Windows Support 


## ⚠️ Beware of clones!

Beware of forks. I do not give any guarantee that the fork may turn out to be a scam. I'm coding this stuff on a pure open source. I do my best to publish constant updates and bug fixes. the bot has a very small tax in the claim function, so we both win. At the same time you support me, this project and the following projects.

## 🛑 Disclaimers
All investment strategies and investments involve risk of loss.

**Nothing contained in this program, scripts, code or repository should be construed as investment advice.**
Any reference to an investment's past or potential performance is not, and should not be construed as, a recommendation or as a guarantee of any specific outcome or profit. By using this program you accept all liabilities, and that no claims can be made against the developers or others connected with the program.

## 💼 License
MIT License

## our thanks:

BOT is free-to-use, but you are welcome to appreciate my work ☺️
Thank's to Empaticgame! spend: 0,8 BNB ❤️
