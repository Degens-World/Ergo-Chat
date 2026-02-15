# Flying Pig (™)

**Total messages:** 359

---

**2022-05-31T10:14:25**

You could set up and mint your own version of sigusd...but it would have a different tokenID and no one would accept it...Unless you can convince enough people that your sigusd is the real deal. Beauty of crypto :)

---

**2022-07-28T20:29:13**

My V35 node keeps dropping peers like nobody's business....dropping back to V34 to see if that helps.
Anyone else having same issue?? (i can see the main public node only has 30 connection! Usually it's got 100+)...

---

**2022-07-29T05:24:25**

It does now. Last night it had 23 at its lowest and all my nodes was under 10. It lasted for several hours. When I woke up this morning it was back to normal.

Someone on the ergo channel posted the excact same thing. Their node kept losing peers in the same timeframe

---

**2022-07-29T05:36:21**

I downgraded my node to 34...which is running fine now.. Not sure about 213 since that's still on 34 and it's now back up to 120+.

Maybe it was all just a fluke, but still weird.

---

**2022-07-29T06:41:19**

When I checked my logs last night my node was banned due to "exceeding max delivery checks" (or something like that, im not at my home pc)

---

**2022-07-29T10:04:45**

Maybe getblok.io could run a testnet pool which pays out tiny amount of ergs to mainnet, but it has to be so tiny that if the hashrate is high people will drop off... :)

---

**2022-07-29T10:05:03**

(not even sure if it's possible, but they seem to be clever people)

---

**2022-09-08T06:59:50**

Maybe nautilus can incorporate both explorers and pick a random one to use for submitting transactions and requesting balances?? @nemo429  spread the load?

---

**2022-09-11T14:26:36**

Public node stuck on 836448...
I had to restart my node to get it going again....

---

**2022-09-11T14:29:24**

(213.239.193.208)

---

**2022-09-11T14:52:42**

It's now catching up again...it was stuck until block 836464

---

**2022-09-11T15:27:11**

Stuck again ;) 
Hopefully will self repair.... My node (running .42) also got stuck a few times.... Hopefully something that can be identified and fixed.

---

**2022-09-11T16:10:40**

Where do I send it? (Message here?)
I did see an entry in the log that says "problems with ntp"

---

**2022-09-15T13:25:00**

Explorer is stuck (public and my own). 
Node is on BLock 840312, explorer stuck on 840298

---

**2022-09-15T13:25:27**

Public node is fine

---

**2022-09-15T13:53:15**

I can see it's fixed..

---

**2022-09-15T13:53:24**

what do i need to apply to my local?

---

**2022-09-19T14:23:29**

Explorer not playing nice again ;(
My explorer is stuck 1 block behind.
So is public explorer

nodes are ok

---

**2022-09-19T14:28:24**

nope, still stuck. Node on 842815, explorer on 842813. (4.0.45)

---

**2022-09-19T14:28:42**

just caught up!

---

**2022-09-19T14:28:45**

weird

---

**2022-09-19T15:18:14**

I that one is just the length of the block, nothing has been mined. 20 minute blocks is quite normal due to difficulty ;)

---

**2022-09-19T15:18:42**

earlier explorer was genuinly stuck 3 blocks behind, but it eventually caught up

---

**2022-09-29T18:04:46**

There seems to be disagreement on how rush to get EIP out was handled.

I'm a user of the network but I lurk in the developer channel to get a sense of what's going on.
The current situation, in my humble opinion, needed to be addressed ASAP.
The user experience is terrible at the moment and although the difficulty would eventually go down over the next few weeks that would mean weeks of bad experience, miners leaving and general discontent. And it would repeat again and again until we reach equilibrium. That could be months!
That's not what is needed now that profitability is down on all POW coins and general sentiment is not favourable. 
As a principle I agree everything should be voted on and time taken to consider options.
However, do not let principles and stubborness get in the way of common sense.
Look and listen to the community who are all (90%+) frustrated with the user experience.....
I think you'll find that once the EIP37 passes normal business will resume....
This is a one off event that needed a one off intervention...

(I'll get back in my box now...)

---

**2022-09-29T18:33:35**

I think my message came across wrong. I wasn't really talking about miner profitability as the core topic of my message. I should have left that out.

I meant that without eip37 the block times could potentially take weeks/months to reach 2 minute (by miners hopping on and off).

That's the part I am concerned about because it hampers the user experience. 

It wasnt about mining profitability...that will come eventually. (PS. I'm mining at substantial loss to support the network and with that it's mission)

---

**2022-10-02T04:53:57**

844672
https://votes.sigmaspace.io/

---

**2022-10-10T17:19:31**

Change the application.conf to increase max peers.

---

**2022-10-10T17:45:43**

Darn...I've been doing it the hard way it seems.

---

**2022-11-06T16:52:21**

All explorers are stuck on block  869219.
Nodes are still producing

---

**2022-11-06T19:36:12**

I've done a reboot as well as trying to pin it to different node versions (103, 105 and 5.02).

Looks like a mismatched data type, my local explorer throws this error: java.lang.ClassCastException: [J cannot be cast to [B 
(chain-grabber)

(Not a developer...just hanging in the forum to read updates and learn)

---

**2022-11-06T19:40:33**

Yup, probably. It's happened before and it needed backend updates.

---

**2022-11-23T10:25:36**

There's someone doing this very soon (2023) I believe...spreadly.

---

**2023-01-16T09:57:57**

You do churn them out.... I just updated mine to 5.0.5 a couple of hours ago :)

---

**2023-02-02T05:51:54**

Python

---

**2023-02-02T12:21:07**

in the tokens table in explorer DB does the box_id reflect the current box the token sits in?
(my guess is no...because when I query a token ID that I know I have in a wallet, it's returning the address of a previous wallet I had)

---

**2023-02-02T12:52:52**

Thanks, i figured. I managed to get what i needed in the end repurposing one of the API queries from explorer db source.

---

**2023-02-15T08:07:51**

https://github.com/FlyingPig69/Ergo_Explorer_Queries
This extracts the tokens left in any ergopad staking contract, by address (or token_ID, just uncomment in the sql).

(PS! Probably a very poorly written query ...but it works...)

---

**2023-02-26T18:04:24**

Addresses can't store data.

You could perhaps create a faucet with unique links that affiliates can link to.

Once an address has been created the new user would need to enter their address and receive a unique token linked to the referrer. Then track that to see if the address has interacted on the Dex. 

But it wouldn't work if they use a derived address on the Dex (private mode in nautilus)

---

**2023-03-05T14:34:11**

Is there a public testnet node?
Going to dip my toes into some light/simple scripts.

I can sync my own but I wanted to test something now :)

---

**2023-03-06T06:58:31**

noob question, apologies in advance. 
I'm using the create token ergotutorial to dip my toes into the appkit using python.
I'm using a testnet wallet with 60 erg (from faucet).

However, i get an error that there is not enough erg in the wallet, (there is...)

Does the appkit get boxes from explorer? I think yes as I found this line in the appkit code.

'    # Check if node is on MainNet or TestNet
        self._networkType = NetworkType.MAINNET if network.lower() == 'mainnet' else NetworkType.TESTNET
        if self._api is None:
            self._api = RestApiErgoClient.getDefaultExplorerUrl(self._networkType)"

The default public testnet explorer is not synced (stuck on feb 8).

Is there a way to change the explorer address using the appkit  in the same way i can change node?

---

**2023-03-06T07:12:07**

Thank you, that worked

---

**2023-03-06T07:45:29**

Two more question...I'm looking at the docs on github but they are outdated (3 years old).

1. Does the appkit support writing to box registers (from the release note it seems so, but there's no docs to say how). 
2. When minting a token, can you, in the same tx, write to the box registers?

My goal is to create a token (got that part done) and write some data in the registers in the box where the token was initially created. Specifically I'm looking to write then token ID in the box register (not sure if that's even possible in the same tx....)

This could be way over my head since i'm a simple python newbie. I learn by reading existing code and then modify to my needs.... But I thought i'd ask.

---

**2023-03-06T07:58:48**

No, then I don't need to write token I'd to register. I was not aware this was the case.

---

**2023-03-06T08:00:18**

But I would like to know how to write to registers if that's possible....

I'll elaborate on my idea a bit later. It's in my head at the moment and it might already have been done by someone more clever than me.

---

**2023-03-06T09:02:43**

I am looking to create a way to store files on the blockchain (i know, not necessarily a good use of space etc..but i want to try. Reason: Because......:) )

A box can store 4kb of data of which ~3kb could be custom (from what I've read).

I'm looking to mint multiple tokens that together contain the data to link them together (1 of x kinda structure) as well as the binary data (xml/base64).
 
I'd build 2 scripts:

Mint:  Convert local file into a suitable format and split into x parts. Then create x linked tokens with data stored in registers.
Extract: Collect registers data from x tokens to reconstruct file locally

Splitting and converting data is not an issue, but figuring out how to enter data in registers using python is what I'm looking for.

---

**2023-03-06T09:07:20**

Excactly!
And it would all be stored on chain. Not on a web server which might not be around in 10 years

---

**2023-03-06T09:13:29**

I'm not there yet, but initial research i can convert to base64 and then split into x parts.
Each token would contain data with:

1. A unique identifier of "collection" (this can be custom, but needs include some no-collision uniqueness to avoid duplication)
2. How many tokens are in the "collection"
3. Which number/part of the collection the token represents (x of x)

---

**2023-03-06T09:14:06**

It's an idea, but I'm a really novice dev. I know HOW it can be done, but putting it into practice is whole different situation.

---

**2023-03-06T09:17:32**

Who needs a use case? :)

You can't transfer a box to someone else?

---

**2023-03-06T09:18:32**

If I can link a token to multiple boxes that contain the data that would work too.

---

**2023-03-06T09:18:41**

(as I said, not a dev...)

---

**2023-03-06T09:21:53**

My use case is that I want to create a token/nft that I can send to someone else and that has the ability to be linked to x boxes containing the filedata.

---

**2023-03-06T09:22:09**

Maybe I'm thinking about this the wrong way.

---

**2023-03-06T09:24:11**

My initial question still stands, how do I create boxes with data in the registers using appkit :) (python).
Once I know that I can experiment.

---

**2023-03-06T09:36:54**

yes

---

**2023-03-08T04:19:03**

I think this was started when I was looking at storing images/files in box registers and using a server/script to extract from the chain/boxes..

... We had a discussion back and forth and then martisaart said she had built an MVP which might have some security issues.

Hence she decided not to continue beyond MVP.

---

**2023-03-08T04:21:10**

It was a discussion/exchange of ideas. Not a proposal 😉

---

**2023-03-17T10:57:57**

https://spreadly.org/

Not sure what status is though....they were thinking of Ido a year ago during bull but then...... 💩 hit the 🪭

---

**2023-03-17T11:47:29**

I thought everyone knew "they"??

I read in a discord channel somewhere where ergopad was discussed and spreadly was mentioned as a potential ido.
But this is almost a year ago and much has changed. 
They could have shelved their idea and gone back to their dayjobs....just like Darkpool (rest in peace)

---

**2023-03-18T06:46:17**

I can now install without being in developer mode.

But when using it it still says "Pending review". I guess the Devs need to turn that prompt off in the code itself.

---

**2023-03-18T06:46:42**

Which would require a new ledger review....:)

---

**2023-03-25T11:58:43**

Has anyone done an analysis on how how many boxes will be impacted by storage rent?

I did a quick query and from the first 6 months (Jul 2019 - 1 Jan 2020) there seems to be 307 boxes totalling just over 13k. One box has 1400 ERG! That box would take centuries to return to the chain....

---

**2023-03-25T11:59:56**

Perhaps there needs to be some sort of multiplier for each storage rent period where nothing has moved?

---

**2023-03-25T14:09:19**

I thought it was also to avoid a "Satoshi-wallet"?. Currently 1 million bitcoin not in circulation.

But I guess dust causes a lot more clutter.

---

**2023-03-25T19:41:31**

I did not know this....
Makes sense to me know.

---

**2023-04-02T04:31:41**

The same might  need to be done on node_u_outputs

I had mine synced from scratch the other day, but yesterday the utxo tracker got stuck.
Only affects mempool, but still..

Current schema per github: CREATE INDEX "node_u_outputs__ergo_tree" ON node_u_outputs (ergo_tree);
Should be: CREATE INDEX "node_u_outputs__ergo_tree" ON node_u_outputs using hash (ergo_tree);

I don't really know how to use git for this kinda stuff (i'm just a dev channel lurker....)

---

**2023-04-04T03:54:31**

Your previous Paideia transactions froze my explorer utx tracker...could be same thing?

---

**2023-04-04T04:03:42**

Log entry....

---

**2023-04-04T04:05:25**

I dropped node_u_outputs__ergotree index (btree) and recreated using hash. Same issue as with node_outputs.
That table is very small though, not sure why it's indexed at all really....

---

**2023-04-04T18:02:11**

Is there a way to extract all smart contract addresses?

---

**2023-04-04T18:08:43**

True...but we could get some sense of tvl...or even map addresses to known projects.

---

**2023-04-05T12:33:16**

Total Value Locked in USD:

I know you guys discuss and create complicated contracts, quantum physics, wormholes and other interesting concepts.

Many of you could probably write this is in machincode whilst blindfolded, hanging upside down and sipping a glass of something strong. BUT..........you haven't so here we are :) 

Hope there's room for us amateurs as well.

We were discussing TVL (in USD) yesterday so I took it upon myself to put together an explorer query to do just that!

It pulls just over 3200 contracts (excluding mining/emissions contracts). 
Many of these are spectrum proxy contracts where I suspect trading bots have submitted swaps that slipped and they never refunded....
It likely also has a number of multisig wallet (e.g. ergofoundation) etc. 

But it's a start.
I've added the name of the contract where I know what it is, if someone has a contract address they want to share, let me know.

Covers:

1. Erg.
2. sigUSD
3. SPF
4. Neta
5. Paideia
6. Ergopad
7. EGIO

It's easy to add new tokens which I will do when get some spare time, or anyone can do it themselves.

It's probably a poorly optimized query, but it works! And takes around 5 minutes to complete.

Query is here, and you can also find the csv of today in the data_outputs folder.

https://github.com/FlyingPig69/Ergo_Explorer_Queries/blob/main/contracts_TVL.sql

---

**2023-04-18T12:43:48**

what happens if node mempool is full? (1k txs) 
Does it reject txs until space is available or replace the oldest one?

---

**2023-04-18T13:20:14**

But if the fee is higher than existing txs in mempool it will replace it?

---

**2023-04-18T13:21:27**

Basically, if the node is full, i can submit a tx with a higher fee than the lowest one in the mempool and it will replace it.

---

**2023-05-05T01:55:16**

Some miners consistently process less than others....

Can you share your mining pool list?

I don't have nanopool address for instance.

---

**2023-05-07T03:34:49**

Lithos?
I think that's what they aim to achieve.

Benefits of a pool for small miners to still reap consistent rewards, but the winner of the block actually processes the transactions (even its a small 1gh/s miner)

---

**2023-05-28T02:52:00**

Try the spectrum channel. You'll have better luck there.

https://t.me/spectrum_labs_community

---

**2023-06-09T14:04:56**

You can probably use this query and modify it. It pulls all contract addresses with erg value plus a few tokens, but you can modify to include all addresses..

Take out the last 4 lines and you should get what you need....but it will take a looooong time to run I would think.

https://github.com/FlyingPig69/Ergo_Explorer_Queries/blob/main/contracts_TVL.sql

---

**2023-06-22T11:40:12**

Like ergpy?

---

**2023-07-03T12:05:46**

It's not...stuck in spectrum proxy contract!

---

**2023-07-03T12:05:48**

https://explorer.ergoplatform.com/en/addresses/2ysN6BW5GJ41gzDcT9uZf9rbph6aZnmjbkxWsj5TSWpV4SvmU1YijHvzPKovM6erXta5paZUY2WGn1JH9dX3DT5PvNEpDXbWiYMVjCpzUUWos96m4Kb5Dsftimymq4dv59NyF5c2S8HZfSJoNLLADDALxJTAbNXUtzSf5NeLWHdWq852RCXFyyHmu4g5HcVvUUb2oiE8wjC1nVwt3aZ9fh27r69xbLh2U44UYTjoJhDST6wsmv6uKgvx4TAc81SaYuEjKiWJmpezpw9MuuTDFX9qwnWxMEF5dcde9WGWaFxE1QHMXGyBkYNKpaBEg9wL5j25foUVCs3HudeYVxRR5xkh4U7AGHt3Nuc7omKZH7dmf3WaVeFpjHSMiioBr4xPX8zrhZ3BYRCy8ZNS3qz1mmM3iQf9A95UyijAyRdzUxNeTymNpnEi9qJBaAxtNuRK7GryrHunzc2xv72cNC8izR8EydFLkMhRLsE36Yiw2k67yT5e3Lp4KDudiEFzMHF1MLAQpyxXviBRdReziTHTJpRSW4ZrDb3P9Ed2USVqjh1XiHJZKMdxSY6AoH5QXenBMpyH1956RBdaFTCJ4macqqxhzn

---

**2023-07-03T12:07:28**

hmmm...14 confirmed txs..i bet it failed and needs to be refunded and try again. Unless some of the spectrum guys can create a tx to manually push this through? whilst adhering to the rules of the guard script of course.

---

**2023-07-03T12:07:53**

failed meaning, the bots didn't pick it up for some reason.

---

**2023-07-03T12:10:46**

No, i'm saying someone used the "remove liquidity" function on spectrum. This creates a proxy contract where they send the LP tokens. The bots scan for this and executes the contract.

It can be refunded, but they'll have to try again.

---

**2023-07-03T12:15:38**

nope...someone exploited the hodlergo contract...

https://explorer.ergoplatform.com/en/transactions/6f76516fa9a453478f65d6c9476398cbb883728ee89a354ff9c56bdc07524ca6

---

**2023-07-03T12:16:36**

and then swapped 30k hodlERG to drain the LP

---

**2023-07-03T12:16:37**

https://explorer.ergoplatform.com/en/addresses/zCkAGbp4TmVEp91dy8R2VqCcwhmLSjZGioVMwa8agsWtjd94RaT7tXaJGue17eGmnokgRmtAP23QRTPTHYMrg1KqcHhzPuH953AhS27MpPuHedrTiU8DW5eWgHGiYnTzUnkbLux3ERyTeie8keAT6vHzfGa4fw8LoRyyR6QTq9o2X2aWY84PweqnFAQn8FchFbBvegcpj1BdRHJ2pkpcvCrH4hYaw8vwtoPHJngofp8ktYaEc2sqMhCwCXExHio8VHPixPm2NAz1axhkajiAgDPHEanMxqfbxXcXkUKpoDTR4iqfN7Vbys7LRDGJHLS1Wvc1bDjR1TggEB5yyYU3vgYfoDqsQZvmTfiySnQQr4A1vPZ8EacvHDKEWp6Aj7UyJgh9JbYzwyzbGt1xEHqnL2pEpNQBR77W2vauwqHR98JJusHWjfUv4WCeXMQrgj8be3fKpGqTht7kTk2UNPQAfBQdTtCjM1cizhXx93YzQy86PTwrLjNiv5hWnhqBA3WmocZebJEkTcZ7MUJeqWN4TFESHNv4ckWRaEJbSZiwbgN1AeExyjRzvoBdvLZf8veJrTbCQihqApEYHhAVEboXqBXkes6ZXmke

---

**2023-07-03T12:19:47**

Yeah, and then they sold it on spectrum and gained 900 ERG.
In this case the original LP holder lost that :(

---

**2023-07-03T12:24:16**

Now we have to be careful with refunds!!!

---

**2023-07-03T12:24:40**

if you refund hodlerg then this scammer has 96k worth of hodlerg tokens!

---

**2023-07-03T12:24:42**

9fqhn4LpFKXDAzh4fDG3gY3tSyPEQ4stcMNjpjg5L6tjQGeHVJW

---

**2023-07-03T12:26:29**

Some might have genuinly bought from spectrum as well (not sure how many, but some might have)

---

**2023-07-03T12:29:09**

Yeah, you can buy 41 hodlerg from spectrum for 1 erg now.

---

**2023-07-03T17:28:16**

I think Kushti refunded him. Which is an incredibly kind thing to do.

---

**2023-07-03T17:35:01**

Lol. Probably to try and obscure who has actual hodlerg 

I wouldn't worry about it....the blockchain has a history of what tool place before the exploit.

---

**2023-07-03T17:36:04**

If thats what they are tying to do then that just proves they are an amateur.

---

**2023-07-04T01:59:45**

Kushti will figure this out in 2 blinks....

---

**2023-07-04T17:41:18**

Can you reverse engineer a smart contract address/ergotree?
(I'm guessing no....)

---

**2023-07-04T17:53:04**

The reason I'm asking is because the hodlerg hacker put 75 of the 950 erg they stole in a smart contract. That contract only has 1 tx.

Just wondered what it could be :)

---

**2023-07-04T18:36:32**

Found it...but makes zero sense to me.

If anyone can decypher it then that's where 75 of the 950 ergs from the hodlhacker sits :)

I'm just a sleuth trying to track it.
I thought they would run it through a mixer or withdraw to an exchange....

---

**2023-07-06T06:30:52**

1st is the emission contract where block rewards are paid from.

2nd is the miner address.

---

**2023-07-15T03:05:47**

https://docs.ergoplatform.com/dev/scs/ergoscript/

---

**2023-07-15T03:07:20**

The experts will come along soon I'm sure, but these are some great resources. I'm a novice/beginner.

---

**2023-07-15T03:09:29**

Yes! I've used that. Great examples with clear explanations of core functionalities.

---

**2023-07-18T01:32:48**

Because they don't know.... Or have left the ecosystem.

---

**2023-07-31T15:15:34**

main explorer is stuck on 1059124 .... as is my own explorer
Anetabtc explorer seems to be up to sync...

---

**2023-07-31T15:20:51**

Mine caught up and so did main...was stuck for 30 minutes or so. Weird....

---

**2023-09-06T04:48:02**

Is there an updated or alternative version to this tx builder? It's archived and I couldn't get it to compile?

Looking to build TXs in a simple way using Python. 
This looked like a VERY easy to use tool. All it would require it the in/out in json format and it will create a unsignedtx.

https://github.com/scalahub/jde/tree/main

---

**2023-09-06T04:56:18**

I have ergpy but i can't pick the boxes....at least not figure out how..
JDE allows to specify input boxes by boxID etc...run it through the tool and it will create an unsignedtx (according to the description).

If this worked it is SUCH an easy way to build a detailed TX without complex code.

I guess what I'm after is a simple way to list the boxes i want to spend, and the input addresses/tree along with any register entries and have a tool create the unsignedtx.

---

**2023-09-06T05:11:54**

I'm more proficient in python, much easier to use for a novice like me with little spare time to learn new language.

---

**2023-09-06T06:51:33**

Lol...it's ok. Wasn't a request as such. Just asking what's out there and what is not :)

Ergpy is pretty cool too for building simple txs :) thank you.

---

**2023-09-06T18:57:11**

Python is incredibly simple for novices to use and to learn. 

Java, scala, rust etc etc has a much steeper learning curve. More flexibility and options for sure, but sometimes quick and easy is preferred.

And your work on Ergpy is much appreciated by us "mini/apprentice-devs" who don't necessarily have the motivation or time for heavy learning to do basic functions.

Having said that, I have decided I will attempt to figure out typescript enough so that I can use fleet....we will see how that goes..

---

**2023-09-14T14:51:32**

you broke my explorer.....

---

**2023-09-14T14:51:40**

and the public one :)

---

**2023-09-14T14:53:17**

grabber is synced but api/blocks is on 1073...maybe it will sync up 👌

---

**2023-09-14T14:55:39**

it's on 1079 now...so catching up, no error.

---

**2023-09-14T14:56:37**

and mine is back on track!
Public still lagging

---

**2023-09-14T15:08:38**

no, nothing.

---

**2023-09-14T17:21:43**

Mines on 29...catching up. 
I too have made  bunch of changes to pgconfig, but not to heap sizes in the  explorer code like reqlez.

---

**2023-09-14T17:22:21**

nope, mine is up to sync again. Performing like a champ!!

---

**2023-09-15T01:53:21**

Can you set those directly in the ergo.conf file? 

Or do you need to amend in application.conf and then build?

---

**2023-09-18T08:25:13**

Is there source for this? Is it written in python? (if yes..."yaaay!"... if no.."oh well"

Looking to create multiple separate outputs from one larger file.

So let's say I have a file with 1000 transactions, i want to split that into 10 of 100 each. 
Ideally chained, but non chained is ok as well.

---

**2023-09-18T17:51:11**

Is there a min number of erg a box with a token needs to contain?

---

**2023-09-18T17:55:17**

i did 0.0001 and that worked...just wondering how low i can go..

---

**2023-09-18T17:56:20**

I'l just keep lowering it then, until i hit the limit...

---

**2023-09-18T18:03:10**

p2pk plus token

---

**2023-09-18T18:03:45**

0.00001 gives me this...
"ery output of the transaction should contain at least <minValuePerByte * outputSize> nanoErgs"

---

**2023-09-18T18:04:18**

They are :)
Each token has it's own box with 0.00001

---

**2023-09-18T18:05:47**

0.00004 worked....

---

**2023-09-18T18:06:16**

I'm cheap..don't want to overpay :)

---

**2023-09-19T09:14:17**

I'd put my hash towards a Sig mining pool!

Winter is coming so my miners will be turned on for heat. Was mining aleph but if someone created a pool with storage rent support I'm in with my approx 2ghs!!

---

**2023-09-19T11:01:01**

i can throw a rig at it at night if it helps. Not quite as cold yet as it needs to be.

---

**2023-09-25T05:28:00**

We should change TPS to BPM (Bocks Per Minute...)

That's what users care about. How long for my tx to get confirmed so that I can do the next one...

---

**2023-09-27T16:46:04**

You're only 40?.......
Child!!!

Don't think you're alone. I'm in the same boat as you, learning because of Ergo.

We should start an "old persons club"!

---

**2023-10-04T11:14:49**

Question/concern...(prompted by a concern by lexylemon in Baseless)

How can we prevent mass spam of utxos for a single address?

When I tested my mass AirDrop tool,  I initially used my own address.

I ended up with 20k unspent boxes.....took a while for me to clean up.

The average user wouldn't know how to do this and when using Safew, the wallet didn't even create a tx (didn't test satergo).

Nautilus can do it but limited to 200 boxes, it should probably allow much more than that, 2000 is possible.

But still, how can we prevent this type of spam? 2.5 erg and I can spam someone with 60k boxes....

Proposal:
Can there be limits to amount of boxes sent to one address in one tx? 
Maybe this can be set at node level/config. Not sure.

But I think it needs to be addressed.

---

**2023-10-04T12:10:45**

You can retrieve unspent boxes by address/ergotree from non-indexed node.

Not sure why explorer is used by wallets for tx generation but then again I'm not the expert.

---

**2023-10-04T12:11:51**

Doesn't lite node store all utxos?

I thought lite nodes stored utxos but eventually prunes spent ones.

---

**2023-10-05T01:45:21**

This is helpful, was not aware of this settings. I guess other wallets could implement similar approach.

Safew didn't manage to create the tx at all, Nautilus was fine, didn't test satergo

---

**2023-10-09T10:38:06**

How does the remission work? Are there 2 contracts?

I'm seeing this:
https://explorer.ergoplatform.com/en/addresses/22WkKcVUvboYCZJe1urbmvBL3j67LKb5KEAvFhJXqA6ubYvHpSCvbvwvEY3xzUr7QvxpEtqjzMAPMsVdZh1VGWmZphvKoJdVzL1ayhsMftTtEFoA3YYdq3zKeeYXavVrrPUmK3fRXJ2HWEbZexewtBWcgAnHBw5tKvYFy9dEUi645gE2fYMUvVBtbvMExE9mjZ2W9goWkqu1VtThAsMZWZWjHxDjX116HpeQKu9b9neEUBj4kE5sX8QXaV6ZeReXxYHFJFg2rmaTknSPMxHXA8NpQKgzryBwLssp5EJ1QTqn5R6xuvGgFCEUZicCEo8qk8UNbE7e2d4WqW5qzpQPzJkKoPa5UtJEPYDWNhaCKmCpzdSc77

Holding 3.1 million and a Remissions NFT Token

Then this:
https://explorer.ergoplatform.com/en/addresses/6KxusedL87PBibr1t1f4ggzAyTAmWEPqSpqXbkdoybNwHVw5Nb7cUESBmQw5XK8TyvbQiueyqkR9XMNaUgpWx3jT54p

Holding 756k and receives 12 erg for each block (but some seems to be bundles in multiples of 12).
And it seems to send txs to the first address, but nothing since August...

Just curious on how the mechanism works.

---

**2023-10-12T05:17:04**

Tried to write this is in discord but got time out...let's try in telegram....

---

**2023-10-12T05:17:40**

Using ergpy how can I create/send transactions from multiple sender addresses? (In this case a contract and my address?)
I can specify what multiple recipient addresses receives, but for senders, it looks like the send_tokens function uses a str for sender address, not list (which is does for receiver address)?

sender_addresses = [
    "2werr........",  #contract
    "9fLYPig......"   #prover
]

receiver_addresses = [
    "2werr........"",
    "9fLYPig......"
]

token_ids = [
    ["abv123", "def456", "xyz"],
    ["xyz"]
]

erg_out = [4, 3] # from sender addresses
erg_in  = [2 ,5] # to receiver addresses

tokens_out = [
            [1,10,40], # from contract
            [0] # from prover
]

tokens_in = [
            [1,10,30], #to contract
            [10] #to prover
]

output_main = helper_functions.send_token(ergo=ergo, amount=erg_amount, amount_tokens=tokens_in,
                                          receiver_addresses=receiver_addresses, tokens=token_ids, fee=miner_fee,
                                          wallet_mnemonic=wallet_mnemonic)

_____Helper_Functions____
@initialize_jvm
def send_token(ergo: appkit.ErgoAppKit, amount: list, receiver_addresses: list, tokens: list, wallet_mnemonic: str,
               input_box=None, amount_tokens=None,
               mnemonic_password: str = None, sender_address: str = None, prover_index: int = None,
               base64reduced: bool = None, return_signed=None, chained=None, fee=None):

---

**2023-10-12T07:01:09**

The contract doesn't require signing, the 2nd (mine) address does.
You can specify which address to use for signing (in the functions there's a prover_index.

I can see exactly what this transaction should look like as a json, but I'm struggling with constructing it with the available tools.

---

**2023-10-12T07:04:11**

It seems like a "simple" thing...

Outputs:
Specify sender addresses
Specify how much ERG to send from each address
Specify which and how many tokens to send from each address
Specify which address to use as signer (prover)

Inputs:
Specify recipient addresses
Specify how much ERG each will receive
Specify which and how many tokens each address will receive

Assemble as a json and sign.....

---

**2023-10-12T07:05:08**

Maybe I'm asking too much :)

---

**2023-10-12T07:11:37**

Yeah, I'm thinking that might be an easier option, but more work 😜.

I looked at the duckpools code and they have a json template and just populate the various values/boxes

---

**2023-10-12T07:14:22**

Yeah, I know the box i want to use from the contract, that's the easy part.
Selecting my own is a different matter 😜

I'll get there, learning a lot as i dig into these things. 

I was looking for an easy option, but that might not exist.

---

**2023-10-13T11:38:48**

Gave up on building my "complex" tx using ergpy....so started from scratch and will build myself (in python, but not using appkit). Aiming to have the node create and sign the tx.

Came across a problem:
When creating an unsigned TX using the node, does it only scan the main wallet for available boxes?

Scenario:
I built a python script that creates my request which I pass to the node. 

I have 2 tokens i want to send to 2 addresses.
1 token is in main wallet address
1 token is in a derived wallet address.

The node seems to not find the token in the derived address?

As per attached image. If i specify the tokens in the main address, it works fine, but not for any in a derived address.

---

**2023-10-16T18:40:58**

Bah...or use api from spectrum....I did it the hard way.

Typical me!

But somehow I manage to get most things working in my hacky way!

---

**2023-10-16T18:44:47**

Lol...I actually didn't know the API had the pool ID......and I only needed 3 or 4 for my bot so did it manually :)

But to answer your question, I'm all for automation, but for me that comes after the discovery phase.

---

**2023-10-17T05:37:17**

Actually, what would you do if the spectrum API went down or they made some changes to the structure? (unlikely, but possible)

I'm pulling data directly from the chain instead....so my only point of failure (apart from code...) is the chain itself! Pool_ID will remain constant forever....

---

**2023-10-17T05:47:11**

Lol...sure, but then code would likely have to change too :)
But the old would still be there right? They can't move funds to new contract.. so there's that.
If they can, then it's centralized :0

---

**2023-10-20T17:05:28**

This is one of the key factors of success. UX has to be superior. Users really do not care about fancy terminology, they care about speed and experience.

Developers on the other hand DO care about tech.

There's 2 types of marketing.

1. End users:
Keep tech talk at a minimum and focus on real world use cases. Stuff they undersand. It's even ok to talk about Txs per second. We can get 1000 Txs in a block, that is great marketing! (Technically it's outputs, but end users care not)

2. Developers:
Market the security, ease of development, extended utxo, Sigmaprotocols etc...they get it and we need them to be onboarded and build cool stuff.

---

**2023-10-29T17:32:08**

[Dinosaur enters the room....]

---

**2023-10-30T11:04:13**

what settings in conf to index the node?

---

**2023-10-30T11:04:24**

(github has no mention of it)

---

**2023-10-30T11:47:40**

ergo.node.extraIndex = true

---

**2023-10-30T11:54:32**

Do i need to start from scratch? I had a pruned node...

---

**2023-10-30T11:54:40**

doesn't seem to be indexing.

---

**2023-10-30T12:03:18**

i turned pruning off, but i guess i have to start again

---

**2023-10-31T10:48:20**

Is there a way to speed up how quickly the node cleans up invalidated transactions in mempool?

I can often see multiple txs spending same boxes in the mempool on my local node, and they remain for many confirmations before being cleaned out.

Ideally they should be removed and not propogated at all if it's invalid, no?

---

**2023-10-31T10:49:38**

i tried that, but seems to still linger in there for a while, i'll try again though.

whichever node the public explorer uses is pretty efficient, it clears up quickly

---

**2023-10-31T10:52:45**

Want it faster than that, but I'll give it a go, thanks.

---

**2023-11-22T04:36:14**

The Node API doesn't seem to always return the token information for SOME tokens..

this is bPaideia, token cannot be found:
Example: http://213.239.193.208:9053/blockchain/token/byId/0040ae650c4ed77bcd20391493abe84c1a9bb58ee88e87f15670c801e2fc5983

this is the remission token, token cannot be found:
http://213.239.193.208:9053/blockchain/token/byId/d9a2cc8a09abfaed87afacfbb7daee79a6b26f10c6613fc13d3f3953e5521d1a

---

**2023-11-22T04:37:18**

same for my local indexed node, those two tokens can't be found. There is probably others as well

Edit: I should have read two messages up.....my bad! :)

---

**2023-11-22T08:46:43**

hate wick......wall of text!!

---

**2023-12-07T14:06:44**

http://node_url/blockchain/indexedHeight

---

**2023-12-08T17:55:34**

Restore in nautilus and send yourself everything or break it into a couple of txs.

You can comfortably send around 1k boxes in one tx (depending a bit on the contents).

I don't understand why mobile wallet only does 80 and Nautilus 200.

It should consolidate up to the max 96kb.

---

**2023-12-14T12:20:47**

Ah crap...mine to. :(

---

**2023-12-14T12:22:11**

Shameless plug. Ergo Node Explorer has a warning implemented to let you know if main node is not indexed correctly :)

---

**2023-12-15T09:24:39**

kushit's node (213) is on .16 and fully indexed. How?

---

**2023-12-15T10:03:13**

Whoops! Sorry :(

---

**2023-12-17T14:37:02**

mine got stuck erlier today (used2066 branch). A restart fixed it

---

**2023-12-17T14:39:33**

at 1157056 to be precise

---

**2023-12-17T14:43:48**

actually no, 2 days go...

---

**2023-12-22T08:43:44**

Any endpoint on node for transactions IDs by address? (to return only a list of TXids, not the entire tx data)
There is /blockchain/transaction/byAddress but that returns ALL the data, was looking for something a bit leaner for only returning a list of IDs.

Looking for something similar to what /blocks/{headerid}transactions does.

---

**2023-12-23T03:26:35**

ASICs are encouraged by design.

---

**2023-12-23T03:28:13**

I bet Bitmain already has or are designing them.

---

**2023-12-28T10:39:23**

Apart from 213, are there any other public indexed nodes?
I've made an update to node explorer and with the public node being heavily used i was thinking to point it to a less busy one?
(Vercel has max 10 seconds execution time and times out on some of the larger queries)

---

**2023-12-28T10:43:17**

thanks, i'll give it a go. Still 10 second limit, but hopefully not so busy.

---

**2023-12-28T10:44:49**

just updated it, will tell you in a few seconds. the main one works fine for most queries, but it runs over 10 seconds on larger ones such as spf rich list (yes, it has a rich list now!)

---

**2023-12-28T10:49:07**

sorry, was much slower than 213...couldn't even load the RSN list :) I've reverted back.
Peeps will have to run their own for the larger queries.

---

**2023-12-28T10:55:54**

90ms to yours and 35ms to 213.

Shouldn't make that much difference

---

**2023-12-28T11:05:30**

Well, it's this one

http://213.239.193.208:9053/blockchain/box/unspent/byTokenId/9a06d9e545a41fd51eeffc5e20d818073bf820c635e2a9d922269913e0de369d?offset=0&limit=100

BUT, it's run multiple times in increments of 100 until it's got all the boxes (there's a LOT!)

---

**2023-12-28T11:09:05**

one after another, it just appends them together

---

**2023-12-28T11:10:17**

dunno, the script just runs until it's found the limit :)

---

**2023-12-28T11:13:06**

im running it now, we're at 100k, it's counting :)

---

**2023-12-28T11:36:20**

This was the problem!!
I added a counter and noticed that the code spent a LOT of resources appending 100 items at a time. I changed limit to 16384 and it's MUCH faster!

I added your node again and most tokens load fast now.

It still can't do SPF as that's 50k boxes. Takes 15 seconds or so on my local PC so can't get that under the 10 sec vercel limit.

Thank you! :)

---

**2024-01-16T13:29:45**

What is the key difference between a stealth address and setting up multiple covert addresses?

If you send me erg to a stealth address and I later spend that by sending it to my wallet, then there is a link between what you sent the stealth address and what I withdrew from it.

Not sure I get it...or does it get mixed after being withdrawn from a stealth address?

---

**2024-01-18T06:52:09**

From node setttings:

# Number of transactions from mempool to be re-broadcasted at each epoch
    rebroadcastCount = 3


———
What specifically does this do, explanation is a bit unclear

1. What is an epoch in this case? (a block?)

and then what happens? Does it rebroadcast 3 transactions from mempool every epoch? If so which txs?

My initial thinking was that the node will rebroadcast a mempool tx every 3 blocks until it's confirmed or cleaned up as invalid.

---

**2024-01-18T16:47:22**

Node derives addresses differently?
Added new addresses in the node, but they don't match new addresses in nautilus, using same seed.

Only the first address matches, any subsequent ones are different.

---

**2024-01-18T17:05:13**

nope, didn't set a pass (i verified this in the node, just in case).

---

**2024-01-18T17:05:46**

didn't do anything to derivation path.

---

**2024-01-25T10:34:52**

how deserialize registers (to numbers) using python? :)

---

**2024-01-25T10:44:35**

and what does r4 and r5 represent in the sigusd bank box?

---

**2024-01-25T10:45:54**

Thank you :)

---

**2024-01-25T11:05:39**

close....

1 digit off

---

**2024-01-25T11:25:23**

Fixed it....

---

**2024-01-26T06:15:34**

serializes numerals for registers using python.

I forked it and added deserialization as well...seems to work ok.

(full disclosure, maths is way above my level so i had to consult chatgtp on some of the parts...)

---

**2024-01-30T06:19:06**

Add node explorer on top of satergo as indexed node? (But I know you don't like python)

Imagine downloading satergo and you get one click indexed node, wallet and explorer!

---

**2024-01-30T08:34:38**

You can populate your explorer psql DB with the info in the known miners table.

---

**2024-01-30T08:34:58**

I'm still baffled as to why the official explorer doesn't have it populated....You need to do it manually, but once done, it's done.

---

**2024-01-30T08:36:03**

I'll share mine and Aco you can share yours, then we can have a complete list?

---

**2024-01-30T08:39:33**

As per Aco, someone published a list somewhere, and kushti has provided names of a few. You can also cross reference the data from the miningpools website, they will show which blocks they solved.
But there's no official way

---

**2024-01-30T08:56:43**

Do you miss the 1 hour block times as well?

---

**2024-01-30T18:30:24**

Forked, fixed and added numeral deserialization as well. 
Need better python support ;)

Complex stuff! Waay above my brain capacity but some help from chatgpt got me there.

https://github.com/FlyingPig69/ergo_serializer

---

**2024-02-02T13:06:47**

I wouldn't count receiving wallets...that would include the 1000s of wallets that received 0.0001 from an airdrop..

---

**2024-02-24T18:18:32**

"sorry"?

---

**2024-04-15T18:08:49**

Safew allows to build the tx and select which address to send from.

It's a bit hard to find but it's possible.

Safew is very slow though and terrible UI.

I wish Nautilus gave more control over addresses to use!

If you use mobile wallet you can select which specific address to send from from, but that only works with regular tx, not daps.

---

**2024-04-15T18:11:34**

Thinking about it, not sure if safew allows address selection when using it as a dapp...

Regardless, I agree 💯 that wallets should allow you to select which address to use for spending boxes, as well as chose a separate change address.

But not sure that is priority yet. 99% of users don't need it.

---

**2024-04-15T18:13:31**

If ergopay is supported you could use the ergopay cold wallet functionality.

Add the seed on an offline phone.
On your "hot" phone add the address as read only.

Then when making a tx/dapp interaction you can scan the qr code with your hot wallet using the address you want to use. It will only consider boxes for that address.

---

**2024-04-15T18:18:08**

No, the hot wallet will choose which boxes to use, and since its a read only wallet it will only consider boxes for that address.

Then you sign with the offline wallet.

I've used this a lot. Works, but I'd prefer Nautilus to have it as I use a ledger

---

**2024-04-25T15:23:41**

What number of confirmations does ergo consider practical finality?

---

**2024-04-25T15:35:27**

I am asking as having a discussion with someone the 30 confirmations required from CEX (kucoin in this case).

Is 30 what we consider final and no rollbacks?

---

**2024-05-01T15:15:42**

Would be good to have a way of clearing mempool from api? 
I've seen other blockchain nodes able to do this through a simple post.

Ocasionally invalid txs hang around in mempool for several blocks even though spent....

---

**2024-05-01T15:20:37**

Ideally the solution should be to clear txs in mempool that have been spent (either spent by another address OR already completed)
You can often see this happening with spectrum execution bots.

There are multiple wanting to spend the same box, but only one wins. You'll often see an invalid/didn't win tx hang around in mempool for a few blocks even though that box has been spent.

---

**2024-05-01T15:21:54**

Yes, but it doesn't.

---

**2024-05-01T15:23:21**

I tried reducing the mempoolcleanup duration but that didn't work.

---

**2024-05-02T11:19:11**

Love the speed at which you work kushti....either means request was easy, or you're just superhuman.

I think it's the latter!

This improvement will make working with mempool SO much easier.

---

**2024-06-08T06:58:39**

Fleet real world commented  examples of basic functions

Sending tx
Sending token
Minting token (incl audio/graphics)
Adding data to box registers (to include serialising)

And how can you do the above connecting to Nautilus/ergopay.

I have a very good handle of utxo and I can build txs in python (without ergpy) but lacking a way to properly manage registers and people tell me "use fleet....."

---

**2024-06-08T07:02:06**

Tbh I'm more interested in learning how to use fleet....and then I can focus on dapp connector.

A new dev entering the ecosystem (in particular novices) learn best by examples and tweaking those to suit their needs...

---

**2024-06-08T07:11:17**

Devs usually don't want to write docs.....it's not fun.

And I totally get that. You should see my code!! No one would get it. But then it's only for me

---

**2024-06-08T07:11:48**

I guess you could do bounties for writing good documentation?

If there's an incentive someone will pick it up.

---

**2024-06-08T07:23:15**

For dummies by dummies?

---

**2024-06-08T07:24:19**

When ergo moons and I retire I'll create docs for all my python stuff...after detangling the spaghetti..

---

**2024-06-12T09:49:33**

You can run as many as you your memory can take.
In ergo.conf just change the ports.

---

**2024-06-12T09:51:10**

yes, i believe so. I've actually added them to all my nodes so that i can keep track.
And you can just copy the entire folder over so no need to sync.
If you need a new wallet just delete the wallet folder

---

**2024-06-12T09:52:04**

Yeah, you need to reindex for the wallet, and i tend to adjust the indexheight so that it doesn't start from block 1

---

**2024-06-12T09:52:18**

it's wallet scan btw, not reindexing the whole chain.

---

**2024-06-12T09:55:01**

213 node seems to be down.

---

**2024-06-12T09:56:09**

Who has time for that :p I need things NOW!

---

**2024-06-12T10:38:37**

Both

---

**2024-06-19T08:03:15**

Delete/backup as per Glasgow then restore wallet with seed.

Then set wallet/scan (or something like that) to the height you want to start at. 

I've done this a million times, works great.

---

**2024-06-19T14:49:34**

Wowsers! That would be immensely helpful to newbies and allow projects to focus on building rather than how to serialize correctly :P (might be easier for some than others).
Not a critical item though, but thought it was worth asking :)

---

**2024-06-20T07:48:07**

Excactly that! And also the reverse. Provide serialized constant and get "5" or "(5,10)".
Explorer does this on the UI, provides serialized and rendered value for registers.

---

**2024-06-20T07:49:47**

This is not my tx BTW...but an auction coin tx by the same person who did that RosenTx 😜

---

**2024-06-24T03:09:45**

What about BASIC?

---

**2024-06-25T10:49:58**

Cardano is currently under ddos attack, costing the attackers 6 ada a minute and slowing the chain down (but txs still go through, just slow..). not sure of motive yet.
How could this be handled on ergo where txs cost is tiny?

Let's say someone decided to spam the network with 10000 txs every minute. 
It would cost $15k/day but someone might be incentivised to do it.

---

**2024-06-27T13:26:48**

Miners would get rich!!

---

**2024-06-27T13:30:58**

Not much...nodes would be a bit bloated perhaps but that's about it. Eth is terrabytea...sol even larger..

---

**2024-06-27T13:32:31**

Each tx can only be 96kb
So depends on how many tx the chain could process..

And it would be VERY expensive

---

**2024-07-01T04:39:19**

213 node index seems broken for some records on /blockchain/transactions/byAddress
Indexed height is up to date but some addresses do not have latest transaction in the db.

Example here from 213 vs my own indexed node, mine pulls the latest tx, 213 does not.
(it's not my address, just a random one i picked)

---

**2024-07-01T08:25:36**

Yeah, i noticed that if I increased the limit it would return all the txs, but not in the expected order.
I've always seen the last entry (limit 1) being the last tx, as it should be.

---

**2024-07-01T09:13:02**

yup...it "broke" my public NodeExplorer which uses 213 and relies on the txs  being entered in the index sequentially.
No biggie since I'm probably the only one using it when i'm "on the road" otherwise i run it locally.

---

**2024-07-01T09:16:36**

on the plus side it seems significantly faster!

---

**2024-07-01T12:14:15**

I expect the the last tx submitted to be first returned when offset=0 and limit=1. (blockchain/transactions/nyAddress)

Is that not the case with 213?

---

**2024-07-02T08:15:12**

The ordering is still not right. Before offset=0 and limit=1 would pull the last TX for that address.
Now it seems a bit random.

To see what I mean check out this: https://ergo-node-explorer.vercel.app/address/9fLYPigGHXkTyyQvU9zzoT3RTAXJ4dfHjbkg6ik2fHKKxjprSrh
This pulls the txs using /blockchain/transactions/byaddress and on old node (21) it works seamlessly pulling the txs in descending orders from latest and then backwards in time.

Using the above link now which uses 213, the first tx it pulls is from 2nd May 2024  (which isn't even the first tx for that address) and then it ascdends to 3rd 4th etc of May

---

**2024-07-02T08:21:14**

this is 213 on your snapshot node: http://213.239.193.208:9053/swagger#/blockchain/getTxsByAddress
this is  on node 21 (same I use locally) http://84.174.158.219:9053/swagger#/blockchain/getTxsByAddress
Use 9fLYPigGHXkTyyQvU9zzoT3RTAXJ4dfHjbkg6ik2fHKKxjprSrh in both of those and you can see the output is different..

---

**2024-07-04T04:45:54**

How do you send a tx with the private key? (not mnemonic)

---

**2024-07-16T11:53:40**

The node has a setting "minimum miner fee". 
If a mining pool sets this to 0 then they would mine it for free. But they won't because that makes no sense.

Default is 0.001 erg for node to accept.

---

**2024-07-25T12:00:33**

Here you go

https://github.com/FlyingPig69/Ergo_Token_Minter

---

**2024-07-25T12:02:15**

That will be $15,000 please 😜

---

**2024-07-25T18:24:24**

This is great! And the UI!! Pretty and simple!

---

**2024-07-26T05:12:21**

Here's one I created, uses python and a wallet on indexed node.

https://github.com/FlyingPig69/FP_Consolidate

---

**2024-07-28T10:16:12**

You can set list of peers in the conf file, can't remember the label/value from the top of my head but it's possible.

You'd also need to set peer discovery to false in the conf.

---

**2024-08-06T05:33:55**

Is this any reason why nodes cannot be made to accept mnemonic to send tx?

---

**2024-08-06T05:34:27**

i understsnd you might not want to send to a public node,(security as it would be stolen) but local?

---

**2024-08-06T05:42:53**

I create my own request and use the wallet/send on my node.

---

**2024-08-06T05:43:28**

yup

---

**2024-08-06T05:43:55**

yup....not literally by hand, but contructing it in python

---

**2024-08-06T05:44:24**

i can use private key, but not mneminic

---

**2024-08-06T05:44:46**

ergpy usex a jar...

---

**2024-08-06T05:45:29**

i write my own from sxratch but have not been able to figure out how to sign it using mnemonic...tried ergpy but failed as it converts the request to js a

---

**2024-08-06T05:45:50**

not a big issue but was wondering why node doesnt have sign by mnemonic

---

**2024-08-06T06:04:29**

Is it though....less safe than privatekey? less safe than api key?

---

**2024-08-06T06:06:26**

mnemonic is just a "password" that allows you to prove you are allowed to execute something...or log into something.

---

**2024-08-06T06:07:03**

User is responsible for guarding that in the same way you guard your email or banking passwords

---

**2024-08-06T07:45:59**

If you supply mnemonic and address surely there's no brute force needed?
(I guess you'll need to provide the address index (or whatever is used to determine the derived address...)

---

**2024-08-06T07:56:40**

I did try to sign using private key but failed (we had a discussion in dev-support some time back).... I might have to try again, the samples provided in swagger doesn't make much sense :)

---

**2024-08-06T07:57:00**

Which reminds me, a lot of the samples in swagger are old/don't work :p. FYI

---

**2024-08-06T07:57:45**

Special setup is what you get when a non-dev does deving with spaghetti code....:)

---

**2024-08-06T08:00:32**

Yeah, might do that. I'll try again later and move the conversation to dev support.
Thank you :)

---

**2024-08-07T10:07:13**

not an expert but I am familiar with it, used for multithread processing

---

**2024-08-07T10:07:43**

concurrencies to be specific

---

**2024-08-07T10:09:28**

or maybe you're talking about something very different...in which case "no"

---

**2024-08-07T10:12:27**

ahh...just read it, forward compatibility, something totally different...I was thinking concurrent.future

---

**2024-08-07T10:15:43**

yeah, no.......

---

**2024-08-07T10:21:11**

prefer indents to braces :)

---

**2024-08-07T10:21:33**

not a real thing :)

---

**2024-08-07T10:23:27**

not a chance!

---

**2024-08-12T03:08:23**

Agree with this.

Eternal has a simple switch between mainnet, testnet and pre-prod.

It was dead easy for people to help test splash without needing to download separate apps or tweak config files. Just click the switch

---

**2024-08-23T14:01:01**

Someone beat the sigmanauts pool to the storage rent..

---

**2024-09-10T12:04:31**

You had enough to make an awesome library!!

I've used it a lot to learn.

---

**2024-09-23T06:18:19**

oh jeez, are we moving developers into a group? 
Please don't...terrible experience on mobile and  I lose track of last posts.

When the sigmanuts group did the same I lost track of it all and forget to check and therefore post much less.

Prefer the last channel with message to appear on the top rather than the group as a whole.

E.g. within sigmanauts there's 15 channels, if anything is posted in the smaller one it appears on top....

---

**2024-09-23T06:18:23**

maybe it's just me...

---

**2024-09-24T06:53:51**

2 key pages that need some love...
Ergoplatform and sigmausd, if those are in the mix

---

**2024-09-24T06:54:13**

In that priority order

---

**2024-09-24T09:30:19**

This one should work

https://ergo-node-explorer.vercel.app/

paste the token ID.

Unfortunately kushtis node is down right now so the site won't work. Try again later

---

**2024-09-24T09:31:01**

actually, it's up again, but it's indexing. Wait until that's done. 
The red warning will be gone

---

**2024-10-03T07:37:03**

How do you force a reindexing of a node?

---

**2024-10-03T08:04:19**

this works. thanks. 
Helpful to have an API but wouldn't say it's priority over everything else right now.

---

**2024-10-09T04:22:45**

/Summarize last 100 posts...

---

**2024-11-07T07:52:05**

I would be wary of using any site where you don't have a way to contact the team....
Only two that are currently available that I would trust....

https://www.ergodex.io/ - Hosted by Spectrum finance who created the DEX Contracts
https://dex.mewfinance.com/ergo - Ran by Aaco and HQ who are well known in the ecosystem

Anything else is risky...

If I was a hacker/scammer I would host a ergodex with zero fees for a long time to become trusted (but never reveal who I am)....
And when ergo one moons and dex usage is high I'd amend the UI to send certain transactions to my wallet........

The most secure and safe way to the DEX is to host your own UI (available from the spectrum teams github site).

---

**2024-11-07T07:52:55**

(and this question is probably best asked in the main channel, not developer channel)

---

**2024-11-08T13:26:53**

Price is in R4

---

**2024-11-08T13:26:59**

And sigrsv in R5

---

**2024-11-08T13:34:47**

Rendervalue is the price of 1 sigusd...

---

**2024-11-08T13:39:26**

ahh..yeah, i don't know what R5 is actually, it renders to 3516416280  (but maybe my vlq decoder is not quite right)

---

**2024-11-08T13:42:03**

No, the smart contract is actually an address!
This here:

5vSUZRZbdVbnk4sJWjg2uhL94VZWRg4iatK9VgMChufzUgdihgvhR8yWSUEJKszzV7Vmi6K8hCyKTNhUaiP8p5ko6YEU9yfHpjVuXdQ4i5p4cRCzch6ZiqWrNukYjv7Vs5jvBwqg5hcEJ8u1eerr537YLWUoxxi1M4vQxuaCihzPKMt8NDXP4WcbN6mfNxxLZeGBvsHVvVmina5THaECosCWozKJFBnscjhpr3AJsdaL8evXAvPfEjGhVMoTKXAb2ZGGRmR8g1eZshaHmgTg2imSiaoXU5eiF3HvBnDuawaCtt674ikZ3oZdekqswcVPGMwqqUKVsGY4QuFeQoGwRkMqEYTdV2UDMMsfrjrBYQYKUBFMwsQGMNBL1VoY78aotXzdeqJCBVKbQdD3ZZWvukhSe4xrz8tcF3PoxpysDLt89boMqZJtGEHTV9UBTBEac6sDyQP693qT3nKaErN8TCXrJBUmHPqKozAg9bwxTqMYkpmb9iVKLSoJxG7MjAj72SRbcqQfNCVTztSwN3cRxSrVtz4p87jNFbVtFzhPg7UqDwNFTaasySCqM

This is the contract that contains the entire logic of the Spectrum DEX (yes, that's all of it!!).

To interact with it you need to ensure you send the correct amount and tokens in order to spend the contents...which is all handled offchain.

---

**2024-11-08T13:42:46**

(and this is also an address, you can look at it on the blockchain and see all the swaps that have happened)

---

**2024-12-06T04:35:13**

That's a solid resume you have there....

Github link?

---

**2024-12-06T06:48:00**

Good point, this would make it so that whales can mint their 16k leaving the shrimps locked out until next step, at which point they will likely do another 16k leaving shrimps out again.

There are people who mint 100k sigUSD which would then take several hours to mint blocking large amount of users.

---

**2024-12-06T17:26:17**

Doesn't that mean whales can block smaller actors from minting sigusd at a set price level

Doesn't that defeat the purpose somewhat?

---

**2024-12-06T17:28:41**

But right now,if this was implemented, you can block by minting 16000 sigusd?

---

**2024-12-06T17:34:46**

If it was 16k usd per oracle update it would be riskier to use things like duckpools...(even riskier than now).

If you use Duckpools,  you might need to "get out" quickly if price drops and you want to lock in gains. You can't do that if oracle updates block you if 16k is minted.

---

**2024-12-06T17:35:16**

you guys are the experts, but from a users standpoint, it seems restricitive and I don't understand why it needs to be that way?

---

**2024-12-06T17:38:13**

price would quickly lose peg to bank, since the arb bot cannot act to level it.

---

**2024-12-06T18:04:40**

You'd have to mint 800k right now to lock the bank. Or redeem a bunch of sigrsv.

---

**2024-12-06T18:08:13**

I'm just a user so won't go against expert advice and research :).

Tend to stay mostly away from sigUSD tbh, but would feel sorry if people could get liquidated because they can't mint sigUSD due to a low 16k limit per epoch. (As long as within the 400-800 RR)

Maybe it's the %s more than the concept.

---

**2024-12-07T05:47:41**

Is the goal with bank update to stop someone from being able to force the ratio above/below 400/800 minting a large amount of sigUSD/rsv?

---

**2024-12-07T08:25:28**

I like this. So let me el5.

Update the contracts as currently discussed which means a 0.5% limit of bank box (which today would be 16k usd).

Then work on an update where the more sigUSD/sigrsv you mint a higher fee needs to be paid whcuh goes to Oracle pool owners.
Meaning, it would be unfavoruable to mint 100k sigUSD as the fee would be too high.
Would dynamic fee be based on mints per epoch, or mints per tx? If mints per tx, people will just submit multiple tx. If mint per epoch it needs to be finely tuned.


Glad the discussion is happening at a level where us normies can understand the impact :)

---

**2024-12-19T13:42:30**

Oracle pool operators not reaching consensus??

---

**2024-12-19T13:44:37**

correct....not being updated

---

**2024-12-19T13:47:03**

it's been at 1.7662 for several hours

---

**2024-12-19T15:44:05**

If the question is "is oracle updating" then the answer is no...still at 1.7662..
Other than that, no idea. 

I'm guessing there are less than 4 oracles online (4 is consensus). Which is worrying if that's the case.

---

**2024-12-19T16:04:42**

it's updating again....gotta catch up i guess...

---

**2024-12-19T16:05:24**

Will admit it's a bit worrying that this could happen....not enough operators?

---

**2024-12-19T16:29:03**

Iove  that!
Direct interaction with contracts allows you to see what you get. It might fail, but at least you don't need refund from proxy.

And move that it used node.
Why apps use explorer when node has all you need is beyond me.

---

**2024-12-20T04:53:12**

Dex is usually cheaper for smaller amounts.

---

**2024-12-20T07:39:07**

Why? Due to the centralized part of it (server has to sit somewhere)

But I love the cold signing possibility with ergopay. if that can be done without ergopay, then it's a winner.

---

**2024-12-20T07:41:28**

That part I agree with!
But with ergopay you DO review the TX first, same as direct interaction

---

**2024-12-20T07:42:38**

Not sure what you mean...
When I scan the code my wallet tells me exactly what is going out and where it's going.

---

**2024-12-20T07:42:48**

Yes you do...

---

**2024-12-20T07:44:17**

Maybe i'm confusing something here actually.
I think of ergopay as method of signing a tx using QR codes.

I DO agree with your points on sending txs to a proxy contract, but that's not a feature of ergopay, that's the dapp

---

**2024-12-20T07:55:12**

I actually think we agree.....for the most part.

You should always be able to verify the action of a transaction, and that's not possible using proxy contracts.
UNLESS there's a standard created for proxy contracts that wallets can use to verify WHAT that proxy contract is allowed to do(possible??)

---

**2024-12-20T07:56:12**

Spectrum would not really function without proxy contracts as slippage would be a big issue.
It takes time to sign the tx (not a lot, but some) and by the time you signed it, the box you signed might have been spent.

---

**2024-12-20T07:56:25**

not so much an issue today, but might be if dexes get 100s of txs.

---

**2024-12-20T08:30:30**

On the proxy contracts/sigusd part...There's someone right now offloading 15k sigusd in batches on dex of 1000....

---

**2024-12-20T08:31:05**

they could do it all using tokenjay/sigusd/minotaur...

---

**2024-12-20T08:31:19**

feel like I should shout it from the rooftops in main channel!!

---

**2024-12-20T08:32:09**

Yeah, they are loosing 100s of $s/erg...

---

**2024-12-20T08:32:26**

BUT, they are running their own dex interface...

---

**2024-12-20T08:33:04**

https://explorer.ergoplatform.com/en/transactions/244521f0f96bc83de32c0f32cf288d125f8acdc3880b391bf0e7cd65c3c705cd

---

**2024-12-20T08:33:08**

is not a duckpools loan...

---

**2024-12-20T08:33:11**

https://explorer.ergoplatform.com/en/addresses/9hoX2vdzZAkTspWk6NddPHgs2mmUZJuqRRdvUv49cmmKhMRpiPR

---

**2024-12-20T08:33:46**

they did borrow 15k off duckpools and now selling on dex using their own interface, so it's someone with at least SOME knowledge

---

**2025-02-05T08:25:26**

Love this!!!

---

**2025-02-14T06:53:41**

delete extra in the history folder

---

**2025-02-19T10:34:46**

Regular users don't care for box selections...that should be way down backlog.

Put yourself in a total new ergo users shoes. Someone who comes from Solana or other popular chains. What are the top features for the best wallets in those ecosystems.
Copy and improve on that.

Right now, 95% of ergo users are bought in and don't need convincing, but we may need to convince new users..

A decent looking mobile wallet should be higher priority than some of the more advanced requests and accomdating the core ergo users who aren't going anywhere any time soon.
(Like Canon...he can ask for box selection, but he won't leave if he doesn't get it :))

---

**2025-03-07T05:00:41**

Has there been a rate limit added to node api recently?

My node explorer stopped working a while ago and i only got time to look into it today.
Turns out it timed out after a few api calls. (it does ~10 calls when loading the main page)

I added a retry strategy which fixed it, but thought check?

(https://ergo-node-explorer.vercel.app - shameless plug just for marketing purposes...)

---

**2025-03-07T05:21:15**

Also seems to be something wrong with 213 index?

Mew token is not found on 213:
http://213.239.193.208:9053/blockchain/token/byId/6c35aa395c7c75b0f67f7804d6930f0e11ef93c3387dc1faa86498d54af7962c

It's present in the index on other nodes (here's one...)
https://ergo1.oette.info/blockchain/token/byId/6c35aa395c7c75b0f67f7804d6930f0e11ef93c3387dc1faa86498d54af7962c

---

**2025-03-07T05:21:40**

I can add an issue if that is better?

---

**2025-03-10T08:02:56**

Wonder what explorer API has that node api doesn't and that dapps need?

---

**2025-04-28T05:45:47**

Main explorer index has some indexing issues?

tokenid 9a06d9e545a41fd51eeffc5e20d818073bf820c635e2a9d922269913e0de369d
-----
Node: http://127.0.0.1:9054/blockchain/box/unspent/byTokenId/9a06d9e545a41fd51eeffc5e20d818073bf820c635e2a9d922269913e0de369d?offset=0&limit=10000
Unspent Boxes >10000
---------------
Node: http://213.239.193.208:9053/blockchain/box/unspent/byTokenId/9a06d9e545a41fd51eeffc5e20d818073bf820c635e2a9d922269913e0de369d?offset=0&limit=10000
Unspent Boxes 189
---------------

---

**2025-04-28T05:46:17**

This is spf tokens. only 189 boxes on main node.

---

**2025-05-01T07:20:58**

The api must return full box is a pain point....

 It's inefficient to get the boxid from one API and then have to poll the node again to get the contents of that box.

Some might need only the boxid whilst others the full contents.

A simple flag would solve that (include contents=true or false)

---

**2025-05-03T15:25:16**

Does this not work for you?

curl -X 'POST' \
  'http://213.239.193.208:9053/blockchain/box/unspent/byAddress?offset=0&limit=5&sortDirection=desc&includeUnconfirmed=false&excludeMempoolSpent=false' \
  -H 'accept: application/json' \
  -H 'Content-Type: application/json' \
  -d '"9abcdef...."'

---

**2025-05-06T16:48:47**

It's the extra folder only.

---

**2025-05-08T02:24:37**

Any reasons why dapps can't use indexed nodes?

Relying on 1 or 2 main explorers seems risky as they occasionally goes down.

With Duckpools it's essential to be able to submit your tx in a timely manner as loan conditions change.

---

**2025-05-08T03:17:46**

Seems like an obvious direction to go. With ability to add your own node.

---

**2025-05-08T03:18:41**

Duckpools right now doesn't open source the UI so if UI is down and on top of that whatever explore is used is lagging you're Fu*ked.

---

**2025-05-08T04:14:35**

Yeah. I do actually know this, but I keep raising it every 6 months when we inevitably get some issues with dapps that use an explorer.
😄

We should encourage new dapps and wallets (and existing) to shift to indexed nodes.

That goes for nautilus too which currently uses explorer only.

It's one of the reasons I actually run my own explorer locally JUST in case something happens.

---

**2025-05-08T04:15:03**

But regular users won't (and should not even think about it).

---

**2025-05-08T04:15:16**

I'll raise it again in 6 months.

---

**2025-05-08T04:27:26**

Agree with the reporting aspect. Partially because there are no efficient or user friendly way to report issues.

End users won't create GitHub issues as it's cumbersome and not user friendly.

Many dapps don't have a reliable support channel which is why people vent in tg/discord.

The only dapp that has some ticket system is rosenbridge from what I've seen. They use discord, it's not efficient but it's something.

Part of the challenge is, and this is no one's fault, that projects in ergo are barebones with Devs (sometimes a single dev) having little or no funding.

The easiest thing to cut is end user support systems.

---

**2025-07-04T16:24:34**

Just synced node6.0.

When I restored a wallet and derived the next address number 2 and 3 was identical addresses. The ones after that were as expected.

---

**2025-07-04T16:30:19**

swagger /wallet/addresses

They also show on the node wallet page under addresses

---

**2025-10-29T11:56:11**

Sigmausd Oracle is stuck on 1644679

---

**2025-10-29T11:56:36**

That's all i wanted to say, i'll close the door on the way out...

---

