# zhang zee

**Total messages:** 88

---

**2022-06-13T18:02:42**

hello, could anyone here help me ?I was wondering where can I test or debug my ergoscripts program?

---

**2022-06-13T19:03:12**

thank you sir

---

**2022-06-15T19:34:41**

is there any chinese developer here? need help with my ergoscript low-level question.can't properly describe them in english😂

---

**2022-06-15T22:50:38**

ok, In the ergoscript paper, the example of atomic exchange on a single blockchain. I think alice is the seller sells the token in exchange for ergo ,and bob is the buyer,but to in alice script,output is 60L token,while in bob script, output is 100 ergo. so when we sign the transaction with the two box as inputs,alice still get his token back,bob get 100ergo back ? do I misunderstand,or it's wrong in the paper?

---

**2022-06-15T22:56:17**

another question is propositionbytes of a box ,I don't know If I understand the right way. if the box is only belong to a individual,which can be described PK. the box propositionbytes is more like a property to tell whose box it is ,in which case box.propositionbytes== pk.propbytes?

---

**2022-06-15T22:58:52**

and the emission contract, does the genesis box have to be signed at every block? it's signed onchain or offchain?

---

**2022-06-15T23:00:29**

sorry to bring so many trivial questions

---

**2022-09-02T06:11:41**

19:11:03.689 INFO  [ctor.default-dispatcher-5] s.c.n.NetworkController - Connecting to peer: PeerInfo(PeerSpec(unknown,0.0.1,unknown-/37.156.20.158:9020,Some(/37.156.20.158:9020),Vector()),0,None)
19:11:04.067 INFO  [ctor.default-dispatcher-5] s.c.n.NetworkController - Failed to connect to : /37.156.20.158:9020
java.net.ConnectException: Connection refused
  at java.base/sun.nio.ch.SocketChannelImpl.checkConnect(Native Method)
  at java.base/sun.nio.ch.SocketChannelImpl.finishConnect(SocketChannelImpl.java:777)
  at akka.io.TcpOutgoingConnection$$anonfun$connecting$1.$anonfun$applyOrElse$4(TcpOutgoingConnection.scala:111)
  at akka.io.TcpOutgoingConnection.akka$io$TcpOutgoingConnection$$reportConnectFailure(TcpOutgoingConnection.scala:53)
  at akka.io.TcpOutgoingConnection$$anonfun$connecting$1.applyOrElse(TcpOutgoingConnection.scala:111)
  at akka.actor.Actor.aroundReceive(Actor.scala:537)
  at akka.actor.Actor.aroundReceive$(Actor.scala:535)
  at akka.io.TcpConnection.aroundReceive(TcpConnection.scala:33)
  at akka.actor.ActorCell.receiveMessage(ActorCell.scala:577)
  at akka.actor.ActorCell.invoke(ActorCell.scala:547)
  at akka.dispatch.Mailbox.processMailbox(Mailbox.scala:270)
  at akka.dispatch.Mailbox.run(Mailbox.scala:231)
  at akka.dispatch.Mailbox.exec(Mailbox.scala:243)
  at java.base/java.util.concurrent.ForkJoinTask.doExec(ForkJoinTask.java:290)
  at java.base/java.util.concurrent.ForkJoinPool$WorkQueue.topLevelExec(ForkJoinPool.java:1020)
  at java.base/java.util.concurrent.ForkJoinPool.scan(ForkJoinPool.java:1656)
  at java.base/java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1594)
  at java.base/java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:183)
19:11:08.710 INFO  [ctor.default-dispatcher-5] s.c.n.NetworkController - Connecting to peer: PeerInfo(PeerSpec(unknown,0.0.1,unknown-/213.239.193.208:9020,Some(/213.239.193.208:9020),Vector()),0,None)
19:11:09.055 INFO  [ctor.default-dispatcher-5] s.c.n.NetworkController - Failed to connect to : /213.239.193.208:9020

---

**2022-09-02T06:11:58**

trying to setup a ergo testnet node locally

---

**2022-09-02T06:12:07**

has anyone met this problem?

---

**2022-09-02T06:12:34**

ping the peers seems ok

---

**2022-09-02T06:13:11**

4.0.41

---

**2022-09-02T06:13:54**

I use openjdk-11-jre

---

**2022-09-02T06:14:00**

would this be ok?

---

**2022-09-02T06:14:14**

thank you

---

**2022-09-02T06:14:50**

this version?

---

**2022-09-02T06:19:20**

also if I need to revise the peers port to 9021?

---

**2022-09-02T06:22:57**

but I don't know why they still connect 9020 after I change the port to 9021

---

**2022-09-02T06:27:21**

ok it's my wrongdoing

---

**2022-09-02T19:55:37**

can someone good heart sends me some testnet ergo

---

**2022-09-02T19:55:39**

3Wyo9cARuCzq5VpyrKUaVqNbYSRqMnM3JbqimaVUBcUCh4q5arBw

---

**2022-09-02T19:55:53**

i have trouble using ergofaucet because network

---

**2022-09-03T02:45:00**

😭😭

---

**2022-09-03T03:55:59**

+8

---

**2022-09-03T03:56:21**

beijing time

---

**2022-09-03T03:58:30**

and my local testnet node stuck here

---

**2022-09-03T03:58:51**

won't download the block infomation

---

**2022-09-03T04:27:03**

last valid date is 31.8.2022

---

**2022-09-03T04:27:27**

🤣no wonder I can not see the ergs you sent me

---

**2022-09-03T06:53:51**

frustrating

---

**2022-09-03T12:45:56**

mine is stucked

---

**2022-09-03T12:46:04**

testnet node

---

**2022-09-03T12:47:27**

your testnet?

---

**2022-09-03T12:47:50**

noice

---

**2022-09-03T12:49:19**

how can i use nautilus to connect ？

---

**2022-09-03T12:50:27**

im using nautilus testnet version

---

**2022-09-03T12:52:09**

ok  i need to do some research

---

**2022-09-03T12:53:34**

is this okay to use official testnet keys in your testnet

---

**2022-09-03T12:54:29**

okay address compatible

---

**2022-09-03T12:55:24**

but i see testnet address and mainnet address quite different at begining letters

---

**2022-09-03T12:56:26**

mainnet address starts with 9h,9i

---

**2022-09-03T12:56:40**

testnet does not

---

**2022-09-03T12:59:32**

i will sync your node tommorow,thank you very much.

---

**2022-09-03T20:50:06**

how to mine on your own node?

---

**2022-09-03T20:51:44**

your node work functionally MGpai

---

**2022-09-03T22:03:16**

3Wyo9cARuCzq5VpyrKUaVqNbYSRqMnM3JbqimaVUBcUCh4q5arBw

---

**2022-09-03T22:03:32**

mgpai ,would you send me some ergs on your testnet?

---

**2022-09-03T22:04:36**

I failed setuping my mining server😢

---

**2022-09-03T22:28:48**

3WwJVzygjrKvdKGDUZSyZdemuK5F4xiQQFtauuHyd59tsC3k1bYp

---

**2022-09-03T22:28:54**

mgpai this address

---

**2022-09-03T22:28:58**

plz

---

**2022-09-04T04:36:09**

MGpai.  sir ,where to find  my address?

---

**2022-09-04T04:39:06**

my testnet address seems not the right form on your testnet

---

**2022-09-04T04:39:23**

my official testnet one

---

**2022-09-04T05:26:52**

what contract you are sending to?

---

**2022-09-04T05:27:21**

you means the erg along with comet?

---

**2022-09-12T01:00:47**

how to refer to oracle pools? the box have pool nft  has the current price?

---

**2022-09-12T01:02:44**

{"items":[{"boxId":"58e24ddfaa693cd93969eb138bf6d33e43075545ef68519d90d3744b024b722e","transactionId":"2ad78306c714b047cd35b00b882e2450fa67fac5f65c76004e820ca8ba9f0bce","blockId":"bf64cc2825c351ac9b5a4b194f229cbeab96fe3442ce36f7d3fba402193f8cb9","value":6971000000,"index":0,"globalIndex":21521871,"creationHeight":836715,"settlementHeight":836717,"ergoTree":"1014040004000e208c27dd9d8a35aac1e3167d58858c0a8b4059b277da790552e37eba22df9b903504000400040204020101040205a0c21e040204080500040c040204a0c21e0402050a05c8010402d806d601b2a5730000d602b5db6501fed9010263ed93e4c67202050ec5a7938cb2db63087202730100017302d603b17202d604e4c6b272027303000605d605d90105049590720573047204e4c6b272029972057305000605d606b07202860273067307d901063c400163d803d6088c720601d6098c720801d60a8c72060286029a72097308ededed8c72080293c2b2a5720900d0cde4c6720a040792c1b2a5720900730992da720501997209730ae4c6720a0605ea02d1ededededededed93cbc27201e4c6a7060e927203730b93db63087201db6308a793e4c6720104059db07202730cd9010741639a8c720701e4c68c72070206057e72030593e4c6720105049ae4c6a70504730d92c1720199c1a77e9c9a7203730e730f058c72060292da720501998c72060173109972049d9c720473117312b2ad7202d9010763cde4c672070407e4c6b2a5731300040400","address":"NTkuk55NdwCXkF1e2nCABxq7bHjtinX3wH13zYPZ6qYT71dCoZBe1gZkh9FAr7GeHo2EpFoibzpNQmoi89atUjKRrhZEYrTapdtXrWU4kq319oY7BEWmtmRU9cMohX69XMuxJjJP5hRM8WQLfFnffbjshhEP3ck9CKVEkFRw1JDYkqVke2JVqoMED5yxLVkScbBUiJJLWq9BSbE1JJmmreNVskmWNxWE6V7ksKPxFMoqh1SVePh3UWAaBgGQRZ7TWf4dTBF5KMVHmRXzmQqEu2Fz2yeSLy23sM3pfqa78VuvoFHnTFXYFFxn3DNttxwq3EU3Zv25SmgrWjLKiZjFcEcqGgH6DJ9FZ1DfucVtTXwyDJutY3ksUBaEStRxoUQyRu4EhDobixL3PUWRcxaRJ8JKA9b64ALErGepRHkAoVmS8DaE6VbroskyMuhkTo7LbrzhTyJbqKurEzoEfhYxus7bMpLTePgKcktgRRyB7MjVxjSpxWzZedvzbjzZaHLZLkWZESk1WtdM25My33wtVLNXiTvficEUbjA23sNd24pv1YQ72nY1aqUHa2","assets":[{"tokenId":"011d3364de07e5a26f0c4eef0852cddb387039a921b7154ef3cab22c6eda887f","index":0,"amount":1,"name":"ERGUSD-NFT","decimals":0,"type":"EIP-004"}],"additionalRegisters":{"R4":{"serializedValue":"058cae88e301","sigmaType":"SLong","renderedValue":"238095238"},"R5":{"serializedValue":"04e69166","sigmaType":"SInt","renderedValue":"836723"},"R6":{"serializedValue":"0e20f7ef73c4a4ab91b84bb0a2905108d534114472ec057be3a57a9dfc9b1fbd85c1","sigmaType":"Coll[SByte]","renderedValue":"f7ef73c4a4ab91b84bb0a2905108d534114472ec057be3a57a9dfc9b1fbd85c1"}},"spentTransactionId":null,"mainChain":true}],"total":1}

---

**2022-09-12T01:02:50**

current price is 4.2

---

**2022-09-12T01:03:04**

which register store?

---

**2022-09-12T01:03:13**

R4?

---

**2022-09-12T01:04:02**

but it's rendered value is not even close

---

**2022-09-12T01:13:42**

thankyou sir ,specifically  r4 is the price?

---

**2022-09-12T02:14:02**

thank you very much

---

**2022-09-12T05:32:21**

hello, using appkit to mint token,how to get tokenId?

---

**2022-09-12T05:35:58**

the example in ergodoc or elsewhere?

---

**2022-09-12T06:08:57**

thanks,sir,  that works

---

**2022-09-16T02:10:45**

how to use fold in ergoscript if I have A = [1,2,3,4,5],I want to sum them all

---

**2022-09-16T02:11:10**

trivial question,but needs your help,plz

---

**2022-09-16T02:15:13**

is fold function here kind of same to reduce function?

---

**2022-09-16T02:16:13**

thank you very  much ,cheese

---

**2022-09-16T02:57:01**

by the way ,is there any ocacle build documents? is it possible to build a match results feed oracle, where I can get the footballs matches result onchain.

---

**2022-09-16T02:57:28**

just asking for curiosity

---

**2022-09-16T05:20:57**

thank you greenhat. very helpful

---

**2022-10-03T21:22:33**

mgpai,goodwork

---

**2022-11-30T20:34:05**

so when the smartcontract was deployed onchain,it was digested to an address or something, there's no way to review the ergoscript except for the developer reveals their code?

---

**2022-11-30T20:34:36**

through the information that expolorer provides

---

**2022-11-30T21:00:26**

thankyou could  you show a simple example of ergotree to figure out what's going on?for example pinlock contract

---

**2022-11-30T21:01:00**

as far as I can understand ergo tree is some sorta string  that's unreadable

---

**2022-11-30T21:06:30**

so I'm trying to know if ergoscript can be public audited

---

**2022-11-30T21:07:13**

thankyou,I will try to

---

**2022-11-30T21:08:42**

I'd appreciate that

---

**2022-11-30T21:09:06**

so cardano is same with ergo in this part?

---

**2022-11-30T21:11:29**

they have this

---

**2022-11-30T21:12:29**

but I think it's kinda hard to put exact script on explorer,because there's so many rendered value in ergoscript😂

---

**2022-11-30T21:14:50**

yes,one parameter changed, the contract address changed.but thank you very much cheese

---

**2023-08-11T21:30:27**

is there a equation that how many liquidity token I can get when I diposit x and y token

---

**2023-08-11T21:30:41**

using spf protocal

---

