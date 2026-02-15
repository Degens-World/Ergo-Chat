# error

**Total messages:** 11

---

**2022-10-04T07:41:32**

I'll have to take the fall for this one and do some doxxing in the process. The spectrum implementation works as intended. My modified offchain bot (using sigma-rust) was supplying an empty variable to ErgoBoxCandidateBuilder which in turn generated the 0 creation height. This has been fixed now.

---

**2022-10-04T08:04:16**

I'm going to do some swaps in all t2t pools to bring the creationHeight on all pool boxes up to date

---

**2022-10-04T08:07:32**

true, but it will solve the issue I created at least :)

---

**2022-10-05T06:16:56**

in regards to the spectrum trades: it was a bug in a piece of bot code written by me that resulted in some boxes with 0 creation height. So no correlation to spectrum other than a community dev using their platform.

---

**2023-05-14T13:29:31**

could it be that the key you have is not the root key, but the already derived key for a specific address? I had a similar case where I tried recovering from a mixer address. the mixer had the derived key for the address saved in the db. Just used that to sign the tx recovering my funds.

---

**2024-12-21T01:43:07**

@kushti_ru midway syncing with 5.1.1 hanged with this error. Lmk if you need more info before syncing again.

ERROR [tor.default-dispatcher-21] a.actor.OneForOneStrategy - block checksum mismatch: stored(context removed) = 3725640198, computed = 2535819405, type = 4  in /ergo/node/.ergo/history/extra/012139.sst offset 1761285 size 5394
org.rocksdb.RocksDBException: block checksum mismatch: stored(context removed) = 3725640198, computed = 2535819405, type = 4  in /ergo/node/.ergo/history/extra/012139.sst offset 1761285 size 5394

---

**2024-12-21T02:48:39**

Hmm, could be the disk, had some issues in the past on this node. Other node syncs fine, almost done. Will just copy everything over when it’s done

---

**2024-12-25T00:52:46**

I found it best to let it sync first and then enable indexing

---

**2025-11-03T10:24:49**

p2p performance is unfortunately not on par with the hetzner servers. At least from my observation. If you try to monitor for example oracle contracts addresses it just times out in p2p whereas hetzner server delivers the result

---

**2025-11-03T10:27:25**

https://explorer-p2p.ergoplatform.com/en/addresses/2vTHJzWVd7ryXrP3fH9KfEFH2W62Njq1GBzqyvJUvZZAdMsYNN5dbwF9sC3raNEdCUK4xw4Ygjkz41mYRiAWsyFHLeAESUuDxTpbuyG77Y9riUxJN9tMZ6nLCLTpgP5T2XoaYEgGaBkbaf1n5fqUjFUvpoeFr9cLoHRevEEQAiQ6QKEaqsPaWrUq6TbujgvqEw6gB35xug7WKjANyZePMyyrbE1ySthXjLCj6KUGdruDaw63LQdk6XxVNjVdppMW9jHJt6xCGJn93gqtLGUeoErHeX3t3K93KC4Z?offset=0

---

**2025-11-03T10:34:15**

maybe someone can dump the hetzner db schema and check for diffs with yours. it's possible someone made tweaks and they are not in documented

---

