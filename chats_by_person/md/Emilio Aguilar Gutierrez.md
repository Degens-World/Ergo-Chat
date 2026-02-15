# Emilio Aguilar Gutierrez

**Total messages:** 32

---

**2024-07-26T06:53:41**

Can you help me with this issue: 
https://github.com/ergoplatform/ergo/issues/2172

---

**2024-08-05T02:40:49**

I hava a local ERGO blockchain with two nodes... They have the same wallet... But the nodes have different Height... How is this possible?
And their wallet have different amounts (having the same address)... How is it possible?
Are they going sometime to sync height?

---

**2024-08-05T02:42:41**

They are not in the same height... 1372 vs 1279

---

**2024-08-05T02:43:16**

14917.5 ERG vs 8100 ERG

---

**2024-08-05T02:43:51**

How can they sync? How long do I ned wait?

---

**2024-08-05T02:52:45**

Both nodes say: Node is synced

---

**2024-08-05T02:52:58**

But they are not

---

**2024-08-05T03:01:16**

I do not know how to do it

---

**2024-08-05T04:40:35**

- Node 1: Prefix: 96
  network {
    magicBytes = [1, 1, 8, 1]
    bindAddress = "0.0.0.0:9022"
    nodeName = "ergo-mainnet-swa"
    knownPeers = []
  }
- Node 2: Prefix: 96
  network {
    magicBytes = [1, 1, 8, 1]
    bindAddress = "0.0.0.0:9023"
    nodeName = "ergo-mainnet-swa-1"
    knownPeers = ["127.0.0.1:9022"]
  }

---

**2024-08-05T04:41:07**

Is there something  I must add to the configuration to make them work in the same fork?

---

**2024-08-06T02:09:56**

I have deleted the ergo.directory contents of each node. I have unlocked the same wallet in both of my local blockchain... And they are synchronizing... But:

---

**2024-08-06T02:10:06**

- node 1:

---

**2024-08-06T02:10:41**

- node 2:

---

**2024-08-06T02:11:24**

What this means?: 
Sync progress
Syncing headers: NaN% (<- error?)

---

**2024-08-06T02:12:54**

Console just send messages like:
INFO  [ctor.default-dispatcher-5] o.e.m.ErgoMiningThread - Trying nonce 920000
Are they error messages?

---

**2024-08-06T03:14:50**

Is anybody there?

---

**2024-08-06T03:15:05**

Still synchronizing!!!

---

**2024-08-06T05:01:44**

I want to setup a local network with two nodes to mine, connect SAFEW to the local Blockchain... But the configuration I use does not work.
1- nodes have different height
2- SAFEW cannot import the wallet used by the nodes.
I am trying to get support for long time and just get one sentence answer that do no resolve anything day after day

---

**2024-08-06T05:32:59**

I tried with the desktop wallet... Does not work either...
I have two nodes only and after couple hours were not able to sync...
So my configuration files are wrong... I published them and nobody corrects them...😒

---

**2024-08-08T02:07:20**

ergo {
  networkType = "mainnet"

  node {
    mining = true
    offlineGeneration = true
    useExternalMiner = false
    # To work with SAFEW:
    extraIndex = true
  }

  chain {
    addressPrefix = 96
    reemission {
      checkReemissionRules = true
    }
  }

}

scorex {
  network {
    magicBytes = [1, 1, 8, 1]
    bindAddress = "0.0.0.0:9022"
    nodeName = "ergo-mainnet-swa"
    knownPeers = []
  }

  restApi {
    bindAddress = "127.0.0.1:9122"
    apiKeyHash = "324dcf027dd4a30a932c441f365a25e86b173defa4b8e58948253471b81b72cf"
  }
}
I launch only one node... And it is synchonizing forever... (With who?)

---

**2024-08-08T03:36:13**

The url goes to a comparing git version page... I do not understand anything

---

**2024-08-08T03:44:31**

The simplest way to solve a problem is to check if the problem can be reproduced... You have my configuration file... It is so simple, to run an ergo node with it: 
java -jar -Xmx4G ergo/target/scala-2.12/ergo-5.0.21.jar --mainnet -c ergo/my_mainnet.conf
After checking that never synchronizes... You can find a solution (you are the experts) just modifying the configuration files. Or explaining what is missing to do.
And yes... After 1 hour waiting for changes, I launched a second node (not mining) 
ergo {
  networkType = "mainnet"
  directory = "/home/emilio/ergo/ergo-mainnet-swa-1/data"

  node {
    mining = false
    offlineGeneration = true
    useExternalMiner = false
    # To work with SAFEW:
    extraIndex = true
  }

  chain {
    addressPrefix = 96
    reemission {
      checkReemissionRules = true
    }
  }

}

scorex {
  network {
    magicBytes = [1, 1, 8, 1]
    bindAddress = "0.0.0.0:9023"
    nodeName = "ergo-mainnet-swa-1"
    knownPeers = ["0.0.0.0:9022"]
  }

  restApi {
    bindAddress = "127.0.0.1:9123"
    apiKeyHash = "324dcf027dd4a30a932c441f365a25e86b173defa4b8e58948253471b81b72cf"
  }
}
And as usual, did not synchronize; but connected with the initial peer.

---

**2024-08-09T02:35:33**

Does not work... obviously... You have modified a README.md file and a resources file (testnet.conf) that have nothing to do with my configuration file (my_mainnet.conf). Also testnet.conf is for "testnet"... And I am launching a local "mainnet"!
Is there any other to help me? (if does read my messages would be great)

---

**2024-08-09T02:50:54**

Does not work

---

**2024-08-09T02:59:08**

With "devnet" works and both nodes have the same height...
But with "mainnet" does not work
Ia am going to try to change the networkType to "mainnet" without deleting the node data folder... Because the goal is a local mainnet...

---

**2024-08-09T03:03:52**

And after sync in DevNet I changed the networktype to "mainnet" and is still sync and working...
I solved it... I think... Thanks to the DevNet -> MainNet trick.

---

**2024-08-09T03:14:13**

Unfortunately SAFEW cannot get the wallet address of the nodes... (it is "searching existing address" forever)
And ergo-wallet-app lauched with: ./gradlew desktop:run seems to connect but I cannot check becouse I do not have any mined ERG yet in the wallet...

---

**2024-08-09T03:19:02**

I am trying to have an independent main network... I have chainged magic bytes, but not the "genesis block hash"... Could this be the cause of the problem? How do I change them?

---

**2024-08-09T16:20:20**

I do not know about sidechains. But they could interest me...

---

**2024-08-12T09:22:11**

I am working for a company that is interested in developing a POW Blockchain... To use their own token... I have researched some options and Ergo technology could fix as foundation... If is possible to find a collaborative agreement I would be very happy

---

**2024-08-12T16:08:28**

Ok, I Will DM you. The requirements are very simple, POW, easy to mine in BTC machines, and easy to bridge to polygon. Multiplatform wallet and web blockchain scanner...

---

**2024-08-13T02:03:51**

I wrote you a DM in discord (eag_swag->kushti0978) 
If you did not receive it, just tell me.

---

