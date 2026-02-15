# Josemi

**Total messages:** 73

---

**2025-07-30T11:46:38**

Yes of course.

---

**2025-07-30T11:49:26**

Have into account that with Ubuntu 24 I had problems because of the docker version ...

---

**2025-08-03T04:41:30**

Yeah, it's python3.11

Use python3-venv for isolate python dependencies.

And the docker version that works on Ubuntu 24 made problems to me in the past.  I always use Ubuntu 22

---

**2025-08-06T08:39:26**

What happened.?   Execution or packing?   Or fails during installation.?

---

**2025-08-06T08:40:43**

Anyway, I will try directly on u24 this month to ensure everything works perfectly

---

**2025-08-06T15:30:29**

👍.   Python3.11 should work

---

**2025-08-14T10:18:25**

yes please, could be great

---

**2025-08-14T10:22:11**

mmm okey, im going to try to do that.   Thanks

---

**2025-08-16T09:01:52**

Cool , im with fleet sdk so perfect.    Thanks

---

**2025-08-18T00:54:28**

This command https://github.com/moon-miner/feeless-Ergodex-run-script?tab=readme-ov-file#one-line-installation don't worked to me.  The other ones worked

---

**2025-08-18T01:00:08**

anyway, the repo for https://www.ergodex.io/ergo/swap is not public? seem a more clean ui to me @Patato55

---

**2025-08-18T05:06:48**

Ah okey, me too, maybe not public

---

**2025-08-19T00:17:01**

@anon_br Ey;   i receive an error "Maximum call stack size exceeded" when i execute a tx. with a long double loop in one of the  ergo script.  
The problem is on the JS implementation? 
Or for some reason spent this super heavy contract is not possible?

---

**2025-08-19T00:18:05**

Basically (in ergo script)
for i in 1000:
      for j in [1...5]:
              {compare maximum}

With 100 it works.

---

**2025-08-20T08:12:31**

Yes, mock-chain

---

**2025-08-24T12:52:01**

How i add a token logo on nautilus wallet? It takes the image from a mint box registry? Or manually added on the source code?

---

**2025-08-24T13:15:38**

ohh okey   thanks

---

**2025-09-17T08:26:00**

Game of Prompts

- Some improvements at reputation system.
- Working with frontend  judges part

---

**2025-09-22T12:08:06**

Okey thanks 🙏

---

**2025-09-22T12:11:49**

Just out of curiosity, what’s the maximum number of inputs that have been spent in a single transaction? More or less?

---

**2025-09-22T12:51:57**

Cool

---

**2025-09-23T02:21:56**

Hi!   How do you think to do that?

---

**2025-09-24T11:21:20**

Game of Prompts 

- Judge system done.  So basically now all the main stuff is implemented. 
- This week I have been seeing some issues if the judges have a lot of opinions, so I need to update the reputation system again 😅.
- The current implementation allows for 20-50 participants, which is great, but probably can be unlimited or extremely high, so I will try to improve this too.

---

**2025-09-24T11:23:51**

If this goes forward, when the time comes I could implement it.

---

**2025-09-24T15:07:11**

contracts

---

**2025-10-02T16:31:21**

When using an input that has a token, is it possible to omit that token from the outputs and thus remove the token from the network’s state? I thought this wasn’t possible to do.

---

**2025-10-02T17:12:04**

ohh okey, i thought that burn was something like an output with a script that is always false. In case of ERGs is different right? burn ERGs is only possible with an always false script (without considering rent).

---

**2025-10-08T09:21:23**

For funding there are multiple options:
 - ErgoRaffle: Smart Contract based that sends a percentage for one of the founders using randomness. Has been used for a lot of community funding.
 - Mew fund: centralized but powerful, with a lot of options;
 - Stability Nexus' Bene: Smart Contract based and p2p (no backend required to be executed by anyone). But for now only supports ERG tokens exchanged for your custom token (not, for example, sigusd).

---

**2025-10-08T16:12:14**

We've got the functionality in place to support any token. Now we just need to do some more in-depth testing and sort out a few UI bugs.

---

**2025-11-20T13:37:28**

Question about templates: in an Ergo script I have a template where I put any 32-character hexadecimal string and I get the same template_id… however, if I put 32 zeros, the template_id changes.

---

**2025-11-20T15:49:29**

Not sure if this is the best way to share the code ... https://github.com/StabilityNexus/BenefactionPlatform-Ergo/commit/ea59d6a1d1cc26eb16977d41742f287770dc7657

==

In Bene we need to distinguish between using ERG or any other token. So far we’ve left ERG empty (base_token_id == ""), but its template differs from the token version—presumably due to the constant’s length.

I tried using hexadecimal 0, but the template still changes only in this case (see paper.md).
Does that make sense?

---

**2025-11-21T06:27:43**

https://github.com/StabilityNexus/BenefactionPlatform-Ergo/blob/ea59d6a1d1cc26eb16977d41742f287770dc7657/contracts/bene_contract/contract_v1_2.es#L372

IsErgBased variable is used in the contract.
Unique difference is 0s instead of anything else

---

**2025-11-21T06:50:45**

Okey thanks... I will fetch both templates for now

---

**2025-11-21T10:01:28**

About this… it seems that a 0’s value is treated the same as an empty Coll[Byte]. And I understand that the template ID changes because it has a different length.
I think I’ll have to work with both templates.
@kushti_ru

---

**2025-11-24T12:17:04**

I'm not sure I understood you correctly. The problem is that there really isn’t any trusted node to confirm the transaction. Does the NIPoPoW proof make it possible to ensure that the transaction was carried out (with a preselected difficulty and number of confirmations) without needing to rely on a node afterward?

---

**2025-11-24T12:26:16**

I’m not sure I’m explaining myself well. A practical example: I’m going to a deserted island to set up a coconut shop. I want to accept ERG payments from my island, which has no internet connection. So I write down in a notebook the last block of the network and the current difficulty.

I tell everyone that whoever wants to come to my island to buy coconuts must bring proof that they’ve paid me 1 ERG for each coconut they want. So they arrive on my island and say: “Hey, look, this is the new block X. In it you can find transaction T, which you can clearly see sends 2 ERGs to your address, so give me two coconuts. It was mined with this difficulty, and before it is the last block you saw before coming here.” And I, even while being on my deserted island, will know that the person is either telling me the truth, or is such a chad that they mined a block by themselves just to get two of my coconuts (they lied, but I don’t care, let them have the two coconuts).

Will I be able to run my coconut shop with peace of mind, trusting that my ERG wallet is filling up even though I can never actually verify it? (Except in cases where chads show up who mine fake blocks—but I don’t care about those.)

---

**2025-11-25T08:30:39**

https://app.rosen.tech/events/43acfb9f8b44abe197d5e01e2f3724195d047fd15df22878fc4502669e70c436

"Application error: a client-side exception has occurred (see the browser console for more information)."
"TypeError: Cannot read properties of null (reading 'slice')"

---

**2025-11-26T09:00:26**

🔥🔥 perfect !!! That is great news

---

**2025-11-26T09:01:55**

is there a library to validate this type of things.??   sigma-rust can be used for that?

---

**2025-11-27T09:08:03**

Cool... What is the state of this?? Is done?

---

**2025-12-04T01:49:06**

I'm still working on Game of Prompts. This will allow me to give the Celaut node a first real use in terms of how services are built and distributed, even though each user runs the services on their own node. A real application will let me see potential issues that I might not notice by simply testing with dummy services.
After that, I'll work on bringing the payment/reputation systems from alpha to beta and moving that toward Basis.

---

**2025-12-05T04:42:38**

Really?

---

**2025-12-11T12:09:16**

Opinions about use an ERG wrapper?
https://ergoforum.aap.cornell.edu/t/simplifying-game-of-prompts-contracts-why-not-use-only-tokens/5293

---

**2025-12-16T23:58:18**

val authorizedToEnd: SigmaProp = {

        val resolverAuth: SigmaProp = {
          val prefix = resolverPK.slice(0, 3)
          val addr_content = resolverPK.slice(3, resolverPK.size)

          val isP2PK = prefix == P2PK_ERGOTREE_PREFIX
          if (isP2PK) {
            proveDlog(decodePoint(addr_content))
          }
          else {
            sigmaProp(INPUTS.exists({ (box: Box) => box.propositionBytes == resolverPK }))
          }
        }
        
        val winnerAuth: SigmaProp = {
          val winnerBoxes = INPUTS.filter({ (box: Box) => 
              blake2b256(box.propositionBytes) == PARTICIPATION_SCRIPT_HASH && 
              box.R5[Coll[Byte]].get == winnerCandidateCommitment 
          })
          if (winnerBoxes.size > 0) {
            val winnerPK = winnerBoxes(0).R4[Coll[Byte]].get
            val prefix = winnerPK.slice(0, 3)
            val addr_content = winnerPK.slice(3, winnerPK.size)

            val isP2PK = prefix == P2PK_ERGOTREE_PREFIX
            if (isP2PK) {
              proveDlog(decodePoint(addr_content))
            }
            else {
              sigmaProp(INPUTS.exists({ (box: Box) => box.propositionBytes == winnerPK }))
            }
          } else {
            // Si no se encuentra la caja del ganador, la autorización falla
            sigmaProp(false)
          }
        }

        if (winnerCandidateCommitment != Coll[Byte]()) {
          winnerAuth || resolverAuth
        } else {
          resolverAuth
        }
      }



This raises "Malformed transaction: Scripts of all transaction inputs should pass verification. b32bbdd8dd9b5d92894439d0a60c1ba6201d727b9dbd5f419786f510046ad02d: #0 => Success((false,1712))"


But the same replacing "winnerAuth || resolverAuth" with "winnerAuth"  works.   (winnerPK == resolverPK)


What is the problem here?

---

**2025-12-16T23:59:05**

I don't understand why, but with fleetsdk - mockchain works.
Fails on-chain.

---

**2025-12-17T08:34:04**

val P2PK_ERGOTREE_PREFIX = fromBase16("0008cd")

resolverPK and winnerPK are proposition_bytes. So the prefix lets us know whether we can perform proveDlog; if we can’t, it proves authenticity by spending some input.

---

**2025-12-17T13:20:57**

Game of Prompts: I’m finishing up the interface and the contract. I’ll very likely have it completed before the end of the year. I’d like to run a small test competition with anyone who wants to participate, to try things out and gather feedback.

The Bene Wallet UI library received two or three PRs implementing ErgoPay, which has now been added to Nautilus and Safew.

Bene received more than 50 PRs!!! Some of them (I think four) focused on searching for potential bugs in the contract. In the end, they all turned out to be false positives, but it’s great to see the effort people put into reviewing the contract. It’s reassuring that multiple third parties took the time to examine it carefully, even if no issues were ultimately found.

---

**2025-12-17T13:22:28**

I didn’t mention it before, but all of the PRs came from the Unstoppable Hackathon.

---

**2026-01-10T11:27:52**

I think I don’t understand a simple concept about token uniqueness in Ergo. When minting a token, can it end up in two output boxes at the same time? How is this possible?

This is the token:
https://explorer.ergoplatform.com/en/token/a4a52dd17d6c1af1a024422b06906d3060ac12c7aa5fdbfaec92240c24a2d619

And this is the mint tx of the token:
https://explorer.ergoplatform.com/en/transactions/576bcd3afc4dc4d1d1b89b0617dba93c2e0aa38cfab55c5a13f45ca3b9067ded

As you can see, Output(0) and Output(1), both, contains the emission amount of the token.
Why is that possible?

---

**2026-01-10T12:25:14**

In that case the emission amount is not 100000002, is 200000004

---

**2026-01-10T12:25:28**

??

---

**2026-01-10T13:22:21**

So the explorer is wrong @kushti_ru @LuivatraEP

---

**2026-01-10T18:12:44**

Yeah, that's an issue 😅

---

**2026-01-10T18:15:49**

Hide emission amount or fix it, I agree. But show an incorrect emission amount is a problem

---

**2026-01-10T18:24:35**

I approved Bene’s PR to mint an EIP-004 NFT and add it directly to the contract in a single transaction... It seemed strange to me, but I tested it and saw that it worked... Although, checking it more thoroughly today, I’ve noticed this. I'll have to use chained transactions

---

**2026-01-11T05:02:16**

maybe, there is a gql ui to check?

---

**2026-01-11T07:56:13**

Okey.  You see an error on the tx code?

---

**2026-01-11T07:56:54**

No, nothing in console.

---

**2026-01-11T10:44:29**

oh, i don't checked extension console.

but was due to pass an array of objects because of chained tx. 
Now is solved.       Sign each tx one per one is required, but works.

---

**2026-01-16T12:25:25**

I’m finishing the Game of Prompts app. Just small details left, in fact; the contracts (both on-chain and off-chain) look pretty solid to me.

I’m planning to organize a first test competition with the Snake game at no cost (a minimal amount of ERG or a test token), but in such a way that the winner still receives the prize NFT and the judges can earn reputation.

If anyone is interested, they can join the Game of Prompts Telegram to stay up to date or ask anything they want.

---

**2026-01-16T12:26:00**

After testing it thoroughly, I’ll work on games related to algorithmic trading, possibly.

---

**2026-01-16T13:30:02**

I can't share, messages are deleted with link

---

**2026-01-22T00:37:03**

Game of Prompts

Shared a video, docs, and an app on TG with some mates. After receiving some feedback, I’ll need to add another action to the contract, so it’s still in development.

Celaut Project

After four months without touching my beloved node…

I worked on a rootless configuration of the node, but abandoned it because it’s a dead end.

For those who don’t want to trust running the node with sudo, an .ova will be distributed; it’s the only feasible solution I can think of.

Likewise, several commands have been added, and the node’s use of Docker is now isolated from any Docker the user may be using.

---

**2026-01-23T03:48:35**

Some explorer working??

---

**2026-01-23T03:52:51**

okeyy

---

**2026-01-23T06:07:43**

I still get errors with this nautilus endpoints

---

**2026-01-28T08:31:44**

Are the explorers having the same problem as last week? I’m getting ‘Malformed transaction… Missing inputs: 0.’

---

**2026-01-28T08:33:41**

sending a token with nautilus

---

**2026-01-28T10:25:08**

Thanks you for the support

---

**2026-02-02T15:39:22**

Is there any reason why EIP-4 uses SHA-256 instead of BLAKE?

---

**2026-02-03T16:22:33**

I’m facing a "ghost register" issue with @fleet-sdk/core ^0.12.0 that makes no sense.

The Setup:

I have a contract UTXO. I log its R5 before and after TransactionBuilder.build().

console.log always shows R5: 05a49ed101 (1714066).

The unsignedTransaction.inputs[0] also shows the same value.


When I call ergo.sign_tx and submit_tx, the Node rejects it with a script error, but the Diagnostic Info shows a completely different R5 for that same input (same index)!

Test 1: Node says SELF.R5 is 1714239.

Test 2: Node says SELF.R5 is 1714260.

How is this possible? 1. If the input box is the same, why does the Node see different Register values than what Fleet has in the unsignedTransaction?

2. Does ergo.sign_tx (Wallet) fetch the box again and overwrite the registers I manually set in the inputs array?

3. Is it possible that the Wallet is injecting a different version of the UTXO from its own cache?

parseBox and TransactionBuilder seem to hold the "correct" local value, but it "mutates" upon signing/submission. Any clues?

---

**2026-02-03T16:26:15**

https://github.com/game-of-prompts/app/blob/main/src/lib/ergo/actions/drain_cancelled_game_stake.ts#L73

---

**2026-02-06T07:38:33**

Thanks a lot ser! 🫡

---

