# TokenRegistry

FutureHack subbmission team[ ZeroPass](https://www.zeropass.io/)

Repositories submitted \(will add them more later!\);

• Smartcontract  
[https://github.com/ZeroPass/Token-registry-smart-contract](https://github.com/ZeroPass/Token-registry-smart-contract)

• NFC SDK/android app; \(trid-token registry id\)  
[https://github.com/ZeroPass/Android-trid](https://github.com/ZeroPass/Android-trid)

We are hacking the passport hardware security module \(active authentication\), to provide us with valid signature on the passport itself \(the signature cant be spoofed, even if android phone  is compromised!\).  
Documentation is nearly non-existent.

We send the hashed Ethereum account address to the passport and receive back signature.

Then we are using a smartcontract to check the validity of that signature, and we write attestation of our ethereum account to the smarcontract itself. Account is the standard the ERC20 style contract with some additional functions\).

That if everything goes according to plan.

---

### how to install and run the code:

/////to be added

---

### Theme:

**Regulation that doesn't leave people and technology behind a closed door.**

The main innovation brought forward by Bitcoin and other cryptocurrencies is the creation of digital bearer instruments - like cash or bearer bonds, but in the digital realm. These instruments use computer code \(so called smart contracts\) instead of the traditional judiciary system to determine the ownership of assets \(coins or tokens\).

Bearer instruments and shares are banned/restricted in most countries, main reason being potential for abuse, such as tax evasion, illicit movement of funds, and money laundering. In addition, the ownership is extremely difficult to establish in the event of loss or theft.

Banks do not want to serve crowdfunding \(ICO\) efforts fearing regulatory clampdown, thus leaving raised funds in perpetual limbo.

### The challenge:

Turn bearer instruments back to registered ones \(via retroactive identification / KYC\), in a way that wouldn’t stifle innovation or discourage the public to participate in the value distribution of these exciting new systems.

---

### The Solution:

Android app, Passport with chip, smartcontract \(extended erc20\).

Whenever you want to secure/attest your ethereum account, you just;

1. Open the android app
2. Input/scan ethereum address
3. take NFC enabled phone, and touch it with your passport

##### Ease of use;

No passwords/usarnames/, just touch and go.

If your phone lacks NFC, you can use your friend's phone, this cant be hacked!

---

#### Alternate uses of this opensource solution

• on-chain voting \(one Passport- one vote\)  
• on-chain KYC \(know your customer\)  
• "universal basic income -UBI" token distributions  
• Sybil protection  
• blockchain oracle \(public\) attestations  
• authentication

