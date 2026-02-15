# Alex Slesarenko

**Total messages:** 17

---

**2023-02-24T07:33:00**

which language you are using

---

**2023-02-24T07:33:57**

then you don't need to parse anything, use Appkit

---

**2023-02-24T07:35:46**

Ah, then you can use serializers from Sigma

---

**2023-02-24T07:41:33**

why you don't want to use existing serializers and just parse modifiers?

---

**2023-02-24T07:44:48**

oh, really?

---

**2023-02-24T07:45:40**

You will need to know the exact serialization format. There is this spec https://ergoplatform.org/docs/ErgoTree.pdf

---

**2023-02-24T07:47:27**

Then you can use latest (not yet released) version of Sigma, where ErgoScript compiler is separated from protocol implementation

---

**2023-02-24T07:49:36**

try the develop branch and see interpreter module. If you can assemble interpreter it should be all you need

---

**2023-02-24T07:50:16**

I mean something like sbt interpreter/assembly

---

**2023-02-24T07:51:34**

I'm haven't tried it though, may not work like this

---

**2023-02-24T07:55:24**

I highly respect all the efforts of digging deep into low level programming. But be wary of reinventing the wheel, especially when it is not necessary 🙂
Anyway, Sigma sources is your best friend.

---

**2023-02-24T07:59:17**

You need to look at SigmaBoolean.serializer and understand of how SigmaBoolean value is serialized. ProveDlog is one of the SigmaBoolean subclasses

---

**2023-02-24T08:00:09**

And you also can look at ContextExtensions serializer

---

**2023-02-24T08:01:10**

SigmaBoolean is a recursive data structure, you cannot skip its parsing easilly

---

**2023-02-24T08:03:29**

Look at the code, they are quite different.

---

**2023-02-24T08:04:25**

SigmaBoolean is a boolean-like logic over sigma propositions.

---

**2023-02-24T08:04:32**

Hence the name

---

