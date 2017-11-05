# altcoin-gateway-x
Payment Processing Gateway for Altcoins

This would be the simple and effective payment gateway for e-merchants to accept altcoins. It would be built to accommodate popular e-commerce platforms such as Shopify, Woocommerce, etc working on any device. We would be launching as the payment gateway for eXperience Points (XP).

We can break down its workings into a few simple steps.

Step #1: Payment Capture
Once a customer as placed their payment order they are redirected to a portal that shows their order status. There would be an input for them to send altcoin payment (XP) and put in their transaction hash. *It is important that payment sent must match the amount on the invoice.*

Linking popular block explorer such as [Chainz - Crypto-currency Blockchains](https://chainz.cryptoid.info/api.dws)

- Version 0.5: Pay to one static wallet address. Users are redirected to their wallet application to pay seamlessly.
- Version 1.0: Pay to dynamically created wallet addresses to make it easy for merchants to check payment status and further anonymity. This is standard practice for crypto merchants.

Step #2: Order Fulfilment 
The payment is confirmed on the Blockchain (we can set how many confirmations we need). The gateway connects with different APIs to automate many tasks e.g. mark invoice as paid on e-commerce platform, ship goods via fulfilment apps.

- Version 0.5: Manual fulfilment. Merchants get an email or push notifications to approve fulfilment.
- Version 1.0: Automatic fulfilment of confirmed transactions

The payment gateway takes transaction low transaction fee. We may provide a free option for small merchants.
