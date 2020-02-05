# Trust Wallet

![](../.gitbook/assets/screen-shot-2020-01-15-at-8.42.26-am.png)

Trust Wallet is a mobile cryptocurrency wallet. Please visit [https://trustwallet.com](https://trustwallet.com) with your mobile device to download the app.

## IMPORTANT DISCLAIMER

Please note that Trust Wallet does not support Harmony's sharded network architecture yet, so **all transactions to or from Trust Wallet must go through shard 0.** You can only view and access your funds in shard 0.

### Incoming transactions

The funds that are sent within shard 0 will be viewed correctly in Trust Wallet.

If you receive funds in a shard other than shard 0 \(i.e. in shard 2\), you will not see the transaction receipt in the Trust Wallet app. Since your account balance will only show the funds in shard 0, your total balance will not change.

### Outgoing transactions

Since there is no shard selection in the Trust Wallet UI, all transactions will originate from shard 0 and will be sent to shard 0.

### **For more details, please see these example cross-shard transactions using Trust Wallet:**

![](../.gitbook/assets/image-34.png)

### What to do if you receive funds in a shard other than shard 0 when using Trust Wallet?

You will need to export the account in which you received the funds and import it to another wallet such as the CLI or Math Wallet.

**Example Using Math Wallet:**

1. Open Trust Wallet app 
2. Click on "Settings" on the bottom right
3. Click on "Wallets" 
4. Click on the info circle next to "Multi-Coin Wallet" 
5. The screen will show backup options, select "show recovery phrase" 
6. Your mnemonic recovery phrase will show up, make sure to note them down accurately and securely 
7. Open Math Wallet Chrome Extension 
8. Click the + sign next to Harmony
9. Select "Import Wallet"
10. Select "Import by mnemonic"
11. Type in your mnemonic that you noted from Trust Wallet, and click next
12. Name your new imported wallet
13. Open "web wallet" from the extension and you can access all your funds in all shards

