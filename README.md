# TokenRegistry

FutureHack subbmission

Repositories submitted \(will add them more later!\);

• Smartcontract  
[https://github.com/ZeroPass/Token-registry-smart-contract](https://github.com/ZeroPass/Token-registry-smart-contract)

• nfc sdk/android app; \(trid-token registry id\)  
[https://github.com/ZeroPass/Android-trid](https://github.com/ZeroPass/Android-trid)

We are hacking the passport hardware security module \(active authentication\), to provide us with valid signature on the passport itself \(the signature cant be spoofed, even if android is compromised!\).

We send the hashed ethereum account address to the passport and receive back signature.

Then we are using a smartcontract to check the validity of that signature, and we write attestation of our ethereum account to the smarcontract itself. Account is the standard the erc20 style contract with some additonal functions\).  
  
That if everything goes according to plan.

---

### Theme:

**Regulation that doesn't leave people and technology behind a closed door.**

The main innovation brought forward by Bitcoin and other cryptocurrencies is the creation of digital bearer instruments - like cash or bearer bonds, but in the digital realm. These instruments use computer code \(so called smart contracts\) instead of the traditional judiciary system to determine the ownership of assets \(coins or tokens\).

Bearer instruments and shares are banned/restricted in most countries, main reason being potential for abuse, such as tax evasion, illicit movement of funds, and money laundering. In addition, the ownership is extremely difficult to establish in the event of loss or theft.

Banks do not want to serve crowdfunding \(ICO\) efforts fearing regulatory clampdown, thus leaving raised funds in perpetual limbo.

### The challenge:

Turn bearer instruments back to registered ones \(via retroactive identification / KYC\), in a way that wouldn’t stifle innovation or discourage the public to participate in the value distribution of these exciting new systems.

### The Solution:

Android app, Passport with chip, smartcontract \(extended erc20\).

Whenever you want to secure/attest your ethereum account, you just;  
• Open the android app

• Input/scan ethereum address

• take NFC enabled phone, and touch it with your passport

You can use your friends phone, this cant be hacked!

