# Quibbix

**Total messages:** 4

---

**2025-10-23T11:26:51**

Hi. I am trying to write ergoscript and compile to address. Why does escript.online and node api /script/p2sAddress generate different addresses??

This is my simple lock script 
sigmaProp({
  val myAddrPropBytes = PK("9i7kLnWJYEnQRHBL4vrkEkFnas5oWZB9pyC3gk8XwV25bh8n82A").propBytes
  val unlockHeight = 1640416

  INPUTS.exists({ (b: Box) => b.propositionBytes == myAddrPropBytes }) && (HEIGHT >= unlockHeight)
})
escript produces this address:  6KxurWda474G6qwSe1R2eZwDNEpcT8SEUyAHsx4mASQvQCRAH1BMFnwDCFrDMcSdQuUVHc5XfnisVmbztCxVztXrULE

node api this: 2CBksoLo3KeBYLgYWvYGjWxNVspYXvNeiHgMjw4ZRtsu69pSqcAhZVZ3J89CAgRHiYFze97irYYUxBnqRFbzWHHgwS

?

---

**2025-10-23T12:09:34**

In node I changed between 0 and 1 as versions but it produces same tree still.

---

**2025-10-23T12:23:37**

Yes, i use this

{
  "source": "sigmaProp({ val myAddrPropBytes = PK(\"9i7kLnWJYEnQRHBL4vrkEkFnas5oWZB9pyC3gk8XwV25bh8n82A\").propBytes; val unlockHeight = 1640416; INPUTS.exists({ (b: Box) => b.propositionBytes == myAddrPropBytes }) && (HEIGHT >= unlockHeight) })",
  "treeVersion": 1
}

with 1 and 0 it produces same address

---

**2025-10-23T14:20:24**

So does it mean it mean both addresses can be used and will be executed correctly? I don't understand what version 0 or 1 means.

---

