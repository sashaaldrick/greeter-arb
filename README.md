# Workshop: Getting to grips with the Arbitrum SDK, 23/04/2024
 
Hey there, fine people. So you wanna learn how to do L1 --> L2 messaging? 

Well, you came to the right place.

Let's get started with:

`git clone https://github.com/sashaaldrick/greeter-arb.git`

`cd greeter-arb`

Then, depending on your JS runtime, you can run the following:

`npm install` or `yarn install` or `bun install` 🥖

After that, you can go ahead and run `exec.js` with:

`npm run greeter` or `yarn run greeter` or `bun run greeter`


You should get something like below if all went well:

```
$ hardhat run scripts/exec.js
WARNING: You are currently using Node.js v21.6.1, which is not supported by Hardhat. This can lead to unexpected behavior. See https://hardhat.org/nodejs-versions


Environmental variables properly set 👍
                            🔵🔵
                           🔵  🔵
                          🔵    🔵
                         🔵      🔵
                        🔵        🔵
                       🔵          🔵
                      🔵            🔵
                     🔵              🔵
                    🔵                🔵
                   🔵                  🔵
                  🔵                    🔵
                 🔵                      🔵
                🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵🔵
               🔵                          🔵
              🔵                            🔵
             🔵                              🔵
            🔵                                🔵
           🔵                                  🔵
          🔵                                    🔵
         🔵                                      🔵
        🔵                                        🔵
       🔵                                          🔵
      🔵                                            🔵
     🔵                                              🔵
    🔵                                                🔵
Arbitrum Demo: Cross-chain Greeter
Lets
Go ➡️
...🚀

Deploying L1 Greeter 👋
deployed to 0xE2A2d36b88061B8366Ec5C83C3fC123d2E30d74f
Deploying L2 Greeter 👋👋
deployed to 0x28332dc28feb99650cB36053C030dD2F77e9C439
Counterpart contract addresses set in both greeters 👍
Current L2 greeting: "Hello world in L2"
Updating greeting from L1 to L2:
Current retryable base submission price is: 52327600
L2 gas price: 147790000
Sending greeting to L2 with 7942741939600 callValue for L2 fees:
Greeting txn confirmed on L1! 🙌 0x93a3824dc9763e00690e35a57cf476b64ea7f96ab12de03c5ff28c55e32a50fb
Waiting for the L2 execution of the transaction. This may take up to 10-15 minutes ⏰
L2 retryable ticket is failed with status FUNDS_DEPOSITED_ON_L2
Updated L2 greeting: "Hello world in L2" 🥳
```
