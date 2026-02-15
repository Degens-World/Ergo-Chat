# Superellipse

**Total messages:** 5

---

**2025-11-24T06:39:19**

Please read the versions of required building tools in the first message in PR. 
Don't update the gradle if suggested by Android Studio (and don't use the newest Studio itself).

In particular, one of the errors I see in screenshot - caused by JVM version for gradle. Use JVM 17, not the very newest ones. You can select it here: File->Settings->Build,Execution,Deployment->Build Tools->Gradle->Gradle JDK

---

**2025-11-26T17:21:24**

Plan to start working on this issue in a few days

---

**2025-12-02T07:41:05**

@kushti_ru

Guys, I finished updating ergo-wallet-app code to support new versions of Android 15 (and now iOS).

A lot of changes were required to support Android 15. Along the way, iOS module has also been updated with higher component versions, incl. Java.

That is why I double checked the iOS build. As it turned out, newest MobiVM 2.3.24 is required to build the wallet for iOS - it supports the changes. Wallet builds successfully using XCode 26.1.1 + Android Studio 2024.2.2. Patch 2 + MobiVM 2.3.24. Runs without issues on recent iOS versions.
Tested on iPhone 12 mini (iOS 18.6.2).

My pull request passes all automatic checks, no conflicts to base branch. 
https://github.com/ergoplatform/ergo-wallet-app/pull/188

Probably we need to change the version of the app and year of release (in About window). But, overall, it is ready to be released.

---

**2025-12-08T04:10:06**

I think 188 should go first, as it is more urgently needed.

182 &183 can be added afterwards if no conflicts after merging the 188

---

**2025-12-24T18:25:40**

Thank you for the quick merge, PM sent.

---

