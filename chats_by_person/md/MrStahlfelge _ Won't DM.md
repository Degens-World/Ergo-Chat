# MrStahlfelge | Won't DM

**Total messages:** 190

---

**2021-12-31T08:48:36**

There was an EIP or suggestion made to add preview pics

---

**2021-12-31T09:16:56**

I think it should be saved in the payload

---

**2021-12-31T11:36:20**

If I remember correctly that was the proposal for preview pics.

---

**2021-12-31T11:41:13**

Is ipfs decentralized?

---

**2021-12-31T11:42:51**

I wonder that more because the nfts itself are stored there. 
Anyway, I don't know where I have seen the proposal. There's no EIP for it

---

**2022-01-08T06:21:52**

A whole 1, generous today.

---

**2022-01-08T06:27:02**

We should introduce a thisguysucks token

---

**2022-01-26T07:01:28**

I would give you a thumbs up if I could

---

**2022-01-26T07:04:41**

I would give you a laughing reaction, if I could ;)

---

**2022-02-04T08:10:55**

the ergo discord

---

**2022-02-23T14:48:38**

where?

---

**2022-02-23T15:14:08**

ErgoValue?

---

**2022-02-23T15:16:58**

ah. it's not merged yet, let's see if morphic prefers a wrapper for it. but it worked well on java (contrary to some other objects)

---

**2022-03-25T02:04:22**

Did you try using the node http://213.239.193.208:9052/

---

**2022-05-21T01:13:26**

You could use the methods appkit provides, if you use the latest version

---

**2022-06-09T11:27:44**

If it says 0 ergs found than there are 0 ergs

---

**2022-06-10T10:10:10**

I think he will add something like the signing screen of the mobile wallet that shows the spent box contents as well

---

**2022-06-10T10:57:33**

Spent tokens are shown. A token that is going to be burned is spent so it is shown, except when it is sent back to the same address in a change

---

**2022-06-10T11:13:13**

In my opinion it is up to the wallet to show to the user what he is going to sign for.

---

**2022-06-10T11:13:53**

There always can be a malicious dapp, the wallet application is user's trusted application

---

**2022-06-14T06:11:17**

Use a Boxoperations instance and loadtop

---

**2022-06-14T06:11:56**

Deprecated because moved to blockchaindatasource class

---

**2022-06-14T13:01:08**

Can do later, or just check BoxOperations.loadTop source

---

**2022-06-15T03:10:19**

val boxesToSpent = BoxOperations.createForSender(buyerAddress, ctx)
                    .withInputBoxesLoader(
                        ExplorerAndPoolUnspentBoxesLoader().withAllowChainedTx(
                            true
                        )
                    )
                    .withFeeAmount(minerFee)
                    .withAmountToSpend(amountToSend)
                    .loadTop()

---

**2022-06-18T11:09:29**

ergopay showcase can mint tokens on testnet. but you can give me a testnet address and I'll send you some fake sigusd

---

**2022-06-18T17:53:57**

I'll send you some

---

**2022-06-25T05:21:58**

On what platform? Another browser extension, mobile, or desktop?

---

**2022-06-25T05:22:20**

iOS or Android?

---

**2022-06-25T05:22:48**

On which tech stack?

---

**2022-06-25T05:24:04**

Mobile App with visual basic? Not aware of any way

---

**2022-06-25T05:26:21**

It is not about the API, there is no way to create mobile apps with visual basic? Xamarin is only for c#, isn't it?

---

**2022-06-25T05:29:42**

Would not call that visual basic. When I hear visual basic, I think Microsoft. I am old, too. It was my main work horse in the 90s

---

**2022-06-25T05:30:43**

There is no SDK for ergo on that language. You can use the explorer rest API you already found to fetch balances etc. But for calculating wallet addresses and sending transactions there is more involved.

---

**2022-06-25T05:31:56**

It is especially complex when it comes to the smart contracts. But if you start off only supporting p2pk it is a doable task to reimplement everything.

---

**2022-06-25T05:37:43**

Not in any case. Receiving is someone else sending to you, you are passive and just need to check if you got something.
But you need an address to receive something. If you want to create an address, you need some math because it is based on cryptographic keys.

---

**2022-06-25T05:38:35**

So if you don't want to create the address on your device, you can skip that task. If you want, you may be lucky because most code related to this is very similar to Bitcoin. And maybe some library for Bitcoin exists for basic.

---

**2022-06-25T05:47:39**

You are welcome. When receiving, keep in mind that blocks are not found immediately and unconfirmed transactions can be cancelled

---

**2022-06-27T05:30:17**

Use the 213 one

---

**2022-07-01T03:00:39**

java: [adopt@1.8]

---

**2022-07-01T03:00:48**

https://github.com/ergoplatform/ergo/blob/205eabf79806b428f86d4b8c866b4df0581b9458/.github/workflows/ci.yml#L66

---

**2022-07-01T03:02:06**

you can use java 11 as well. it is the latest version

---

**2022-07-01T03:02:29**

good approach to always use the latest LTS

---

**2022-07-01T03:02:43**

no, latest LTS. everyone builds with Java 11 nowadays

---

**2022-07-01T03:03:09**

really, 17? ah, my bad. then 11 is the oldest supported LTS :)

---

**2022-07-01T03:03:47**

Spring seems to have an other opinion

---

**2022-07-01T03:04:10**

no problem to build spring on 8

---

**2022-07-01T03:04:27**

Android builds on 11

---

**2022-07-01T03:05:28**

then you have to tell them, selecting Spring 3 and Java 11 works for me

---

**2022-07-01T03:11:28**

on language level we are still bound to Java 7 for some time. the iOS crosscompiler and Android <= 7 are on language level 7. You can use some Java 8 features like lambas, but classes that were introduced in Java 8 fail.
That's the language level part, building is done with Java 11

---

**2022-07-01T03:13:31**

latest android devices run java 11, yes. but you usually want to target more than 10% of users

---

**2022-07-01T07:35:43**

what do you want to achieve?

---

**2022-07-04T14:06:21**

you already stated that several times

---

**2022-07-09T01:59:02**

time to check if satergo  is safe!

---

**2022-07-09T02:00:44**

that's why I will check it, but don't you feel responsible for your users?

---

**2022-07-09T02:39:45**

appkit already has a burning flag so it had to be done there, no change for you most likely.

---

**2022-07-21T15:52:22**

The developer is on discord and active on the weekly chat

---

**2022-07-22T12:13:54**

Still being able to work while mining

---

**2022-07-22T13:34:40**

There is a way described on SO

---

**2022-07-22T13:34:50**

And yes it should build with jdk11

---

**2022-07-31T12:48:25**

AWS identified

---

**2022-08-08T10:59:49**

Android devices still on 7. The build is done on development machine with 11 because it is the current lts

---

**2022-08-08T11:03:57**

11 is also the current lts and no one upgraded any jres of existing devices

---

**2022-08-08T11:06:20**

https://endoflife.date/java

---

**2022-08-08T12:46:54**

I care about it because it is the version most people settle on to use it, at least in the Android Community. Because the big enterprise providing the development environment is using it, for good reasons.
As long as it gets security updates there is no real advantage in using later Java versions when effectively I am bound to language level 7.

---

**2022-08-08T12:49:59**

If it is needed to keep scala 2.11

---

**2022-08-08T12:51:20**

And it is not correct that the latest features can be used. Some of the language features can be used, but not classes or crypto related methods that are not present

---

**2022-08-08T12:56:01**

As I said, SOME of the language features can be used.

---

**2022-08-08T13:04:23**

This is not correct, but i am not going to discuss this any more with you as I gave the information needed here, believe it or not.

---

**2022-08-08T13:07:26**

Yes because you have the right information and use it wrong often. I never said that there aren't devices supporting Java 8. I said there are devices not supporting it. Now you come with information that API level 26 supports some Java 8 API. That is really great, but it is not new and does not contradict what I was saying.

---

**2022-08-08T13:11:24**

We currently do and there is no reason to drop that. Everything is working fine with Scala 2.11

---

**2022-08-10T03:56:26**

No, you can expect it to be cancelled in most cases if you use the same input boxes

---

**2022-08-10T03:57:16**

Older versions of wallet app did not support transaction chaining and therefore previous transactions got cancelled when not confirmed already

---

**2022-08-10T04:58:22**

exactly, we don't have a true cancel

---

**2022-08-10T05:01:49**

when you have a delay before actually submitting the submission can be prevented during the delay period, sure.

---

**2022-08-20T08:42:23**

if the former is http node api, yes, that is the right way to go for appkit imo

---

**2022-08-26T09:04:40**

have noticed the same

---

**2022-08-26T09:10:33**

probably better since most apps will use address for convenience

---

**2022-08-29T04:08:09**

no, that would be a bid contract and we already have an EIP for that (EIP-31)

---

**2022-09-03T12:05:36**

iOS wallet published by zengate

---

**2022-09-06T09:48:15**

?

---

**2022-09-08T02:48:00**

spring is either used within a servlet container or you use spring boot which ships with tomcat, jetty or even other server implementations. with tomcat it is 30mb and memory footprint 200mb

---

**2022-09-12T01:04:28**

1/

---

**2022-09-12T05:35:11**

Box id of first Input. There are some examples around

---

**2022-09-12T05:39:53**

There is an example linked in appkit's wiki. Minting is also shown in ergopay example repo

---

**2022-09-24T16:05:40**

isn't that a necessity to be a successful youtuber? community members excluded, of course

---

**2022-09-26T12:18:27**

When using appkit, check if Address.create() throws an exception

---

**2022-09-29T10:17:12**

better to 103 than never :)

---

**2022-09-29T11:42:59**

Version check will only work for reference client. Any other client that might come up would fail the check.

---

**2022-09-29T11:47:47**

how to determine if it took place?

---

**2022-09-29T11:48:04**

is the protocol version increased?

---

**2022-10-04T06:41:41**

made with mosaik in only 4 hours - every ergo dev should take a look at mosaik. the code is OSS here https://github.com/MrStahlfelge/mosaikboxconsolidation

---

**2022-10-04T06:42:06**

many reported such old boxes, it seems a dapp messed up the creation height which is revealed by this app

---

**2022-10-04T06:42:34**

send me your address and I take a look at the boxes, or maybe do yourself if a box has a suspicious creation height

---

**2022-10-04T06:48:35**

according to @kushti_ru 's forum post it is https://www.ergoforum.org/t/storage-rent-details/256

---

**2022-10-04T06:55:29**

well it is an issue, looks like the little utility came right in time?

---

**2022-10-04T06:58:02**

I guess that is some kind of let the market decide? If I would go to a hot dog stand and the shopman let others bite first I would go to another stand next time

---

**2022-10-04T07:00:17**

I guess @LuivatraEP is aiming for some kind of warning to get when submitting such a tx?

---

**2022-10-04T07:01:22**

how should an actor make a malicious tx, you are the one to sign it

---

**2022-10-04T07:02:05**

ah I get what you mean. ageusd swap could set next bank box to creation height 0

---

**2022-10-04T07:04:08**

interesting. I did not check, you said you can't protect it?
did not check, but outbox.creationHeight > self.creationHeight is not possible?

---

**2022-10-04T07:05:13**

okay, when it is possible then we are safe. but this should be a 101 like checking SELF.id and I think most devs are not aware of it

---

**2022-10-04T07:06:02**

spectrum guys made sure to make us aware

---

**2022-10-04T07:45:47**

thanks for coming back. when it was a modified bot, it emphasizes even more that contracts should check the creationHeight of outboxes

---

**2022-10-04T10:30:29**

Block 30 * 24 * 365 * 4 = 1051200

---

**2022-10-05T03:02:15**

oh yeah, fud incoming

---

**2022-10-05T04:29:40**

yes, it is a different scenario. in my opinion, the use case of having a transaction to be submitted at any point of time is not really important. a one year time window to submit it is fair enough, especially since this time window can be chosen at creation. the possible misuse of creationHeight outweights the feature in my opinion.

---

**2022-10-05T04:42:45**

I get that, but on the other hand every single smart contract will have to make a check for creationHeight setting.
How about the following suggestion: Every output box creationHeight must be higher than the max input boxes creationHeight? This will not restrict your use case, but will suppress malicious backdating

---

**2022-10-05T04:48:43**

how will that fail? can't see it

---

**2022-10-05T04:51:09**

it should be an improvement for sure, even if not covering everything

---

**2022-10-05T04:55:23**

I think it would be good to have a decision on this soon so that contract devs know if they have to change all their contracts or if it is solved on protocol level

---

**2022-10-05T05:08:39**

I can do an EIP, it will be just a very short one? Does it justify an EIP

---

**2022-10-05T05:45:18**

Yes it is not a good idea.
What was the idea to use the creationHeight in the first place, not the settlement height

---

**2022-10-05T05:57:10**

It is anon_reals token ensuring his fees. I am sure he will take care of it 😅

---

**2022-10-06T02:24:14**

block height is the same?

---

**2022-10-11T14:08:26**

It's XML for me

---

**2022-10-12T02:30:57**

no, that payment portal is not familiar to me. I think it is by hailypdll on discord

---

**2022-10-13T00:53:39**

No

---

**2022-10-28T08:09:10**

The test fails on random endpoints so seem to be connection instability. It started yesterday before all tests went through smooth

---

**2022-10-30T04:13:07**

No there is no shame. The code used in wallet app is here 
https://github.com/ergoplatform/ergo-wallet-app/tree/develop/common-jvm%2Fsrc%2Fmain%2Fjava%2Forg%2Fergoplatform%2Fapi%2Fergodex

---

**2022-10-31T09:45:45**

What do you want to test

---

**2022-10-31T09:46:11**

The restriction is 255 tokens and we lowered it to 100

---

**2022-10-31T10:09:36**

nice

---

**2022-11-14T02:38:25**

If you want to solve it with a backend, you might not need ergoscript at all.

---

**2022-11-14T02:53:53**

That's what I meant

---

**2022-11-14T03:07:40**

You might need to pay upfront, but no problem, simply start an 51% attack

---

**2022-11-20T06:17:16**

Yes, see eip-25

---

**2022-11-20T06:17:36**

Or eip-20 if your product is a token

---

**2022-11-28T09:33:36**

probably because it doesn't support scala

---

**2022-11-28T14:07:05**

Which application? Depends on the framework. If you talk about debugging, yes, that's possible

---

**2022-12-04T04:01:45**

He complains about being ghosted and never sent me a direct message or so. On a side note, Nautilus is not the only wallet supporting NFT.

---

**2022-12-04T04:05:09**

I guess it is not solving his problem but I don't know because he never wrote down what he actually needs. That's what an EIP is about and I've suggested that he writes something. In the tweets he complains about being in charge to describe himself what he needs.
Looks like he is expecting a sales agent calling.

---

**2023-02-03T05:39:42**

Old problem, where is that list fetched from and who curates the list and maintains it

---

**2023-02-03T05:40:26**

Tokenjay provides an API to get a list of open nodes, but using it is a single point of failure

---

**2023-02-03T05:41:21**

And in theory a node could be a bad actor, so a trusted one has to be used as a default

---

**2023-02-03T06:05:59**

When a set of known nodes is present, there is no problem. But how to get a set of known nodes? See above

---

**2023-02-03T06:07:44**

And how do I get a list of known trusted nodes to hardcode? What happens when the hardcoded nodes get down? That's no real solution

---

**2023-02-03T06:08:19**

Or, in this case, the list of hardcoded nodes did not work correct but seemed to work correct

---

**2023-02-03T06:09:14**

So the answer to "who maintains the list" is me?

---

**2023-02-03T06:09:33**

Weak solution.

---

**2023-02-03T06:10:10**

Well, you've seen that it does not work perfect. Additionally, when I update my hardcoded list, rollout time to users is at least two weeks.

---

**2023-02-28T11:31:04**

Reversing a retrieved list is not a problem, but fetching 20 boxes and reversing is not any solution if an address has 1000 unspent boxes

---

**2023-02-28T11:32:25**

What if all means that you get 500 mbytes of data?

---

**2023-03-08T04:26:11**

She 😉

---

**2023-03-23T15:03:22**

If you only have SigUSD then you can use tokenjay

---

**2023-04-16T04:18:11**

You have to instantiate the rest API client with your own okhttp instance. This is recommended anyway to not spawn too many thread pools. See okhttp docs.

---

**2023-04-16T13:40:24**

Check ergo wallet app if you like an example more than documentation

---

**2023-04-25T08:38:18**

I think it doesn't make sense to discuss the name at this point in time

---

**2023-04-30T16:02:56**

You can use the escape character for the second hash

---

**2023-05-01T03:58:36**

There's an escape character for the second #

---

**2023-05-01T03:59:10**

Should be % + hex code of #

---

**2023-05-01T10:06:46**

These kind of comments would had been helpful while the EIP was in proposed state which was quite some time. Now it's around 15 months later without any complains at all so I don't know what to do with the comments. Feel free to propose a change, but keep in mind that you need to be backwards compatible.

---

**2023-05-01T10:31:48**

I don't know what's the problem with using the escape characters.

---

**2023-05-01T10:32:45**

If the question was if the design was made to be best used with a special Java helper method, then the answer is indeed no.

---

**2023-05-01T10:53:10**

I made my implementations to accept # and second one escaped, because as you say a valid url needs to be formatted this way. My implementations also accept two hashtags because, even when invalid, dapps might deliver it this way. Easy rule: be tolerant in what you accept

---

**2023-05-04T05:56:01**

Works for me

---

**2023-05-04T05:56:28**

The error message is returned when trying on mainnet with testnet addresses 🤷‍♂️

---

**2023-05-09T03:03:39**

thought about it but I choose my battles well :D
why don't you open an issue?

---

**2023-06-12T02:35:13**

I did not implement it yet because no one else reviewed it and I thought the lack of motivation is caused by a lack of interest for the feature. :)

---

**2023-06-12T11:01:38**

Why not

---

**2023-07-31T00:55:42**

If you build yourself

---

**2023-07-31T09:49:08**

It is not centralized, everyone can set up a token validation service and users can choose which one to trust

---

**2023-12-03T16:29:53**

There is a java8 compatible mobivm version for anyone to test if that's the question

---

**2023-12-03T16:33:30**

For any other discussions, I can only say that I decided for the solutions with the smallest effort and the best runtime stability in my experiences so far. If anyone wants to rewrite, rebase or whatever, everything is OSS so feel free to do it.

---

**2023-12-03T17:01:58**

2.12 does not work on Android and with proguard as well so there is more an issue on scala side in my opinion

---

**2023-12-03T17:09:58**

A full release build with minification?

---

**2023-12-03T17:10:16**

And did you test signing of tx and not only if compilation succeeds?

---

**2023-12-04T00:46:40**

To get app size down to 6mb

---

**2023-12-04T00:50:40**

I don't remember exactly what the problem was. Missing classes are easy to spot and to exclude so it was something else

---

**2023-12-07T06:35:29**

That's why robovm is the best to use

---

**2023-12-07T08:08:10**

Do it

---

**2023-12-07T08:31:28**

Because it works

---

**2024-06-05T02:29:58**

Can you elaborate what you want to do?

---

**2024-12-10T01:30:02**

Stahlfelge, it is even autocorrected on my phone 😁

---

**2024-12-10T01:32:05**

It is weird that jitpack seems to have dropped the 2.0.2 dependency but kept v2.0.2 🤷‍♂️

---

**2024-12-19T23:25:07**

Because back in the time node had less apis

---

**2024-12-19T23:26:09**

Why someone still buys sigusd over a proxy is beyond me, ui for direct interaction is available for more than two years or so?

---

**2024-12-20T05:16:07**

Okay, I'm surprised that Nautilus does still not support ergopay

---

**2024-12-20T05:27:19**

No, if it's not done until now reason is not lack of time

---

**2024-12-20T08:22:00**

There is no centralized part, you can build the unsigned transactions wherever you want.

---

**2024-12-20T08:24:19**

Not even that, if the TX is small enough that it fits into a qr Code the code can contain it. But that's not often the case so you have to run a http server to give the TX to the wallet. This is for convenience, on a technical level it would work with files as well

---

**2024-12-20T08:29:26**

But I agree you have to trust the address as the correct smart contract. It is no problem with sigusd bank as you can see the in and out. But for other smart contracts you need to trust.
But to be honest, if you can't understand the source of a smart contract you need to trust anyway. If there is a curated repo of smart contracts you need to trust that repo.

---

**2024-12-20T08:35:21**

True, trust as well.

---

**2024-12-20T08:47:17**

But the addresses can change if you have parameters in the code or even if you compile with another version

---

**2024-12-20T09:21:12**

Yeah it could make some more data possible. But many devices have problems with HD qr codes anyway, for cold wallet a low d qr code option had to be added. After all, for hot wallets transferring data via http was a very natural way.

---

**2024-12-20T09:31:25**

It requires a source for the unsigned transaction. If you don't have a source there is nothing to sign.

---

**2024-12-20T09:41:45**

Year qr code can have up to 4000 but it did not work with multiple Android devices. That's why we lowered the data amount

---

**2024-12-20T09:47:49**

There could be other tweaks as well. Some apps transfer private keys with din a4 sized qr codes and it works well. Using some own decoding algorithm i guess. There is room for improvements. When I worked on it, the deal breaker was not transferring the data but dapps not accepting another approach than meta mask does.

---

**2024-12-20T09:57:05**

I see. I did that for cold wallets but not for ergopay. Special hint: the wallet's desktop version allows to paste the data from clipboard. Very handy for testing. 😉

---

**2025-03-05T07:16:17**

Feel free to ping me for such questions.

2.13 was not working with r8 obfuscation back in the times, so the android build was not working regardless of the target version. I raised a ticket to the r8 team back in the times and this might be fixed.

Additionally, the build for iOS is only capable of Java 7 and there is no backporting available. There is an experimental Java 8 version of the iOS compiler available which might work, or might not.

The desktop version is the only version not concerned by any of these problems.

---

**2025-03-06T01:02:22**

Sorry, dk, there were no stateless nodes when I worked for ergo

---

