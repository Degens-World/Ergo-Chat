# C B

**Total messages:** 17

---

**2025-11-10T11:14:07**

The README.md is updated and ready for review https://github.com/ergoplatform/explorer-backend/pull/260 

The status is waiting to be reviewed and reported https://github.com/ergoplatform/sigmastate-interpreter/pull/1086

---

**2025-11-12T11:48:06**

Explorer-Backend:

https://github.com/ergoplatform/explorer-backend/pull/260 (Checked and Accepted) ✅

https://github.com/ergoplatform/explorer-backend/pull/261 (Ready for review)

Sigmastate-Interpreter

https://github.com/ergoplatform/sigmastate-interpreter/pull/1086 (Ready for review)

---

**2025-11-18T07:16:33**

Good. I still have open PR that’s need to checked.

Sigmastate-Interpreter

https://github.com/ergoplatform/sigmastate-interpreter/pull/1086 (Passed Test. Need review

https://github.com/ergoplatform/sigmastate-interpreter/pull/1088 (Passed tests. Needs review)

https://github.com/ergoplatform/sigmastate-interpreter/pull/1089 (Passed all test. Needs review)

Explorer- 

https://github.com/ergoplatform/explorer-backend/pull/260 (Done, waiting on compensation)

https://github.com/ergoplatform/explorer-backend/pull/261 ( Still needs review)

---

**2025-11-18T12:09:42**

Damn.  No response and switched to a different chat immediately after I sent that message, and then continue to chat as if I can’t see y’all. That’s disrespectful.

---

**2025-11-18T14:03:55**

Which ever one is linked to the general chat in the discord

---

**2025-11-18T14:11:57**

Ok

---

**2025-11-19T09:53:45**

I would say find a balance. A way to get incoming submissions for bounties more frequently but have the guard rails implemented in a manner that won’t deter devs, community members from helping.

---

**2025-11-19T11:34:23**

Ok. The bugdetection.scala file should have the tests that were created to find where the inconsistencies for occurring. The test pointed me to txsBuildFrom function in the package.scala file. I thought that was the root issue and that’s where I focused my fix

---

**2025-11-19T11:40:04**

And also I was having issues with sbt dependencies and got an errors related to ergo-wallet_2.12:v3.3.8-aaaab5ef-SNAPSHOT . So I figured I had two options: 1) literally wait or update those dependencies myself or 2) create a workaround for when the dependencies issues do get resolved, the fix should still be valid. That’s was my thought process

---

**2025-11-19T11:58:31**

Ok will do. To be fair, for that particular PR request out the 16 files that changed, the only src/main file that was changed was the package.scala file and I didn’t know how to really present the resolution in the request without changing it myself. The other 15 files are test files in src/test folder.

---

**2025-11-24T05:50:58**

I reverted the changes to help with the errors. Ready for testing

---

**2025-11-24T06:33:10**

This one. I got an email notification about it https://github.com/ergoplatform/ergo/actions/runs/19042705601

---

**2025-11-24T11:27:13**

https://github.com/ergoplatform/explorer-backend/pull/261

I redid the bounty without the ergo wallet dependencies work around as requested. The fix should work up with updated dependencies. Also cleaned up all the unnecessary code and files generated. Now there’s a commit message detailing root cause and the fix

---

**2025-11-26T13:35:27**

Apologies I just got off a plane. I need to catch up a bit

---

**2025-11-26T13:38:28**

Should I separate the two PRs from each other than resubmit?

---

**2025-11-26T13:41:09**

Alright I’m on it

---

**2025-12-01T05:47:10**

@Pgr456 https://github.com/ergoplatform/explorer-backend/pull/261 I separated the two PR requests. The request should now be a test to prove the bug and fix recommendations. No main files touched and only one test created


For https://github.com/ergoplatform/explorer-backend/pull/260 I removed the submission file as requested.

Side note: Working on in-wallet safety deposit boxes with inheritance features. Should have something tangible to share by the end of the week

---

