# Cheese

**Total messages:** 18

---

**2022-03-28T13:04:11**

I feel like we’ve been having small sync issues for the past week that have been building up

---

**2022-04-15T03:35:50**

Computational cost limit per block is 8M, but can be voted on by miners. Usually when I have txs with low enough cost I’ve been able to chain them arbitrarily, I’ve definitely done more than 3 in a single block.

---

**2022-04-15T03:42:46**

Yeah not having to go through each and every if branch should help a ton, hopefully v5.0 comes soon

---

**2022-12-19T13:58:05**

For p2s, a specific context var number can be set as a standard (assuming that vars need not start from 0).

---

**2022-12-19T14:10:03**

I think restriction to just p2pk and multisig outputs makes the most sense then. Dealing with p2s gets messy and I see no good point in adding messages / attatchments there in the first place. But, I dont see myself using this feature much anyway so 🤷‍♂️

---

**2022-12-19T14:11:36**

I think 2 is an incorrect assumption. Order book style p2s (and others) contracts may set registers only accessed by a contract which is to be spent as a second input. Registers need not be only accessed by the box they are set on.

---

**2022-12-19T14:12:22**

The box that has the register set on it may only check that the second input is of correct propbyte hash.

---

**2022-12-19T14:14:10**

In general, I feel p2s has too many possibilities to make assumptions like that.

---

**2022-12-19T14:16:58**

Are babel outputs going to p2pk or p2s? My issue is coming from setting registers on theoretically any p2s output, at least with p2pk you can always just respend it afterwards.

---

**2024-12-27T10:49:58**

Late Lithos Update:
- Finishing up last few NISP contracts, then building tests
- Figured out the initial design for the optimistic rollup and how the fraud proof contracts will interact with it.

---

**2025-08-11T10:54:21**

Yes, I'll be sending you some contracts to look over soon 😁

---

**2025-11-15T17:57:21**

I guess I would need to to know more about how LLM inference would work across a group of miners. Lithos is relying on the "goodness" concept of NiPoPoWs, where we can verify work was done based on statistical properties of sets of hashes. Not sure how that would translate to LLM work. If you can explain more the idea I can try to see if it could work in Lithos.

---

**2025-11-20T12:03:03**

USE is related to dexy or is it a separate protocol?

---

**2025-11-22T16:38:49**

@kushti_ru Is it possible to add this api route into current mainnet and testnet builds? Please review and let me know if anything needs changing.

https://github.com/ergoplatform/ergo/pull/2255

---

**2025-11-22T17:05:46**

I assume you mean for the lender receiving the block reward? Yes, lithos client will keep track of it. I guess it would be good for nautilus to also scan the mining reward contract for new utxos as well.

---

**2025-12-03T17:02:08**

Lithos
-----------------
Just released testnet version 2.0.2:
- Fixed sync bug which attempted to apply transformations to NISPTrees which were already dropped
- Fixed bug regarding fraud proof evaluation of NISPs with small sizes
- Improved logging for synchronization and transformations
https://github.com/Lithos-Protocol/Lithos-Client/releases/tag/v2.0.2-test


Since last dev update, we've added the following:
- detection and saving of NISPs
- fraud proof contracts
- evaluation of fraud proofs to remove invalid share proofs
- various stratum and synchronization bug fixes

---

**2025-12-17T18:39:10**

Lithos:
- Released version 2.2.0
https://github.com/Lithos-Protocol/Lithos-Client/releases/tag/v2.2.0-test

- Upgraded sync process to be multi-threaded
- Rollups / NISPTrees now sync individually
- Changed logging for sync process
- Most APIs listing data objects are now sorted by height of the mined block they are associated with
- Fixed LDB errors related to multiple database instances

---

**2026-01-15T17:25:43**

Yes done with Lithos 3.0 now so am focusing on appkit

---

