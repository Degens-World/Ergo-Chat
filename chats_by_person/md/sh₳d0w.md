# sh₳d0w

**Total messages:** 15

---

**2023-03-05T15:37:27**

Hello, I am developing a dapp, using react the function that sends to sign the transaction works, but the same function now executed in nextjs throws an error when the extension receives the object, what could it be?

---

**2023-03-05T15:37:52**

when it launches in error it does not open the window

---

**2023-03-05T18:25:37**

I already got it to open the window, but it stays like that

---

**2023-03-05T18:36:23**

yeah, i'm using fleetjs

---

**2023-03-05T18:37:40**

I would appreciate it when you remember haha

---

**2023-03-05T18:48:23**

try{


        const unsignedTransaction = new TransactionBuilder(currentHeight)
            .from(inputs)
            .to(new OutputBuilder(amountToSend, receiverAddress)
                .addTokens([
                    {tokenId: TOKEN_ID, amount: tokenAmountToSend}
                ])
                 .setAdditionalRegisters({
                    R4: SConstant(SColl(SByte, Buffer.from(btcAddress, "utf-8"))),
                })
            )
            .sendChangeTo(nautilusAddress).payMinFee(fee)
            .build("EIP-12")
            .toPlainObject();



        let signedTransaction = await ergo.sign_tx(unsignedTransaction)

        let outputZeroBoxId = signedTransaction.outputs[0].boxId;
        let txInfo = await ergo.submit_tx(signedTransaction)

        result = txInfo





    }catch(e){
        console.log("error", e)
        result = ''
    }


    return result

---

**2023-03-05T18:48:39**

is running on nextjs

---

**2023-03-05T18:49:23**

the same code with react works

---

**2023-03-05T18:51:14**

if i remove it i get that error

---

**2023-03-05T18:57:45**

does the same

---

**2023-03-05T19:05:32**

I fixed it

---

**2023-03-05T19:06:23**

I had to use .toEIP12Object(); instead of .toPlainObject();

---

**2023-03-05T19:19:35**

use this structure

---

**2023-03-05T19:20:22**

https://fleet-sdk.github.io/docs/transaction-building

---

**2023-03-05T19:20:44**

is the official github

---

