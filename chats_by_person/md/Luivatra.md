# Luivatra

**Total messages:** 697

---

**2021-12-23T10:59:26**

you can use mine, I have a lot :D

---

**2021-12-23T10:59:51**

9fbzAZAQauntRwsnCNFPb7DzT7854qWp4uxeWrhgiscW43aFGfN

---

**2022-01-08T06:18:45**

you removed the other tip bot?

---

**2022-01-08T06:19:03**

then I will change the command to /tip instead of /testtip

---

**2022-01-08T06:20:20**

/testtip 1 thisguyfucks for your wallet work! :)

---

**2022-01-08T06:25:56**

/t 1 thisguyfucks all wallet devs fuck (I feel way too old for saying this stuff lmao)

---

**2022-01-08T06:33:21**

ill have a look in the logs

---

**2022-01-08T06:37:12**

hmm, sometimes the generation of a new wallet seems to fail

---

**2022-01-08T06:39:47**

can you try tip the same guy again?

---

**2022-01-08T06:42:03**

👍

---

**2022-01-11T01:45:19**

@mhs_sam in the ergoprofitsharing scripts you use a hash of the ergotree bytes to check the output box has the right contract guarding it. Is that to make the script smaller?

---

**2022-01-11T03:17:22**

Awesome, will look at implementing that in python as well.

---

**2022-01-13T07:24:42**

It seems very simple

---

**2022-01-13T07:24:56**

hah, just needed to complain about it

---

**2022-01-13T07:25:00**

speak to the manager

---

**2022-01-13T09:24:04**

Feedback is welcome!

https://github.com/ergo-pad/ergopad/blob/staking-contracts/backend/app/contracts/staking.md

---

**2022-01-16T02:25:23**

Is it an L1 or sidechain or what? They say watch out solidity so I think running on EVM but then it later in the article sounds like it is their own chain?

---

**2022-01-16T14:59:38**

Sign a piece of data?

---

**2022-01-16T18:01:55**

Well it is always a tx. You can of course keep the boxes on the same address, but to change data in registers you need to spend the box and recreate it with new register values

---

**2022-01-17T00:06:36**

No dont know that

---

**2022-01-17T03:38:34**

Wth 🤣

---

**2022-02-06T15:48:48**

Thanks :)

---

**2022-02-08T09:13:58**

yikes

---

**2022-02-08T14:22:25**

Make sure to reserve some time, that is like syncing a full node**2 😅

---

**2022-02-08T14:23:27**

yes

---

**2022-02-08T14:24:19**

we started shortly after the issues around neta launch and it is still syncing (above 600k now so almost!). Running on a virtual machine though so might be throttled somewhere

---

**2022-02-08T14:25:19**

Yeah think so, might be ways to improve sync time, but I dont know @ergopad_leif is running it

---

**2022-02-08T15:58:18**

You can see an explorer as a node with the data in an indexed db, so search can be optimized. So guess some things are easier to do on explorer

---

**2022-02-26T04:16:11**

Yeah, setting maxtransactioncost in config doesnt seem to help. Will make an issue.

---

**2022-02-28T04:00:28**

how much from scratch are we talking here? Any coding experience?

---

**2022-02-28T04:04:40**

in all cases it is important to understand how eutxo works, because that will influence how a dapp is built

---

**2022-02-28T04:05:22**

https://docs.ergoplatform.com/dev/

---

**2022-03-28T13:03:26**

Not just .24 .23 as well

---

**2022-03-28T13:03:41**

Seems like network is stuck

---

**2022-03-28T13:57:46**

Only 40ish in0uts and outputs

---

**2022-03-31T09:22:09**

trying to scam in a dev channel lmao

---

**2022-04-15T02:41:36**

Is there a limit on confirming transactions per address per block? When running compound I submit fe. 20 chained transactions fairly shortly after eachother, but they only get confirmed 3 at a time.

---

**2022-04-15T03:37:20**

hmm, could be the issue I guess. JIT should help quite a bit though

---

**2022-04-26T02:09:33**

this only relates to mining reward transactions I assume?

---

**2022-05-09T00:14:18**

You can just read the oracle utxo. The info is all there in the registers

---

**2022-05-10T12:56:14**

What do you mean, how they get erg rewards?

---

**2022-05-14T23:02:48**

The way its build kind of prevents an open api sadly

---

**2022-05-15T01:45:36**

I would suggest using sigma rust or appkit to generate those wallets and show a qr code or something for the tip. Dont think the tip bot makes fits in this scenario

---

**2022-06-08T05:41:29**

you sign boxes though, so that would still basically lock the funds or else the tx wouldnt work

---

**2022-06-08T05:42:33**

guess if you want you can make a bank service that could handle things like this (maybe even on a L2 like scalahubs example)

---

**2022-06-10T05:32:20**

Ergopad staking depends on burning working like it does now, wallets should probably just write in big letters at the top what gets burned in a tx a user is about to sign.

---

**2022-06-10T05:45:21**

But that wouldn't prevent this situation, because the dapp doesn't use the burn address

---

**2022-06-10T07:03:55**

That would break ergopad staking though, basically locking stake until no penalty is applied.

---

**2022-06-13T10:32:31**

Yeah that would be great!

---

**2022-06-13T15:49:22**

I think there is a pretty print, but to call it human readable is a stretch imo, although it could maybe be readable if it gets some formatting?

---

**2022-06-18T07:50:54**

why not just mint?

---

**2022-06-23T06:01:18**

certainly useful, just needs to be able to take parameters/constants as well

---

**2022-06-27T06:02:37**

you mean 5.0 right? Almost done preparing a "tx cost" test setup for staking to compare tx cost values on 4.0.31 and 5.0

---

**2022-06-30T09:00:37**

Only issue I could see is it not playing well together with p2s input box, but could be resolved by making an intrawallet tx to spend the box, unless that doesnt work

---

**2022-07-08T11:28:09**

yeah eip mentions 255, guess stored in a short

---

**2022-07-08T11:30:07**

oh I see your comment now, yes

---

**2022-07-08T12:37:59**

Based on sigmarust, so could have happened in a lot places

---

**2022-07-08T13:02:15**

I would expect that limitation to be an issue even without nft's. Tokens with value, vesting keys, staking keys etc. Who knows what we deal with a year from now

---

**2022-07-08T13:42:26**

Agree 100%

---

**2022-07-09T02:33:46**

It could be a check in the endpoint that takes in transactions, add a tokensToBurn structure that the explorer/node can verify, but not change the protocol itself

---

**2022-07-09T02:34:09**

damnit kushti, too fast!

---

**2022-07-09T02:37:21**

Tbh, I think that would be an ok solution? I am more than happy to adapt the ergopad burning code for unstaking to safeguard people

---

**2022-07-11T07:14:22**

Probably easier to wait for babel fees implementation before you fork

---

**2022-07-19T06:11:05**

No

---

**2022-07-23T11:57:36**

Yeah, I need (ergoid, long) for staking but wouldnt want to be restricted to defaults in future

---

**2022-07-25T13:32:50**

hmm maybe I should just switch our entire code base to ASM 😅

---

**2022-07-29T05:27:36**

Didnt 35 have more aggressive peer removal on failure to deliver?

---

**2022-07-31T13:36:44**

Shit, I know its a bear but that is maybe taking it a bit far

---

**2022-07-31T13:38:51**

Too late! Already booked a flight!

---

**2022-07-31T13:39:22**

That is my big question as well

---

**2022-08-02T16:17:08**

True devs have no clue what day it is 😂

---

**2022-08-14T00:29:25**

I use it in my bots, although it would be possible to switch to just getting the transactions from the blocks.

---

**2022-08-15T14:34:51**

Allow for usage of node instead of explorer for certain apis

---

**2022-08-18T15:58:15**

Right that would work as well of course

---

**2022-08-18T16:00:35**

Yes, much easier to ensure correctness

---

**2022-08-18T16:58:02**

Could a "gap" in the data occur if due to congestion the tree isnt updated within 10 blocks?

---

**2022-08-18T17:00:22**

Still, interesting nonetheless, feels like we are only scratching the surface of what is possible

---

**2022-08-19T04:24:29**

Yeah I believe so

---

**2022-08-26T08:56:07**

dont know if you are doing anything with them right now, but I am seeing transactions appear and disappear on the explorer, maybe one of the nodes is having issues?

---

**2022-08-26T08:57:03**

no this is confirmed transactions

---

**2022-09-04T06:11:16**

Cant burn erg, its just some weird p2s address

---

**2022-09-19T05:16:40**

That would be nice

---

**2022-09-19T05:30:18**

well you can just pass the same data in the context extension, but of course it will be a waste of space

---

**2022-09-19T05:31:16**

ah I see your point yes

---

**2022-09-19T05:33:41**

yeah, question is, is there a reason it is not supported or just an oversight? would it be possible to add in this functionality with a soft fork?

---

**2022-09-23T06:55:52**

Had no idea it was that common

---

**2022-09-27T05:08:50**

Activation could happen within a fairly short period (days?) What would the impact be if not all exchanges are on the new version?

---

**2022-10-03T02:22:04**

sure, was just looking at it, very simple actually cause the algorithm didnt really change, just the parameters + the capping at 50%

---

**2022-10-04T06:24:23**

@MrStahlfelge awesome consolidation feature on tokenjay. One of my wallets says oldest utxo is 3.2 years. Which I doubt :)

---

**2022-10-04T06:42:28**

oof, will have a look at what box it is

---

**2022-10-04T06:46:10**

and the culprit is.... Spectrum 😅

---

**2022-10-04T06:46:47**

so storage rent is based on creation height not settlement height?

---

**2022-10-04T06:51:21**

isn't that an issue? cant even protect from it in ergoscript

---

**2022-10-04T06:56:46**

yeah I see that, but if we have decentralized off chain code how do we prevent someone from setting the creation height to 0 and let it be taken by the miner on the next block

---

**2022-10-04T06:59:43**

someone could do an emission transaction for ergopad staking and set creation height on the new stake pool box to 0

---

**2022-10-04T07:00:56**

no, I am talking about malicous actors

---

**2022-10-04T07:01:43**

no, anyone can sign the contracts

---

**2022-10-04T07:02:01**

similar to the spectrum bots

---

**2022-10-04T07:02:33**

yes, although impact wouldnt be too big due to it having a lot of erg

---

**2022-10-04T07:04:29**

I assumed that was settlementheight

---

**2022-10-04T07:04:34**

but I can see now why it isnt

---

**2022-10-04T07:05:15**

Well, happy to find out now, and not when storage rent hits

---

**2022-10-04T07:50:47**

thank you for that :)

---

**2022-10-04T07:52:13**

ah right, didnt think of that!

---

**2022-10-04T08:08:06**

you didnt create an issue, you brought it to light, so ty (not sarcastic lol)

---

**2022-10-04T08:17:36**

think it depends on box size?

---

**2022-10-05T02:27:33**

So instead of focussing on 6.0 after 5.0 activation maybe we should focus on a storage rent SF. There is also the "what to do with tokens" issue when a large amount of tokens is in a box with low amount of erg and it is taken by storage rent, what happens with the tokens

---

**2022-10-05T04:08:33**

think he meant signing, but first submitting in the future

---

**2022-10-05T04:12:25**

yeah, 2 different cases

---

**2022-10-05T04:13:06**

what restrictions are there on creation height of the resulting utxo when a miner takes storage rent?

---

**2022-10-05T04:13:22**

if there are no restrictions he could set the creation height to 0 and take rent again next block

---

**2022-10-05T04:48:23**

this sounds good

---

**2022-10-05T04:49:42**

higher or equal (for chained tx)

---

**2022-10-05T04:55:18**

maybe we should put this on the forum so we can have a structured discussion

---

**2022-10-05T04:56:13**

certainly agree with this 😅

---

**2022-10-05T05:00:20**

oh that is great!

---

**2022-10-05T06:09:54**

also, creation height being lower than creation height of the inputs does not make much sense

---

**2022-10-05T14:11:45**

no

---

**2022-10-05T14:44:16**

NFT's on ergo are native, no need for smart contracts

---

**2022-10-06T02:23:23**

that same tx is still in mempool on explorer (at least in the UI) so can use that node to investigate I guess

---

**2022-10-06T02:31:42**

the tx was confirmed almost 24 hours ago, but is lingering in some mempools

---

**2022-10-06T02:35:23**

my guess (without knowing anything about the inner workings of the node) would be some fork handling logic not cleaning the mempool properly

---

**2022-10-06T10:46:53**

Yeah it was a neta stake tx

---

**2022-10-06T10:47:08**

Not submitted by me though

---

**2022-10-11T13:49:24**

Yeah, an end tag, this is where you go to stop with what you are doing and just dev

---

**2022-10-11T13:51:28**

Hey, HTML was my first programming language! (or so I thought when I was 11 😂)

---

**2022-10-11T13:52:42**

Would still take a phd to figure out what the hell was going on in MS Frontpage generated HTML

---

**2022-10-13T15:47:25**

Nothing special, think the appkit just needs to see block version 3 in the header

---

**2022-10-14T08:55:53**

.tps

---

**2022-10-14T09:07:24**

high tps is the domain of L2, doesnt make sense to cause bloat on L1

---

**2022-10-20T06:49:01**

maybe tweets costing something is not a bad thing looking at the load of worthless trash that gets posted on twitter 😂

---

**2022-10-31T15:16:38**

doesnt it cache though?

---

**2022-11-17T16:25:07**

@oskin regarding SPF, could you mint 2billion (instead of 1 billion) on both ergo and cardano and keep 1 billion to lock into rosen bridge on both sides once rosen is ready? that way they would both be native on each side and use the bridge once ready (if locking tokens in the bridge like that is possible @mhs_sam )

---

**2022-11-22T05:26:32**

that doesnt give double spent error?

---

**2022-11-23T10:15:30**

Need a trustworthy oracle source for it

---

**2022-12-04T14:03:10**

Complaining on twitter is much easier than writing an EIP

---

**2022-12-17T18:24:36**

Cant message be in context var of the users' first utxo input?

---

**2022-12-19T13:50:10**

P2pk utxo wont look in context variables

---

**2022-12-19T14:01:51**

Think they do sadly, think i got error about it

---

**2023-01-07T10:25:09**

Try use the new ergovaluebuilder

---

**2023-01-07T10:28:10**

https://github.com/ergoplatform/ergo-appkit/blob/develop/common/src/main/java/org/ergoplatform/appkit/scalaapi/ErgoValueBuilder.scala

---

**2023-01-08T15:35:35**

yeah, wth @oskin you cant just post a tease like that 😂

---

**2023-01-08T15:38:08**

I asked chatgpt to make println work in ergoscript but for some reason it didnt work....

---

**2023-01-12T01:38:09**

No need to go through the trouble of writing a python->ergotree compiler if the existing language doesnt suck 😅

---

**2023-01-12T01:40:35**

Awesome news for cardano though!

---

**2023-01-18T01:14:39**

one of the main reasons I tried Scala is Ergo 😂

---

**2023-01-18T06:44:54**

@kushti_ru some ghost transactions in (one of) the explorer mempools

---

**2023-01-27T06:00:53**

https://api.ergopad.io/projects/16

---

**2023-01-27T06:16:16**

Been there done that

---

**2023-01-31T12:22:47**

IRS wants to know your location

---

**2023-02-07T13:48:13**

maybe only use 1 node for mempool stuff if possible? to keep it consistent

---

**2023-03-06T08:04:02**

actually, the tokenid is already written to a register (R2?)

---

**2023-03-06T09:16:26**

Why use tokens for it though? Can just store the data in registers. Or do you have a use case for the tokens?

---

**2023-03-06T09:19:10**

But a token holds no data, you could just pass someone the box id of the first box in the chain

---

**2023-03-06T09:34:12**

Which one you using, ergpy?

---

**2023-03-07T04:47:19**

Why not use "it" 😅

---

**2023-03-20T04:40:53**

good, the wallet rescan is slow indeed

---

**2023-03-25T13:56:50**

The goal of storage rent is avoid dust & bloat, a box with 1k erg is no dust or bloat

---

**2023-03-26T14:37:12**

It combines some transactions into one, fe. swaps on spectrum

---

**2023-03-31T10:34:37**

Yeah, guess I could do that, just might be an issue if minimum fee changes

---

**2023-03-31T11:25:30**

yeah, will probably do that, either that or just a context var, could be he isnt smart enough to change the context var 😅

---

**2023-03-31T16:57:49**

Sorry about that, one of the paideia contracts is a bit big

---

**2023-04-03T10:43:39**

Doesnt even know how to mass mint, he must be new here

---

**2023-04-12T23:11:38**

Have you successfully send a simple transaction? Probably best to start with that, send 0.1 erg from one p2pk to anothet

---

**2023-04-12T23:51:31**

Minting an nft is a special type of transaction so make sure you can make a simple transaction first

---

**2023-04-14T05:42:34**

he would need to mint the zengate token, create babel fee boxes (with erg) and then make the minting tx more complex because of the need to include the babel box in the input and output. That is just minting with erg with a lot of extra steps :P

---

**2023-04-14T05:44:32**

I dont think Dan needs extra complexity in the minting process 😁

---

**2023-04-14T05:46:49**

its like you said, you need to get over that initial hurdle, it gets easier

---

**2023-04-14T05:49:27**

yeah, huge benefit both ways when a team lead kind of knows what is going on under the hood

---

**2023-04-14T05:51:51**

I started my professional career in PL/1 on z/OS mainframe and no I am not that old, just started at a dinosaur bank 😂

---

**2023-04-14T05:52:28**

well at least you are not carrying the punch cards to the compiler old

---

**2023-04-14T05:55:45**

These younguns dont know how good they have it! Now get off my lawn!

---

**2023-04-15T06:09:02**

Wouldnt that conversation happen in the gh issue though? Do agree this chat should be for dev related chatter, but can still have a bit of banter now and then

---

**2023-04-15T06:14:20**

No, funny banter only 😉

---

**2023-04-17T11:45:08**

Dont see why not

---

**2023-04-17T11:45:39**

Just have less space inside a box than context

---

**2023-04-17T11:50:19**

Just need to perform the same operations in the same order

---

**2023-04-17T12:04:30**

Its not that bad if you keep the state in between transactions. Off course takes a bit to sync from scratch

---

**2023-04-23T13:14:27**

Could take the indexed node ui further

---

**2023-04-23T13:16:51**

https://github.com/Luivatra/indexed-node-explorer

---

**2023-04-27T13:20:48**

Every token transfer on cardano needs a couple of ada attached to it

---

**2023-04-27T13:21:33**

Easy to get used to ergo tx fees

---

**2023-04-27T14:18:17**

no, it is not a tx fee, the receiving address gets the ada

---

**2023-04-27T14:18:45**

reward for watchers and guards

---

**2023-04-28T10:15:13**

doesnt the node complain if the cost is too high?

---

**2023-04-30T04:31:02**

yeah, mine is as well

---

**2023-04-30T14:42:44**

Isnt that a placeholder for an actual address?

---

**2023-04-30T14:52:03**

Ah ok, just use regex 😆

---

**2023-04-30T14:55:07**

Yeah, annoying

---

**2023-05-01T11:39:05**

I am going to update my node just to mess with your statistics

---

**2023-05-01T12:32:45**

The misconception is that batchers are inherently not decentralized. Its only if they are not freely available and closed source

---

**2023-05-02T10:46:21**

That has been an issue for a while, guess the generation breaks because multiple return types use the "items" field. Could use the indexed node for this specific endpoint though

---

**2023-05-03T15:16:51**

1/R6*10^9

---

**2023-05-08T09:54:22**

about time miners wake up

---

**2023-05-08T23:21:50**

Think he meant that the node doesnt accept tx with outputs with creation height smaller than max creation height of the inputs

---

**2023-05-12T11:38:19**

Can confirm

---

**2023-05-17T10:28:43**

Probably too many transactions

---

**2023-05-31T15:15:07**

Doesnt fleet have this built in though?

---

**2023-05-31T15:15:40**

https://github.com/fleet-sdk/fleet

---

**2023-05-31T15:16:19**

I dont do js though so dont know how well it works but made by nautilus dev so xant be too bad

---

**2023-06-02T07:54:41**

I put a max on it in the contracts. Then it is up to the bot operator to decide how much goes to the miner and how much to the operator

---

**2023-06-02T11:29:09**

Nothing scientific right now

---

**2023-06-08T01:09:27**

Doesnt sound like that is the end goal, what are all addresses needed for?

---

**2023-06-09T14:51:23**

Needs to be less than max utxo size, but of course need room for registers as well

---

**2023-06-09T14:53:23**

If really needed you can split the contract up into multiple utxos

---

**2023-06-09T16:48:25**

I have had issues with multi parameter custom functions in some cases, not sure why

---

**2023-06-12T02:33:37**

Gonna go out on a limb, but probably because noone has had the time and motivation?

---

**2023-06-13T06:12:43**

you can pin only your own stuff and not keep anything else stored afaik

---

**2023-06-20T22:02:32**

Trying to scam in the dev channel 🤦‍♂️

---

**2023-06-23T11:24:02**

Global index

---

**2023-06-23T12:30:49**

Yeah, it should

---

**2023-07-03T04:43:16**

was it a treasurywithdrawal with some "extra" withrawal on the side?

---

**2023-07-03T04:51:53**

not all, need to leave 10000000L nanoerg in 😂

---

**2023-07-03T04:52:56**

well this is a valuable lesson to a lot of people, thank you krasa for not making it an overly painful one

---

**2023-07-03T04:54:48**

not just that, important to learn that noone is infallible, we are all human, that is why blockchain+open source+time is so important

---

**2023-07-03T04:55:06**

people forgot about the time aspect because it came from trusted people

---

**2023-07-03T05:12:53**

yeah not sure how to handle the LP, luckily not too big, but someone could dump their hodlerg on spectrum after getting the refund from you

---

**2023-07-03T05:13:32**

maybe give people some time to remove liquidity from lp

---

**2023-07-04T03:12:06**

people might feel burned and dont want to jump in again

---

**2023-07-04T03:17:14**

Having a look, but 5% dev fee seems a bit much ;)

---

**2023-07-04T03:19:03**

I figured :)

---

**2023-07-04T12:34:10**

Price equalled 0 cause tvl was basically 0

---

**2023-07-04T12:38:40**

Can upcast any value you need to compare with to bigint

---

**2023-07-04T14:56:10**

I usually write proxy from user pov and main contract from protocol pov. Proxy protects user, main protects protocol

---

**2023-07-04T15:40:52**

Lol, I know the feeling

---

**2023-07-09T15:13:14**

It is tough to decide and the best option probably depends on specific usecases

---

**2023-07-10T13:56:34**

Is the type enforced or just syntactic sugar?

---

**2023-07-14T09:03:17**

Oops 😅

---

**2023-07-17T23:54:49**

Awesome, will look at it

---

**2023-07-18T01:15:14**

think the issue is that the settlementheight of an input box is not known when evaluating a transaction

---

**2023-07-18T01:18:00**

sadly not themselves, someone ran modified spectrum off chain bots that set creation height to 0

---

**2023-07-20T09:13:37**

All I need is block header id and tx id for mempool transactions, rest I can fetch from api

---

**2023-07-20T09:13:48**

Will send error later

---

**2023-07-20T11:36:59**

beautiful, will try it out tomorrow

---

**2023-07-23T16:59:32**

Sorry didnt get to it yet, will make time for it tomorrow

---

**2023-07-24T03:44:29**

Getting this error, running on 17:
[10:43:16] Received ID(s) of transaction(s) in Inv message: 2d0babb062faab5fe70dd691bc4c141b5ebef46f6cc804c0a8cf8bb7928e27f0
Exception in thread "main" java.lang.NoClassDefFoundError: org/bouncycastle/jcajce/provider/digest/Blake2b$Blake2b256
  at com.satergo.ergonnection.ErgoSocket.send(ErgoSocket.java:85)
  at com.satergo.example.TransactionLoggerExample.<init>(TransactionLoggerExample.java:44)
  at com.satergo.example.TransactionLoggerExample.main(TransactionLoggerExample.java:65)
Caused by: java.lang.ClassNotFoundException: org.bouncycastle.jcajce.provider.digest.Blake2b$Blake2b256
  at java.base/jdk.internal.loader.BuiltinClassLoader.loadClass(BuiltinClassLoader.java:641)
  at java.base/jdk.internal.loader.ClassLoaders$AppClassLoader.loadClass(ClassLoaders.java:188)
  at java.base/java.lang.ClassLoader.loadClass(ClassLoader.java:525)
  ... 3 more

---

**2023-07-25T05:50:17**

working good now, also realized for my usecase I dont need to send any messages, the transaction/header id's are all I need

---

**2023-07-25T06:02:11**

blocking, all worked fine (used it from scala 2.13 btw)

---

**2023-07-25T06:04:27**

apparently up to jdk 21

---

**2023-07-25T07:01:13**

the socket's connection gets closed every 10 minutes, maybe because I dont send anything over it?

---

**2023-07-25T07:21:21**

yeah, requesting modifiers seems to have solved that

---

**2023-07-25T10:38:14**

yeah, already made it before sending modifier request messages, so should be fine :)

---

**2023-07-26T05:18:34**

one more question, getting quite a few errors where the magic bytes are not correct (fe. " incorrect magic [31, -4, 74, -43] (must be [1, 0, 2, 4])"). I am just ignoring them but wondering if you noticed the same

---

**2023-07-26T05:21:46**

no, only my own, but that one is connected to random I guess

---

**2023-07-26T05:24:31**

my node is a few versions behind, maybe time I update it anyways

---

**2023-08-02T04:48:57**

what kind of transactions?

---

**2023-08-02T05:21:14**

If you do it fast previously submitted tx hasnt reached ergopad node yet so it builds next with inputs already used in first tx

---

**2023-08-02T05:24:49**

More an issue with ergopad than the chain, need to update the code, its old

---

**2023-08-05T02:19:27**

Just because there is a misunderstanding doesnt mean there is an unwillingness to listen. I suspect making it more power efficient could hurt the asic resistance, but really need someone that knows what theyre talking about to way in.

---

**2023-08-09T14:49:31**

What is ouch about that?

---

**2023-08-10T01:19:30**

Crux going rust as well

---

**2023-08-14T16:16:39**

Good question. Gets really buggy sometimes when it hits that so I have been reconnecting when it happens. Seems to work fairly well

---

**2023-08-14T17:02:55**

Not really, usually the magic is empty, maybe it just didnt receive it yet. Cant remember if I have seen it non empty

---

**2023-08-14T17:04:31**

And yeah, connected to my own node only

---

**2023-08-14T17:09:13**

Sorry, didnt realize it until now that it was showing empty magic in the error msg

---

**2023-08-15T11:36:29**

The chain part makes that a self answering question 😋

---

**2023-08-15T11:37:30**

How to chain across multiple mempools if part of the chain is not present

---

**2023-08-15T11:37:48**

(In the same mempool)

---

**2023-08-15T11:52:21**

Gotta throttle, you young whippersnapper!

---

**2023-08-16T04:23:57**

Will do tomorrow!

---

**2023-08-20T12:42:19**

What in the ocd is that 😂

---

**2023-08-20T12:47:22**

Well if the ocd is that strong they can do the math :p if there is a fee on paying a bill it wouldnt change the amount on the bill either

---

**2023-08-21T05:02:19**

@mewtoshi at first glance it all works fine, also managed to extract the height from the new blocks so mgpai should be happy :P

---

**2023-08-21T05:02:27**

will keep it running to see if it is stable as well

---

**2023-08-21T05:07:33**

aint nobody got time for selecting an emoji

---

**2023-08-22T23:41:16**

Dif adjust changed after that so I would say it is not irrelevant, but statistics after that would be interesting

---

**2023-08-23T14:52:52**

think I use it as well to make a clone of a tree

---

**2023-08-23T14:59:59**

That is what I use it for as well, and taking staking snapshots

---

**2023-08-30T10:30:03**

I am also at around 10hr for indexing crux db. I am sure it can be cut down, but tough to spend a lot of time optimizing a "one time" operation

---

**2023-08-30T10:39:57**

yeah. I focused on a simple basic data model, further "indexing" is done by performing heavy operations and put result in tables, for example extracting all spectrum liquidity pool boxes

---

**2023-08-30T10:40:32**

so havent had a need for working from scratch, only for specific sub tables

---

**2023-09-04T15:39:43**

Oh that is interesting, what will timestamp be?

---

**2023-09-04T16:23:24**

So no change there

---

**2023-09-04T23:32:27**

This would help with making storage rent tx's

---

**2023-09-05T01:41:43**

at least that is what I put together when he tagged you 😅

---

**2023-09-07T06:03:32**

Not sure what the full package program means, but I would suggest finding a few simple tutorials to learn the basics of programming, followed by back-end and front-end programming. Then see if you like it and which part you like more (front-end or back-end). There is nothing super special about an ergo developer compared to any other developer

---

**2023-09-07T06:12:59**

think it seems to cover both frontend and backend, so that is good. Opinions may vary on c#/.net but I like the language and in the end the language is not that important

---

**2023-09-07T06:17:18**

it deosnt really matter which language you learn as long as you keep in mind that the important things to take in are not language specific, but more algorithms and data structures. When you realize that you can use any language whenever it makes sense and still use your experience in other languages

---

**2023-09-07T06:18:08**

in the end it is still html and css what comes out of javascript sites right?

---

**2023-09-07T06:28:09**

Yeah kinda agree on that

---

**2023-09-07T06:29:37**

Google says it is ok

---

**2023-09-09T15:46:26**

Isnt that why api is versioned? Just make v2 version of same endpoint

---

**2023-09-12T13:56:29**

I have had something in appkit complain when not using consecutive indices, just an fyi

---

**2023-09-12T13:58:43**

No I mean context var's. Not sure if intended

---

**2023-09-12T13:59:03**

oh nvm, I see now you talk about something else

---

**2023-09-12T14:08:55**

Just so I understand the discussion, DeserializeContext = executeFromVar in ergoscript?

---

**2023-09-14T15:13:38**

Heavy metaldata, nice

---

**2023-09-15T02:30:09**

Application.conf is the defaults, ergo.conf overrides whatever you define in there

---

**2023-09-15T02:47:58**

Think mainnet.conf comes in between

---

**2023-09-15T03:17:10**

I am liking Rust for small microservices, because of the very low resource usage. There will never be a single language best for everything. If the rust node gave Kaspa a big boost it is probably because the old code was no good. If your code is no good and a big refactor is needed it is easier to sell that it is to use a new language than to say your old code is shit.

---

**2023-09-15T03:17:37**

In totally unrelated news I will over time switch ergopads backend to Rust because Python sucks

---

**2023-09-15T03:18:11**

Yes, but I dont like my code 😂

---

**2023-09-15T03:20:17**

Python puts a lot of trust in the discipline of the programmer to produce good code, when you are (one of the) only dev on a project and stuff needs to be done fast it is tough to be disciplined like that

---

**2023-09-15T03:21:43**

yeah, weak typing requires strong programmer

---

**2023-09-16T09:39:46**

Ergo is still a small db and not that many users are hitting the db, it is the explorer datamodel that is the issue

---

**2023-09-16T09:43:58**

and I dont say that blaming anyone, making a well performing datamodel is not easy, but once you have a well performing data model sql is ridiculous in what it can do

---

**2023-09-16T09:46:10**

the portfolio query for crux was performing "ok" returning in 3 seconds, but I am usually not happy when it is more than 1s, so dug in, added 1 index supporting a join and it went down to like 0.5s

---

**2023-09-16T09:47:45**

just think the explorer data model with a table with outputs and a table with inputs doesnt work well, because you end up joining a lot of data just to get the small % that is unspent, which is what is most interesting for a lot of use cases

---

**2023-09-16T09:48:12**

have a lot of work experience, mostly mssql but a lot of stuff translates

---

**2023-09-16T09:48:57**

learn how to get a query plan for the query you are firing off, look at what is taking a long time and try to solve that

---

**2023-09-16T09:50:21**

in pgadmin you can turn on timing in the explain

---

**2023-09-16T09:51:47**

should have something similar in whatever db you use

---

**2023-09-16T09:52:44**

anyways, I am not a specialized db engineer but with a bit of effort you can get the basic knowledge around indices etc. and should help a lot

---

**2023-09-16T09:57:09**

funny thing is on my first job I worked on mainframe with DB2 db, when trying to deploy something with a query in it it would automatically run a query plan analyzer and if it sucked they would stop the deployment and tell you to try again

---

**2023-09-18T21:12:56**

Look in paideia-state code ;) box size in bytes * 360

---

**2023-09-25T01:13:43**

Pure tps is only relevant for chains that only transfer coins. Any other chain will have a variable transaction size/complexity making tps impossible to pin down

---

**2023-09-25T01:14:39**

If you want to compare fix the transaction to a known simple value for size & complexity

---

**2023-09-25T09:43:36**

Should be times blocks/min?

---

**2023-09-25T12:41:24**

Cost is ergotree complexity based

---

**2023-09-26T09:47:33**

I am thinking about turning off the eth/usd oracle. Is anyone using it?

---

**2023-09-27T12:29:51**

That is absolutely amazing

---

**2023-09-30T12:12:41**

Just look at the blockchain

---

**2023-09-30T12:14:57**

Quickest would be explorer api, boxes/unspent/byTokenId/{pool_id} then just divide tokens by erg value

---

**2023-10-04T11:34:14**

doubt it can be prevented 100% tbh, so tools to fix it should be user friendly I guess

---

**2023-10-04T11:43:16**

yeah, but wallets depend on explorer atm and explorer dies on that many utxos

---

**2023-10-06T06:05:35**

same reason the first bag of heroine is

---

**2023-10-06T06:06:07**

but it sure is a big bag

---

**2023-10-09T07:33:33**

I know appkit gets confused when calculating change amounts (it only takes one amount per token per box)

---

**2023-10-09T07:33:54**

is node using same logic?

---

**2023-10-09T07:35:06**

yeah I have seen boxes with the same token multiple times

---

**2023-10-09T09:06:57**

nice, good to know!

---

**2023-10-09T09:07:21**

I tend to make workarounds and never check if the issue has been fixed 😅

---

**2023-10-10T11:43:59**

most endpoints have offset & limit query parameters

---

**2023-10-10T11:48:21**

offset = 0
limit = 100
done = false
while !done
  response = apirequest("...?offset={offset}&limit={limit}
  if len(response) < limit
    done = true
  offset += limit

---

**2023-10-10T11:49:08**

only annoying thing sometimes is that orders is sorted with newest first, meaning if while you are cycling through pages a new entry will shift everything

---

**2023-10-10T20:43:36**

Show coinbase & scripts

---

**2023-10-12T00:11:52**

Hehe, a significant % of all ergo boxes have been holding that token on that address

---

**2023-10-12T07:09:58**

not sure how ergpy does it, but shouldnt you specifiy box_id's for inputs rather than address?

---

**2023-10-12T07:12:37**

its just in most cases when having p2s input you need a specific box, not just any from that address

---

**2023-10-17T05:45:29**

Until they change the contracts 😉

---

**2023-10-17T06:36:31**

Sure, but new contract would mean improvement so they might encourage moving liquidity over. Anyways, not really relevant right now

---

**2023-11-10T01:18:36**

There is update

---

**2023-11-10T01:22:02**

https://github.com/ScorexFoundation/sigmastate-interpreter/blob/develop/docs/LangSpec.md#avltree

---

**2023-11-10T04:14:41**

Think its in eip 4

---

**2023-11-10T04:25:59**

Yes, eip 4 is a meta data standard for token minting but believe it describes what you just wrote as well

---

**2023-11-10T04:28:42**

Agree!

---

**2023-11-10T04:34:43**

The average crypto investor doesnt care about elegant design, but elegant design gives a stable foundation and longevity, it will come

---

**2023-11-13T01:09:03**

I will give an example when I get to my pc

---

**2023-11-20T01:59:25**

You could use .slice to look for a sequence of bytes I guess, but not sure it would work

---

**2023-11-20T02:38:54**

Yeah that is going to be difficult to implement in eutxo I think

---

**2023-11-20T03:29:03**

Interesting idea

---

**2023-11-20T04:15:58**

how do you force the inclusion of a dataInput in every transaction a certain token is in

---

**2023-11-20T04:18:13**

this is a huge pro or a huge con of ergo depending who you ask :D

---

**2023-11-21T00:12:01**

@kushti_ru my node was using quite a lot of cpu and saw a lot of misbehavior penalties in the log

---

**2023-11-21T00:15:17**

and it keeps being the same ip that gets the misbehavior penalty

---

**2023-11-21T00:17:38**

956726-mn-ergo-node  | 06:16:56.278 INFO  [tor.default-dispatcher-30] s.c.n.PeerConnectionHandler - Send message MessageSpec(22: RequestModifier) to ConnectionId(remote=/15.235.13.47:9030, local=/172.21.0.2:42058, direction=Outgoing)
956953-mn-ergo-node  | 06:16:56.486 INFO  [tor.default-dispatcher-30] o.e.n.ErgoNodeViewSynchronizer - Got 1 modifiers of type 102 from remote connected peer: ConnectionId(remote=/15.235.13.47:9030, local=/172.21.0.2:42058, direction=Outgoing)
957190-mn-ergo-node  | 06:16:56.499 WARN  [tor.default-dispatcher-30] o.e.n.ErgoNodeViewSynchronizer - Failed to parse modifier with declared id be40351ba48bd5cb1cc43ba74f4f67ed231c912edb9a749f5e4c1f7ed1c77635 from ConnectedPeer(connection: ConnectionId(remote=/15.235.13.47:9030, local=/172.21.0.2:42058, direction=Outgoing) , remote version: Some(5.0.15))
957541:mn-ergo-node  | 06:16:56.499 INFO  [tor.default-dispatcher-42] s.c.n.peer.PeerManager - /15.235.13.47:9030 penalized, penalty: MisbehaviorPenalty

---

**2023-11-21T00:18:02**

not sure if that had anything to do with high cpu though

---

**2023-11-21T02:38:07**

forgot this node was on 5.0.14, will update see if it persists

---

**2023-11-21T05:11:10**

Yes

---

**2023-11-22T04:00:36**

same issue here

---

**2023-11-22T06:53:34**

but why do they disappear after being confirmed? Seen it happen multiple times today

---

**2023-12-08T19:57:42**

The max possible inputs got higher after node 5.0

---

**2023-12-13T12:16:59**

Think its a js bug when converting big number to string

---

**2023-12-13T12:34:13**

Register can be bigint though

---

**2023-12-13T12:39:53**

That shit scares me lol

---

**2023-12-13T13:00:36**

oof, that is a nasty one

---

**2023-12-14T09:06:58**

can confirm, 5.0.14 indexed node is fine, 5.0.16 indexed node stuck on that height (the index is stuck, the node itself is fine)

---

**2023-12-23T02:47:14**

Think sub blocks is better solution tbh.

---

**2023-12-23T10:15:10**

I am hitting limit for size before complexity since v5 on transactions, guess it will be similar for blocks

---

**2023-12-23T23:49:57**

Why?

---

**2023-12-24T16:54:09**

How about a structure of a combination of types? Found that the biggest plus when working with cardano

---

**2023-12-27T03:39:42**

Address is derived from guardscript, so no

---

**2023-12-27T03:41:00**

You can make a guardscript have a user signing as a confition though, but would need to implement it in a wallet to show it there

---

**2023-12-29T04:58:46**

Storage rent claim spends the utxo

---

**2023-12-29T04:59:45**

I would not assume the registers are identical, but could be wrong

---

**2023-12-29T07:23:22**

Ok cool, good to know

---

**2024-01-03T14:25:59**

If a dapp already uses mempool + transaction chaining sub blocks wont do much difference, other than it might make it easier to make sense of the chaos that is the mempool, depending on sub blocks might help avoid ghost transactions etc. in the mempool

---

**2024-01-03T14:28:06**

I would love to see wallets have an option to show unconfirmed balance, I think that would resolve a lot of UX issues. Sub blocks are great on their own if they improve propagation of transactions, spreading the load instead of peaking when the block is mined

---

**2024-01-13T02:23:50**

That is just a multisig right? Or am I reading it wrong

---

**2024-02-02T12:59:44**

Can you consider those active?

---

**2024-02-22T09:42:13**

kushti doesnt have such a check either😁

---

**2024-02-24T00:25:01**

If you mint into the ephemeral sc your register requirements clash with eip 4

---

**2024-02-24T09:41:16**

r4-r6 are used in eip 4

---

**2024-02-24T10:13:55**

ah ok, now I see, didnt realize you wanted to name the token as the address

---

**2024-02-24T10:21:21**

how would this interact with other protocols though, if the token is stuck in the ephemeral contract

---

**2024-02-24T10:23:13**

ok so protocols need to be supporting it, using datainputs to prove ownership

---

**2024-03-02T07:06:38**

Maybe ipfs issue, or issue with some http mirror

---

**2024-03-12T00:42:48**

Needs to be at least the max creationheight of the inputs

---

**2024-03-12T00:43:37**

Relatively new yes

---

**2024-03-12T06:53:04**

who is this Kushti telling me how to PR, he is not the boss of ergo

---

**2024-03-12T06:58:34**

It should be a discussion with all contributors, not just Kushti. Make a thread on forum, work out rules people are happy with and get them implemented

---

**2024-03-12T07:01:59**

yeah issue makes sense

---

**2024-03-14T06:25:14**

I would say in general it is very similar, both being eutxo. Biggest difference is probably resources, where in ergo 1 person is dealing with a problem to solve in cardano there might be 20, that together with catalyst funding gives incentive to make more fleshed out tooling where the 1 ergo dev might feel it is not worth making a generic solution and just do something specific.

---

**2024-03-14T06:28:44**

Only thing I would really like on ergo is deserialize/serialize types in ergoscript, especially if those types can be composites (structs of other types). Think that would be a nice thing to have and make contracts cleaner and more readable. I really enjoyed that in Aiken.

---

**2024-03-14T08:58:02**

what in the languageception is that

---

**2024-03-14T08:58:28**

😂

---

**2024-03-14T08:59:13**

Yeah Aiken is nice for sure

---

**2024-03-14T09:02:35**

got tired of copying reused code so made a simple import preprocessor for paideia contracts

---

**2024-03-15T05:19:52**

Beautiful, it looks super nice

---

**2024-03-15T07:35:49**

Policy id is just hash of a contract that decides if some token can be minted or burned.

---

**2024-04-03T09:12:43**

depends on composability of contracts used I guess. arbitrage between for example spectrum LP erg/sigusd and sigmausd bank could be done in 1 transaction if composability allows it in those contracts

---

**2024-04-03T09:21:36**

yeah, only possible if you can somehow build it into 1 transaction

---

**2024-04-03T09:23:10**

take for example 3 LP's with erg/A, A/B and erg/B, you could arb it in 1 tx?

---

**2024-04-03T09:26:11**

someone can break the chain by outbidding the fee

---

**2024-04-04T08:55:05**

It has been a while since I ran a testnet node, anyone has an example config of the current testnet node?

---

**2024-04-10T13:00:58**

I usually use /transactions/unconfirmed/byErgotree and confirmed utxos + unconfirmed -spent based on that. But makes sense to do that in node api cause its such a general use case

---

**2024-04-26T13:57:48**

Any paideia-state instance will handle all dao's on paideia, so not needed, but of course good for redundancy

---

**2024-05-02T11:38:43**

it is not an easy one to test though, but guess most important thing to test is that it doesnt break anything :)

---

**2024-05-09T13:47:37**

Blake2b256(SELF.propositionBytes) == getVar[Coll[Byte]](0) && executeFromVar(getVar[Coll[Byte]](0))

---

**2024-05-09T13:51:11**

Probably wrong lol

---

**2024-05-09T13:52:37**

The hash should be around getvar and compare to hardcoded hash value

---

**2024-05-14T05:44:53**

Sounds good

---

**2024-05-15T05:16:27**

anyone has some testnet erg to send?
3WxsFN4JMwXcVHooc95Kj68AnhJToXwfZqFz4rbmsdjeuj8tCMEy

---

**2024-05-16T13:03:23**

yes agree, a generic serialize function would be great!

---

**2024-05-16T13:03:47**

and keep the old ones for backwards compatibility ofc

---

**2024-05-28T00:29:26**

Same thing that got us started

---

**2024-05-28T03:29:41**

Im just saying that most devs here arent in it for the money (alone) so nothing is different compared to a year ago

---

**2024-06-18T09:08:42**

Not exactly afaik. They both exist, miner chooses right?

---

**2024-06-18T09:11:40**

Yes but important to know when chaining that multiple branches can exist in the mempool in parallel

---

**2024-06-18T09:14:45**

So if you want you can chain onto each branch to make sure you are part of the winning chain

---

**2024-06-20T06:26:48**

Bit buggy and unoptimized, but I used a few hours to make a graphql layer on top of indexed node that supports all Nautilus usage. It pulls data from indexed node and feeds mempool boxes as if they are confirmed to be used as an experimental graphql server for nautilus to see how the UX is with instant changes happening in the UI/balance after making transactions: https://github.com/Luivatra/indexed-node-graphql

---

**2024-06-20T06:26:54**

@Pulsarzz based on your idea

---

**2024-06-20T06:58:04**

it depends on the /blockchain/box endpoints though, so might hit same issue as rosenbridge

---

**2024-06-21T08:00:52**

Appkit does at least

---

**2024-06-23T14:37:11**

script tokens and additionalregisters contributes to size. amount of erg does matter but not much

---

**2024-06-25T10:56:52**

nemo is working on a repo right?

---

**2024-06-25T11:01:34**

ah similar to the cardano registry

---

**2024-06-28T01:14:51**

I am thinking they are submitted in one go and also limited in size to at least max block size

---

**2024-06-28T07:31:34**

Would be nice for indexed node nautilus.

---

**2024-07-02T23:28:49**

Yes, the http service breaks sometimes

---

**2024-07-03T00:57:48**

Seems not right to me, what is your process for doing this?

---

**2024-07-03T12:10:28**

we will close the api at some point and open up access based on subscription if the demand is there for it, so yes you can, just not sure when you will be rugged

---

**2024-07-04T01:19:59**

Crux

---

**2024-07-05T05:56:17**

Not yet afaik

---

**2024-07-06T13:46:11**

@kushti_ru you found the cause of the http server failing on indexed nodes?

---

**2024-07-06T13:51:23**

ergo_node  | Exception in thread "main" java.util.concurrent.TimeoutException: Futures timed out after [3 seconds]
ergo_node  |    at scala.concurrent.impl.Promise$DefaultPromise.ready(Promise.scala:259)
ergo_node  |    at scala.concurrent.impl.Promise$DefaultPromise.result(Promise.scala:263)
ergo_node  |    at scala.concurrent.Await$.$anonfun$result$1(package.scala:220)
ergo_node  |    at scala.concurrent.BlockContext$DefaultBlockContext$.blockOn(BlockContext.scala:57)
ergo_node  |    at scala.concurrent.Await$.result(package.scala:146)
ergo_node  |    at org.ergoplatform.http.api.BlockchainApiRoute.$anonfun$segmentTreshold$1(BlockchainApiRoute.scala:36)
ergo_node  |    at org.ergoplatform.http.api.BlockchainApiRoute.$anonfun$segmentTreshold$1$adapted(BlockchainApiRoute.scala:35)
ergo_node  |    at scala.Option.map(Option.scala:230)
ergo_node  |    at org.ergoplatform.http.api.BlockchainApiRoute.<init>(BlockchainApiRoute.scala:35)
ergo_node  |    at org.ergoplatform.ErgoApp.<init>(ErgoApp.scala:186)
ergo_node  |    at org.ergoplatform.ErgoApp$.$anonfun$main$1(ErgoApp.scala:306)
ergo_node  |    at scala.Option.foreach(Option.scala:407)
ergo_node  |    at org.ergoplatform.ErgoApp$.main(ErgoApp.scala:305)
ergo_node  |    at org.ergoplatform.ErgoApp.main(ErgoApp.scala)

---

**2024-07-06T13:51:33**

seeing this during startup

---

**2024-07-06T14:09:57**

actually it seems to crash the whole startup of the api, panel is unreachable as is swagger

---

**2024-07-06T14:10:12**

but now managed to startup without that error and still api broken

---

**2024-07-06T14:10:17**

so not sure...

---

**2024-07-06T14:11:37**

not responding on any endpoint

---

**2024-07-06T14:12:55**

yes

---

**2024-07-06T14:14:25**

oh nvm, my browser decided to add https in front instead of http...

---

**2024-07-06T14:14:48**

so I do think that error I pasted before is what crashes the http server

---

**2024-07-07T10:37:24**

Busted 😂

---

**2024-07-15T12:43:04**

Is this gridbot? https://explorer.ergoplatform.com/en/addresses/873uAozZGWZtbb5NskvFGM7h9uVm1VHnSnThQ4X8dwXms1DGHzGU3QjqwR6s3hXhaZgfmZjmFZaq5A3w2iaeAvMnS4fkFZFpUD8NqLEkPE1crXtNYNz8g7j96fm6ywXfQpzTk8SCo7Q6vYQbBfnzsZYVjWUhqoAh1TqruisuFJf3okNZKY5Zo8TCczvXAFuptYjsgTXcW6tQDxD719mYf5p97FPZpxeDC9amornQf19VQeEVsWeckzXqRKvZBvv6kYzg3b7bgpvwvRPNgeSMgjDSzjoPhXTQM7E9r4Z5GCuui9CyjeKueySeQ6wc966JnvKn1wfiTpxLm3nUZrcvooe11ZvuBy6ZxLsmNUzP7jnvhAXWgFu1aXx8zCU9GHG5XUU6eGk3S4z4ZLECQsMVZqFrmuaRp59DHMLL9CERvNqJiFWebcs1YMxdG3XLodsKdJqGKii6Hadakkh5aKbNAvMRGMRWYWirtZXnBrCdvg4cuzfk8eUBFsp7i4WcNb46Zszx1mstyyjwtkpXv8yXoQUv2QPbradxsyeQFex87k5zGeHJmLpXbdDieXfvEsjCef3YgeVtaWEeTQaMx8CFyPrQegot5b9nvTfUo6ryCjYYKgE4XNa7PXxNJ3x4B8jkagf9FMXPRU6Kfcqk738SbCNQDTCmwHyjjJWtnx1adTAujLU8wSJFYwWG3bzCdoDBfmcc3dARZxLMV6YpPkQ6hLZu148ZN7d1T8UuLu1gQLxAbcsVXkBpSLfP4EGu85te1BZazrF6BCVmw52V5246vzUXQm5VVPzXG3NiZRjZ2BGcnR479Z1DU9Vzvd34KQMnjMXmoxeELLAtTfeLp1musyJKURRXaRiYhK9F5Q5vAfBBU3NX8Vmtv4LJNDm8TKRVGrbkacTQnc8vGfitrw8m45CjFdbFjCvgxVuLAJ6eUgg

---

**2024-07-16T02:36:23**

@MGpai0 havent had time to watch your presentation. What can we learn from alephium dev experience?

---

**2024-07-16T06:31:38**

Great!

---

**2024-07-18T06:11:31**

@kushti_ru instead of writing on the forum about eutxo design patterns, maybe we can create a repo on ergoplatform github with a .md describing each pattern and an overview .md grouping them? Each describing how the pattern works and pros and cons

---

**2024-07-19T04:54:59**

token amount is stored as a long so less than that

---

**2024-07-19T05:35:48**

isnt uint64 unsigned long?

---

**2024-07-19T05:36:46**

and is it stored as uint64? in ergoscript it is just long, so kind of assumed it was signed

---

**2024-07-19T05:38:02**

I am confused lol

---

**2024-07-19T05:40:19**

yes, and that discussion was just about javascript being javascript

---

**2024-07-19T05:40:58**

Javascript dev: how is 58 bits not enough?

---

**2024-07-19T05:42:56**

on such a big number who cares about the last digits

---

**2024-07-19T05:50:10**

Made the language just to have animated banners and mouse cursor trails on websites, noone will use it for anything serious

---

**2024-07-19T06:27:55**

https://x.com/Luivatra/status/1814260344665047167

---

**2024-07-21T08:25:48**

yes that is a workaround, executefromvar would be nicer

---

**2024-07-21T08:26:50**

sending funds from treasury supports sending to a p2s with registers filled out, so could use a proxy contract for it

---

**2024-07-21T10:43:28**

360 nanoerg per byte

---

**2024-07-21T10:45:21**

oh didnt know it was there, good to know :D

---

**2024-07-21T11:43:07**

yeah I have been caught out by everything being fine in tests just to realize when testing on chain my utxos didnt have enough nanoerg :)

---

**2024-07-21T11:48:32**

I had it tattood on my hand, hope the miners dont change it

---

**2024-07-21T16:14:16**

Would be nice, but can update contracts later if its not up in time

---

**2024-07-22T22:21:21**

Provide ergotree in context var and evaluate it into sigmaprop

---

**2024-07-23T04:24:47**

heh that might be better response

---

**2024-07-23T08:52:53**

sonatype having some issues by the looks of it

---

**2024-07-23T14:00:53**

your ergohack video was super clear, but maybe not to the average user, made me look forward to it at least

---

**2024-07-26T00:52:17**

Sigma-rust can compile right?

---

**2024-07-26T02:12:24**

Lsp and move to template standard would be nice. Issue is debugging off chain code for testing when off chain code base only has template json

---

**2024-07-26T14:17:37**

How to keep RR aligned?

---

**2024-07-26T14:25:24**

Reserve ratio. If someone mints on one utxo and redeems on another the ratio wont be the same

---

**2024-07-26T14:29:22**

Altho market forces could balance them out i guess

---

**2024-07-28T16:10:20**

I seem to have hit an issue in sigma rust, making it fail signing a Paideia stake transaction: https://github.com/ergoplatform/sigma-rust/issues/757

---

**2024-07-28T16:10:35**

who is maintaining sigma-rust atm?

---

**2024-07-29T06:04:40**

ty for the quick work!

---

**2024-07-30T03:14:06**

does look nice, less convoluted than react

---

**2024-07-30T03:15:57**

haha, might even get into frontend myself with that 😂

---

**2024-08-02T02:07:31**

@kushti_ru you mentioned avl+ being better than mpt, any references on that?

---

**2024-08-02T04:54:38**

ty!

---

**2024-08-04T16:11:32**

Yeah the contract was quite complex, last 2 parameters were token ids so just concatenated them into 1 coll[byte]

---

**2024-08-05T03:39:20**

if they are both mining and only 2 nodes maybe they are both living on a different fork?

---

**2024-08-05T08:26:37**

Ohh, my mind was in weekend mode, the issue was with contract template with more than 5 parameters, not with subsconstants.

---

**2024-08-10T12:34:17**

Defragment wallet

---

**2024-08-10T12:34:41**

Needs an animation just like in win 95

---

**2024-08-16T05:20:54**

Anyone has seen an error like this?
"Malformed transaction: Scripts of all transaction inputs should pass verification. e989df2c1384d3d24b4e9acb9673d12e3f98d81b44332e4622adfc49211abf83: #1 => Success((false,403))"

---

**2024-08-16T05:21:22**

when trying to sign a transaction with nautilus abyss, so guessing it is in sigma-rust

---

**2024-08-16T05:22:11**

the hash value is not present in the unsigned tx json so not sure where that is originating from

---

**2024-08-16T05:29:12**

oh maybe it is when submitting to node... I am bad at js breakpoints apparently :)

---

**2024-08-16T05:41:10**

so the 403 points to extension key length issue? seems weird to me

---

**2024-08-16T05:53:42**

@kushti_ru guessing you would be best to answer this, getting verification error 403 (exKeyLength?) when submitted a signed transaction to node

---

**2024-08-16T06:14:00**

let me check

---

**2024-08-16T06:19:06**

nothing in logs

---

**2024-08-16T07:18:26**

oh that didnt even cross my mind it could be one of the p2pk inputs

---

**2024-08-16T10:01:37**

One is always the paideia dao, the other is the dao the proposal is created in. Now I find the correct data input dynamically I could remove the duplicate in the tx building, just forgot to do that

---

**2024-08-16T10:02:37**

Does that endpoint give more info?

---

**2024-08-16T11:23:02**

Oh I see, the p2s input has a time based condition so the transaction kind of "timed out" causing the first input to fail now

---

**2024-08-16T15:56:05**

I found one repo, 1 sec

---

**2024-08-16T16:02:59**

https://maven.scijava.org/content/repositories/public/

---

**2024-08-17T03:12:25**

but that was a p2pk, could it be due to difference in preheader or something?

---

**2024-08-17T03:23:57**

and where does the hash in the error message come from

---

**2024-08-17T11:46:33**

But its a signed p2pk and the hash is different than the tx id in the signed tx generated by sigma rust

---

**2024-08-17T12:39:40**

right, so the question becomes, why is the tx id different, I am really not sure what to make of this one

---

**2024-08-17T12:40:48**

what is included in the tx id?

---

**2024-08-19T12:23:38**

Any idea what can cause a tx to sign fine with sigma-rust and be rejected by the node?

---

**2024-08-19T13:15:49**

Yes, using it all the time for testing, just spent that utxo in a normal tx

---

**2024-08-22T23:37:30**

Tried graalvm ages ago and hit many roadblocks with getting it working. Might be better now though

---

**2024-08-23T13:49:27**

@CheeseEnthusiast this you? https://explorer.ergoplatform.com/transactions/14ee89106c6d6441d3f2a10b39a1dd3e535d350284bc4b87055eceb2071097cb

---

**2024-08-23T14:06:25**

Looks like it

---

**2024-08-26T02:42:45**

I signed it with Nautilus so 🤷‍♂️

---

**2024-08-26T02:43:48**

Yes

---

**2024-08-26T02:45:38**

Might be a json serialization thing

---

**2024-08-26T02:48:46**

Seem to recall @kushti_ru was working on something similar, a map datatype with predictable serialisation

---

**2024-08-26T03:23:33**

it actually does, but the json serialisation messes the order up, will see what I can do to keep it in line

---

**2024-08-26T03:25:15**

ty for finding the cause, that was a tricky one

---

**2024-08-26T07:02:55**

Ok, managed to align the unsigned json with the order used in appkit, but seems somewhere between nautilus receiving the json and sigma-rust doing the signing the order is changed. Even changing the order of the context variables in the json results in the same signed tx id, which does not match the node generated transaction id. @nemo429 any way to ensure the context extension maintains the same order as the unisnged tx json?

---

**2024-08-28T09:03:19**

1 sec

---

**2024-08-28T09:06:29**

32e61415b2d95b25df9021ede1f7a0af501830e40ac4703297695a9c225477d1

---

**2024-08-30T07:41:47**

Something with the http server thread crashing, think kushti and co were working on a fix, not sure what version.

---

**2024-08-30T07:43:53**

Explorer mempool has been a mess for a while

---

**2024-09-02T05:54:16**

you can omit datainputsraw, and fee is too small, should be 1_000_000 at least

---

**2024-09-02T06:07:41**

oh of course, that caused the error message, other points still stand

---

**2024-09-04T03:30:08**

working with blockchain is like working with the internet in the 90's while everyone thinks all it is used for is porn

---

**2024-09-09T08:40:35**

node doesnt have that restriction (maybe node wallet?) where are you hitting that limit

---

**2024-10-09T04:17:39**

You know, going on a rage barrage of angry messages about there not being a critical discussion when some questionable research is posted instead of calmly starting a critical discussion will drive more devs away than posting a link to some research that may or may not have validity.

---

**2024-10-11T05:50:32**

@kushti_ru workaround with using max 4 context variables is confirmed to work, thank you for the tip!

---

**2024-10-11T07:58:17**

Tried that, didnt solve it. Somewhere along the way going from object to json back to object the order got messed up

---

**2024-10-18T16:23:03**

Changing stuff because its "better" is annoying for existing codebases. Or is there an issue with the old method?

---

**2024-10-18T16:32:21**

Ah yeah that is an issue actually. Kinda caused me to use different types all over as well. So consistent methods with overloaded deprecated methods makes sense yes

---

**2024-10-22T09:22:07**

will try get to it tomorrow

---

**2024-10-28T08:58:23**

not yet, got sidetracked im afraid, was there a specific branch?

---

**2024-10-30T04:29:15**

I added shadowJar plugin to build that, am testing now. If all good and once the new version is deployed I will update ergo-node-zmqpub to fetch the dependency from maven instead of from jar

---

**2024-10-30T05:25:12**

@mewtoshi sending ModifierRequest with ErgoTransaction type seems to crash the socket connection, Header type works fine

---

**2024-10-30T12:40:47**

hmm, maybe it happens all the time 😅 let me check current version

---

**2024-10-30T12:41:47**

yeah current version seems fine, so something is not sitting well

---

**2024-10-30T13:02:03**

ok will verify tomorrow

---

**2024-10-30T14:03:48**

I didnt have signatory setup so thought shadowjar was easier 😅

---

**2024-10-30T14:53:41**

ah I see

---

**2024-11-05T06:53:25**

Tomorrow almost turned into 2 weeks, but verified to work for the zmqpub usecase :) Let me know when it is on maven then I can make a cleaner dependency in my project

---

**2024-11-05T08:07:58**

Hmm actually, @mewtoshi , after letting it run for a while I got this error:
ergo-node-zmqpub  | [error] java.lang.IllegalStateException: Incorrect magic [65, 0, 0, 3] received (must be [1, 0, 2, 4])
ergo-node-zmqpub  | [error]     at com.satergo.ergonnection.ErgoSocket.acceptMessage(ErgoSocket.java:111)
ergo-node-zmqpub  | [error]     at EventPublish$.main(EventPublish.scala:56)
ergo-node-zmqpub  | [error]     at EventPublish.main(EventPublish.scala)
ergo-node-zmqpub  | [error]     at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
ergo-node-zmqpub  | [error]     at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77)
ergo-node-zmqpub  | [error]     at java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
ergo-node-zmqpub  | [error]     at java.base/java.lang.reflect.Method.invoke(Method.java:568)

---

**2024-11-05T08:15:48**

Dont know if that is something that just "happens" and I handle it (reconnecting socket) or if it is something that shouldnt happen

---

**2024-11-08T13:06:06**

yes

---

**2024-11-14T23:59:54**

Each dao has a treasury address and a profit sharing address, profit sharing is automatically split between stakers and treasury, both dont need any registers filled out or othe contract interaction so it should be as easy as sending to any address

---

**2024-11-21T14:06:15**

@kushti_ru is there a list of what is added to ergoscript in 6.0?

---

**2024-11-21T19:29:21**

Ty

---

**2024-11-22T14:48:16**

Spasiba

---

**2024-11-22T15:02:04**

Would verifying signature of arbitrary byte array be possible in ergoscript?

---

**2024-11-22T15:13:44**

Awesome ty

---

**2024-11-23T15:19:49**

I do this by comparing bytes directly, give me 1 sec

---

**2024-11-23T15:23:29**

Not exactly what you want but might inspire you: https://github.com/paideiadao/paideia-sdk/blob/dev/src/main/resources/ergoscript/lib/bytesWithoutCreationInfo/1.0.0/bytesWithoutCreationInfo.es

---

**2024-11-25T06:25:50**

Yes, was daydreaming about dex/cex with deposits into contract which holds people's balance in avltree and transactions handled by signing balance changes (for example setting an order) with private key and contract verifying this when avltree updates are settled on ergo

---

**2024-11-25T06:40:07**

@kushti_ru

---

**2024-11-25T22:02:03**

Yes, L2, centralized or not. But perhaps more efficient than transaction chaining

---

**2024-11-25T22:02:44**

Yes, couldn't remember where to put it, will post on forum for now

---

**2024-11-26T03:57:33**

the eip-5 writeup, now on forum: https://www.ergoforum.org/t/ergoscript-and-contract-templates-why-how-eip-5/5006

---

**2024-11-26T12:38:10**

Would be nice to get a cli ergoscript compiler that produces eip-5 json

---

**2024-11-27T23:55:12**

Its average, but shouldnt be taken as exact especially over shorter time periods.

---

**2024-12-02T05:37:07**

could probably provide the metadata in context variables and hash it to compare with hash value in contract

---

**2024-12-02T05:37:34**

oh ofc it is in the output boxes, no need for context var

---

**2024-12-02T05:38:07**

unless you want only 1 hash, then you provide all 159 in context to verify

---

**2024-12-02T05:41:12**

or put metadata in avl tree

---

**2024-12-02T05:42:32**

there is no avltree support in frontend libraries?

---

**2024-12-02T05:46:06**

could just have it hard coded in the javascript 😁

---

**2024-12-02T05:46:37**

json with all data, fill avl tree in frontend code, create proof

---

**2024-12-02T05:47:08**

its just a static tree anyways

---

**2024-12-03T00:08:20**

Think js is fine as first language, frontend is also nice to be able to see results, but depends what you want to achieve I guess

---

**2024-12-04T08:56:54**

yes

---

**2024-12-06T17:04:23**

in my experience they are, but not sure it is guaranteed

---

**2024-12-06T17:41:07**

Using bank as your quick exit is dodgy anyways. In this case it is locked for half an hour and you can try again. Now a whale can mint sigusd down to 400% rr and you are locked until price recovers

---

**2024-12-07T03:17:08**

So maybe it is important to talk about the why. Many people complained about bearwhale manipulating the protocol and extracting value from rsv and at the same time having an incentive to crash erg price on cex giving bad optics. Instead of focussing on 16k (which would be a larger value if erg rises in price) maybe discuss other solutions or argue for not changing it at all

---

**2024-12-10T00:33:26**

My node has stopped working twice where it just basically stops, log stops producing new entries, but no errors and it does not crash, any ideas?

---

**2024-12-11T04:24:03**

yes

---

**2024-12-11T04:30:23**

a restart gets it going no issue btw

---

**2024-12-11T09:09:12**

stupid guards sleeping again

---

**2024-12-15T13:37:39**

what is the originating ip?

---

**2024-12-15T13:51:52**

Dont think I use 213 anywhere

---

**2024-12-16T13:36:22**

I found an exploit in the paideia staking contracts, I will be working on a fix but in the meantime I have taken the 55 million staked paideia out using the exploit. Whoever finds the exploit I used first will win 25k paideia. It is NOT a complex exploit, so please while you are at it also have a look for other exploits, could be you can earn some bug bounties in the mean time!

---

**2024-12-16T14:36:40**

I agree, we need to get a better auditing culture, but it is difficult when even the devs themselves are on a shoestring budget paying someone for an audit is not always possible

---

**2024-12-16T14:48:48**

/t 10000 paideia for helping me find it

---

**2024-12-16T14:49:08**

25k is still available for whoever dm's me the method

---

**2024-12-16T14:56:18**

still have no idea what you encountered, it looked like a normal dex transaction to me, just had a stake key in the change box, unless I missed something (which apparently happens)

---

**2024-12-16T15:47:56**

https://github.com/paideiadao/paideia-sdk/tree/dev/src/main/resources/ergoscript/Stake/1.0.0

---

**2024-12-16T16:09:33**

/t 5000 paideia could be minor what you found, but rounding up in your benefit

---

**2024-12-16T23:57:57**

Yeah looks fine to me

---

**2024-12-20T05:09:41**

one of the things I want for the crux matching engine, buy on dex until price matches sigusd bank -> rest minted from sigusd bank

---

**2024-12-20T06:35:11**

will run it in parallel on my server, once synced will switch my services to this one, see how it performs

---

**2024-12-20T07:58:28**

it would increase price impact

---

**2024-12-20T07:59:11**

there needs to be a "verified" contract repository, supporting templates and wallets need to integrate that to inform the user

---

**2024-12-20T08:00:02**

of course where possible p2p interaction is best and where utxo shines

---

**2024-12-20T08:00:51**

probably better to go for limit order boxes then

---

**2024-12-20T08:02:49**

some automatic order creation bot to provide liquidity, grid bot

---

**2024-12-20T08:04:10**

the thing is, liquidity is king and amm is much better ux for liquidity provider, just set and forget

---

**2024-12-20T08:32:35**

its a duckpools loan

---

**2024-12-20T08:32:41**

so they  are longing

---

**2024-12-20T08:33:31**

oh just coincidence then heh

---

**2024-12-20T08:37:56**

I tried to start something up, but think it should perhaps be in the hands of something more central like the ergodevs dao https://github.com/cruxfinance/ergo-address-labels

---

**2024-12-20T08:46:38**

its a repository with jsons, beauty is in the eye of the beholder

---

**2024-12-20T08:54:45**

Yeah that is what I meant with it needs to support templates, not trivial

---

**2024-12-20T08:55:25**

Maybe repo just should hold eip-5 style json

---

**2024-12-20T08:55:49**

And consuming service deduce parameter values

---

**2024-12-27T01:46:45**

has config for turning on indexing changed in 5.1? My 5.1.1 node doesnt want to index

---

**2024-12-27T01:48:47**

weird, did the same

---

**2024-12-27T01:48:55**

but isExplorer=false

---

**2024-12-27T01:52:32**

can you send your config?

---

**2024-12-27T02:01:34**

Lol my phone gives reddit and google wallet as options to open .conf

---

**2024-12-27T02:24:04**

weird, had a few other settings which I removed now so it is the same basically, still nothing

---

**2024-12-27T02:24:16**

running it in docker?

---

**2024-12-27T03:04:37**

Yeah, will check api key to be sure

---

**2024-12-27T03:10:46**

right now same as puls

---

**2024-12-27T03:46:00**

actually seems like it doesnt pick up the conf at all

---

**2024-12-27T03:46:12**

@Pulsarzz you use compose?

---

**2024-12-27T03:47:58**

ok, it was just a permission issue on ergo.conf, weird the node doesnt log an error on that

---

**2024-12-29T02:04:25**

Yes, lets do it

---

**2025-01-12T15:18:56**

Address.create("9hhjjgxv...")

---

**2025-01-12T15:19:02**

Iirc

---

**2025-02-01T03:53:31**

I don't think it is good design to put that into the node codebase, that is explorer db stuff

---

**2025-02-09T15:21:56**

Awesome, will make a poc for paideia updated contracts

---

**2025-02-17T08:14:19**

I am 90% sure that is @Armeanio running those nodes

---

**2025-02-17T08:16:34**

who else knows about your "sizes"

---

**2025-02-17T08:16:50**

oh this is dev chat, not baseless

---

**2025-02-21T03:18:52**

when possible (ie. no complicated off chain backend needed) dapps should normalize being able to choose your own node, this is great

---

**2025-02-27T13:55:50**

Updates main goal right now is save the update utxo from storage rent afaik

---

**2025-02-27T14:09:31**

Hah

---

**2025-03-03T16:16:20**

will do it tomorrow, forgot to restore that wallet on a node

---

**2025-03-04T04:32:16**

what is the significance of scala 3, why is it needed

---

**2025-03-04T13:05:54**

They are not connected to internet right

---

**2025-03-04T13:33:11**

Yeah it might miss out on updates, but should still work in existing setup

---

**2025-03-09T14:29:57**

What do you mean with "for indexing data from the node"

---

**2025-03-14T17:02:33**

could be permission issue

---

**2025-03-17T05:01:12**

pff, just make robust code that can handle it! *quickly checks crux backend*

---

**2025-03-17T05:21:46**

executeFromVar is great but would it be possible to generalize that to executeFrom(ergotree: Coll[Byte])? That would open up for things like reference scripts on cardano (refer to ergotree in register of a data input)

---

**2025-04-05T01:48:31**

I can help too

---

**2025-05-18T06:22:53**

its a function of box size in bytes

---

**2025-05-18T06:23:16**

360 nanoerg per byte (I think, cant remember number)

---

**2025-05-18T06:27:18**

calculating box size in bytes is a bit of a hassle, should actually be functionality in the libraries

---

**2025-05-18T06:29:05**

oh its part of fleet? nice

---

**2025-06-10T10:07:52**

@kushti_ru is there a reason for there being executeFrom* functions instead of a generic executeFrom(byte: Coll[Byte])?

---

**2025-06-10T10:23:12**

Ah so it is executing in the context of the caller

---

**2025-06-10T10:39:49**

Was just thinking about a potential pattern with a dataInput having an ergotree(template) in one of its registers so that any other script can "call" it by doing an executeFrom(substConstants(dataInputs[x], parameterIndices, parameters)). That way you could have reusable functions that do not take up any space in a transaction, not even in the context.

---

**2025-06-26T07:47:23**

Indexing doesn't use network (I assume?)

---

**2025-06-26T16:01:07**

Make a separate one called ergo-rocks maybe?

---

**2025-06-26T16:11:34**

Ergo:rocks-v6.0.0 ergo:level-v6.0.0 ergo:rocks (points to latest rocks version) ergo:level (points to latest leveldb version) and ergo:latest, a synonym for ergo:level?

---

**2025-08-21T11:19:14**

Maybe we can make some script to generate a tx per second and have that running on multiple nodes as a stress test

---

**2025-09-08T13:30:41**

Be aware if using ts/js: https://fasterthanli.me/articles/color-npm-package-compromised

---

**2025-09-09T10:45:56**

has the extraIndex config changed in v6 node?

---

**2025-09-09T10:54:48**

weird, my v6 node is not running in "explorer" mode even though extraIndex = true

---

**2025-09-09T10:55:15**

while trying to reset the index folder I deleted the wrong folder heh so trying from scratch now

---

**2025-09-09T10:58:03**

its a copy of my v5 node, so should be fine, 1 sec

---

**2025-09-09T10:58:23**

ergo {
  networkType = "mainnet"
  node {
    mining = false
    extraIndex = true
  }
}

---

**2025-11-21T01:37:28**

At my first job pushing a query to production that didn't hit an index was automatically blocked

---

**2025-11-21T06:54:15**

Many things suck about working on a mainframe but because cpu time is expensive as hell they (the mainframe gurus) don't tolerate stuff that doesn't perform 😁

---

**2025-11-21T06:54:54**

Working on taxing the Danes more efficiently

---

**2025-11-30T15:58:37**

So ergo tree template for USE changed compared to dexygold?

---

**2025-11-30T16:00:10**

In particular for the pool that is

---

**2025-11-30T23:31:44**

We will see if my indexer picks it up or if I need to add something 😊

---

**2025-12-01T00:14:16**

I wrote pool in particular, but some others as well to identify the action taken on pool

---

**2025-12-01T12:01:13**

Yes, it is used by paideia, so should be fine 😊

---

**2025-12-03T14:29:42**

Forgot about that heh, see my update earlier 😊

---

**2025-12-18T10:07:58**

working ergoscript lsp poc

---

**2025-12-18T10:08:06**

fully vibecoded 😅

---

**2025-12-18T16:24:58**

Heh didn't realize some work was done on lsp during hackathon

---

**2025-12-18T16:25:28**

Any complete lsp projects?

---

**2025-12-19T01:25:33**

equivalent to the java thing we have been using?

---

**2025-12-19T08:14:13**

Vibe coded ergoscript (eip5 supporting) compiler and lsp: https://github.com/Luivatra/ergoscript-compiler-lsp

---

**2025-12-19T08:14:51**

Vibe coded zed extension using the lsp: https://github.com/Luivatra/ergoscript-zed-extension

---

**2025-12-19T08:15:55**

Type inferrence:

---

**2025-12-19T08:18:40**

and sort of working error reporting:

---

**2025-12-19T09:27:41**

Awesome!

---

**2025-12-21T03:36:54**

Still not fully working, but think I can get both imports and tests working

---

**2026-01-03T08:16:16**

Where perl?

---

**2026-01-07T03:34:45**

Trying to see what claude code is capable of

---

**2026-01-07T03:34:48**

so far so good

---

**2026-01-07T08:04:59**

building one, syncing headers and blocks, but due to the brute force nature of claude code my node is blacklisted all over 😂 guess it needs a break

---

**2026-01-08T09:56:18**

I just realized that blacklist is permanent lol, so that is interesting considering my ip is static 😅

---

**2026-01-08T11:19:51**

It's a bit annoying heh. Also bit surprising that a slightly malformed message almost instantly leads to permanent blacklist, but I don't know much about what is needed to protect from bad actors

---

**2026-01-08T14:09:53**

Headers syncing nicely!
{"name":"ergo-rust-node","appVersion":"0.1.0","fullHeight":0,"headersHeight":400903,"bestHeaderId":"6b07f23fc1271a5a994f834b342fb07386ab489229766aa50a0e4542e48c7f88","bestFullBlockId":"6b07f23fc1271a5a994f834b342fb07386ab489229766aa50a0e4542e48c7f88","stateRoot":"0000000000000000000000000000000000000000000000000000000000000000","isMining":false,"peerCount":18,"unconfirmedCount":0,"stateType":"utxo","isSynced":false}

---

**2026-01-08T14:46:50**

{"name":"ergo-rust-node","appVersion":"0.1.0","fullHeight":0,"headersHeight":1130275,"bestHeaderId":"dff397203d643e49c54cbe2e6c9f97c9ed286a2af86cfca3a1dc66bda4181cfa","bestFullBlockId":"dff397203d643e49c54cbe2e6c9f97c9ed286a2af86cfca3a1dc66bda4181cfa","stateRoot":"0000000000000000000000000000000000000000000000000000000000000000","isMining":false,"peerCount":26,"unconfirmedCount":0,"stateType":"utxo","isSynced":false}

---

**2026-01-08T14:47:26**

how fast is header sync nowadays on the normal node? been a while since I did one from scratch. Just wondering if I am in the same ballpark

---

**2026-01-09T00:56:15**

Yeah I probably should have done that lol

---

**2026-01-10T12:27:06**

Yes

---

**2026-01-10T13:44:25**

guess the issue here is that someone could mint a token in such a way that minted supply on explorers etc looks to be x amount, but actual amount is 10x, where the minter holds 90% supply and they can try and fool people with that.

---

**2026-01-10T14:39:11**

Need to check crux, can't remember if I handled that case. Guess could also result in larger than max long amount minted of a token.

---

**2026-01-10T16:15:28**

Yeah that is what I would expect, still a weird situation.

---

**2026-01-10T16:16:09**

I actually think spectrum yield farming used this, unless I remember wrong.

---

**2026-01-10T16:16:25**

I mean minting into two outputs

---

**2026-01-11T07:08:15**

Anything in the console? Probably something in the unsigned tx it doesn't like

---

**2026-01-11T09:43:24**

on the website console or on the extension console?

---

**2026-01-11T15:10:51**

Getting there :)

---

**2026-01-11T15:55:59**

https://github.com/Luivatra/ergo-rust-node Fully vibe coded

---

**2026-01-11T15:56:25**

biggest thing missing (partially implemented) is indexed node, and need to test mining functionality etc.

---

**2026-01-11T15:57:20**

But please use it with caution. It seems fine now but it got me blacklisted on quite a few node 😂

---

**2026-01-11T15:59:51**

resource usage seems promising though

---

**2026-01-12T00:27:12**

Maybe it would be best to try it out. Create issues of what is not working and then take ownership of an issue before fixing it. Else it will be chaos and cherry picking between 2 vibe coded branches sounds horrible 😂

---

**2026-01-12T02:27:50**

Yeah it's fine by me, this was mostly an experiment to see how far I could get. Please take it in whatever way you want!

---

**2026-01-12T05:28:19**

1 hour of syncing from scratch

---

**2026-01-12T05:56:45**

First blocks are usually the fastest to sync though

---

**2026-01-12T05:58:31**

Yeah I am quite happy with it, lets see how long full sync takes (and still need to finish implementing indexing)

---

**2026-01-12T07:17:11**

Thanks, will capture that in an issue!

---

**2026-01-12T07:19:54**

It is a choice, it can bog down when running on a slow disk, but I spent some time tuning the rocksdb to take it easy on the disk. Theoretically you could probably also do the indexing in parallel, but that might be a bit too much.

---

**2026-01-12T09:06:41**

No doubt, will take a bit to ensure complete parity

---

**2026-01-12T09:35:57**

Yes

---

**2026-01-22T09:29:48**

yes, this was just claude being a bit idiotic though, think that library seems fine. I am trying to copy as many tests over from the scala node to the rust node so it is more certain it is compatible

---

**2026-01-22T09:32:59**

like not putting genesis boxes in the tree, not performing actions on the tree in the same order. Claude code is great, but when you need 100% accuracy even 99% correctness ends in failure

---

**2026-01-22T09:39:33**

I mean claude forgot to do that, so avl tree was wrong from height 1 :D

---

**2026-02-06T15:51:08**

@kushti_ru I know you are maybe not the rust guy, but I do remember you talking about making the map behaviour consistent in the scala code. Does this look consistent with the scala map? https://github.com/ergoplatform/sigma-rust/pull/843

---

**2026-02-07T03:39:24**

Just fyi, opus 4.6 figured out the issue and made the fix. Would have made the pr automatically if I had not stopped it 😂 it took a long time to find the root cause but still impressive that it did

---

