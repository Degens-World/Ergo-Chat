# Dan Friedman

**Total messages:** 71

---

**2023-04-10T04:56:26**

Hey guys. Trying to write an NFT minter that will pull data from SQL and write it to the Metadata

---

**2023-04-10T04:56:37**

Is there an object called ErgoTokenMetadataBuilder? Or should I use something else?

---

**2023-04-10T08:56:04**

Writing in Scala

---

**2023-04-10T08:56:53**

Not very. Just entries in a SQL database for product traceability

---

**2023-04-10T12:22:20**

What do mean by design?

---

**2023-04-10T12:44:56**

What's the difference between the two?

---

**2023-04-10T12:48:39**

Oh ok. I thought that was for Kushti

---

**2023-04-10T12:52:38**

I think V2 would be better for what I'm trying to do

---

**2023-04-10T18:07:37**

Can you guys point me to an example of minting an NFT in Scala?
Something that shows how to mint and write to the registers?

---

**2023-04-12T20:51:25**

Is there a faucet for testnet tokens?

---

**2023-04-12T21:16:05**

Getting some errors

---

**2023-04-12T22:43:47**

What is the best stack to mint am NFT thought code? Nothing has worked for us so far. No luck with Scala or JS

---

**2023-04-12T22:44:09**

What does everyone usually use? Node? Python?

---

**2023-04-12T23:45:56**

I guess we can start with that but what would be the point? I'm sure the network is fine

---

**2023-04-12T23:48:00**

Minting an NFT is a pretty basic operation

---

**2023-04-13T00:00:35**

The issue is not lack of knowledge here, but rather following the documentation on github sending me to dead ends. Dependencies not being recognized. Calls missing etc. Which is the reason for my questions.

---

**2023-04-13T00:02:27**

I understand that it's probably pretty straight forward for those who have been working with this stack for some years. But even coming from a similar ecosystem like Cardano, this is kind of complicated. Not as far as logic, but as far as trying to piece knowledge together.

---

**2023-04-13T00:10:09**

I might have. Let me check

---

**2023-04-13T00:21:27**

Is that rust or JS?

---

**2023-04-13T03:19:21**

That's great. I'll try it out

---

**2023-04-13T14:08:57**

Looking to write traceability information into the Metadata

---

**2023-04-13T18:16:43**

Is that what it takes to get this stuff running? It's 8am here but I could have some breakfast shochu to get the day started

---

**2023-04-13T22:55:49**

Getting ArrayIndexOB exception when I try to build the project

---

**2023-04-13T23:04:45**

yeah

---

**2023-04-13T23:12:21**

I think that was the problem

---

**2023-04-13T23:12:25**

Im trying testnet

---

**2023-04-13T23:13:18**

NP

---

**2023-04-13T23:13:51**

I need to do it on testnet because I might need to test mint 1000 nfts or even more to load test

---

**2023-04-13T23:19:43**

Theyre going to be created in bulk but will need unique metadata assigned to each from the tracebility data

---

**2023-04-13T23:49:26**

Ran in on mainnet. It threw an exception for the token name saying that it expects Base58 encoding

---

**2023-04-13T23:59:07**

Using double quotes per the read.me

---

**2023-04-14T00:02:09**

Do I need to manually encode any strings to Base58?

---

**2023-04-14T00:07:13**

occam's razor

---

**2023-04-14T00:57:14**

java -jar minting-for-dummies-3.0.0.jar "mainnet" "palmyra-token" "this is a test tea token" "p.jpg" "https://uploads-ssl.webflow.com/633f6d8648371e3386f1cb06/6371d7579366a7717ce501c4_bhupesh-talwar--lk96OJC_qc-unsplash%201.jpg" "9egunrSMzDhjcB2Vcqkue82jv8zaRJSJcR6fdwjuGG2JqQaUCy8"

---

**2023-04-14T00:57:22**

this is what mine looks like

---

**2023-04-14T01:25:27**

ok, had to rebuild the jar which fixed that

---

**2023-04-14T01:26:39**

Yeah that was a mistype on my end when I was writing the string here

---

**2023-04-14T01:26:52**

now its having a fit with the mnemonic

---

**2023-04-14T01:29:26**

It's giving me index 7 out of bounds for length 7

---

**2023-04-14T01:30:23**

Is there a parsing character for the mnemonic? Or is it spaces?

---

**2023-04-14T01:31:24**

That's what I'm doing now

---

**2023-04-14T01:32:56**

Something to tell your grandkids

---

**2023-04-14T01:36:19**

Just re-downloaded and rebuild maybe 15 minutes ago

---

**2023-04-14T01:37:06**

There are 8 arguments. Mnemonic is the 8th one. It starts from 0

---

**2023-04-14T01:43:04**

Checked that. Looks ok

---

**2023-04-14T01:45:16**

I mean if it's an index out of bounds I'd think one of the indexes is beyond the string

---

**2023-04-14T01:47:01**

treid it both ways but before I rebuilt the jar the last time. :et me see if thats it

---

**2023-04-14T05:32:25**

Minting with ERG for now. Going to launch a hybrid token using Rosen in a bit

---

**2023-04-14T05:43:50**

Good point

---

**2023-04-14T05:44:13**

Tell that to my wife

---

**2023-04-14T05:46:01**

Hey! What are you hinting at? 😡

---

**2023-04-14T05:47:58**

The initial hurtle of not paying others to do this work like I have for the past seven years

---

**2023-04-14T05:50:29**

Oh I can value it either way. Did this since the 90s. This ain't nuttin. You ever bare the pain of programming in debug? Or dealing with an AS400 mainframe?

---

**2023-04-14T05:50:46**

Now that's pain

---

**2023-04-14T05:52:06**

Oh, I'm that old

---

**2023-04-14T05:52:39**

Fucking RPG still roams the farscape of my nightmares

---

**2023-04-14T05:53:30**

C++, LISP, GW Basic

---

**2023-04-14T05:53:32**

Ugh

---

**2023-04-14T05:54:50**

Amiga assembler

---

**2023-04-14T17:32:30**

Perms?

---

**2023-04-14T17:33:30**

I want perms. And soul glow for Ergo

---

**2023-04-14T17:35:03**

It's concerning that the amount I post is considered a lot

---

**2023-04-14T17:36:42**

Maybe I'm in the right channels and you're just afraid of the revolution

---

**2023-04-14T17:38:57**

Don't be afraid. Don't fight it. Just go with it. It's only frightening because it's new

---

**2023-04-15T16:00:38**

Hey, kind of a basic question. Does Scala use lazy evaluation like Haskell?

---

**2023-04-15T18:16:47**

Maybe your friend. Definitely not mine. He still won't come clean about being SKYNET. Just try asking. You'll see

---

**2023-04-15T19:03:00**

It's pretty funny when it gets woke and for what reason. Woke GPT

---

**2023-04-30T22:23:37**

Anyone know what are the dependencies for ipfs?

Keeps giving me "Extracting structure failed"

"sbt.internal.bootserversocket could not create lock for sbt"

---

**2023-04-30T22:24:27**

using this for my dependencies 

libraryDependencies += "io.ipfs" % "java-ipfs-api" % "2.14.2"

---

**2023-05-23T02:56:23**

Can someone recommended a cheap server to host a Scala backend?

---

**2023-05-23T04:00:36**

Nice!

---

