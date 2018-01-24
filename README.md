# TokenRegistry

FutureHack subbmission team[ ZeroPass](https://www.zeropass.io/)

Repositories submitted \(will add them more later!\);

• Smartcontract  
[https://github.com/ZeroPass/Token-registry-smart-contract](https://github.com/ZeroPass/Token-registry-smart-contract)

• NFC SDK/android app; \(trid-token registry id\)  
[https://github.com/ZeroPass/Android-trid](https://github.com/ZeroPass/Android-trid)

We are hacking the passport hardware security module \(active authentication\), to provide us with valid signature on the passport itself \(the signature can’t be spoofed, even if Android phone is compromised!\).  
Documentation is nearly non-existent.

We send the hashed Ethereum account address to the passport and receive back the signature.

After that we use a smart contract to check the validity of that signature, and we write the attestation of our Ethereum account to the smart contract itself. The account is a standard ERC20 style contract with some additional functions.

That if everything goes according to plan.

---

### How to install and run the code:

**For android app;**

• Use the newest android studio \(with Gradle\),

• download code from Github, and import it

• build-it to the device.** **

**Smart contract is deployed on;**

[https://rinkeby.etherscan.io/address/0xee2ba50c1cbd227a035090d99dec587ae9efb3bc](https://rinkeby.etherscan.io/address/0xee2ba50c1cbd227a035090d99dec587ae9efb3bc)

### How to use the proof of concept;

**1.\)** Open the android app

**2.\)** Type those 3 number groups in the app fields  \(we would implement camera scan if we had more time\)![](/assets/import.png)

This is used to create the **BAC**  [https://en.wikipedia.org/wiki/Basic\_access\_control](https://en.wikipedia.org/wiki/Basic_access_control) that negotiates a session key which is then used to encrypt challenge response communication between phone and passport.

**3.\)** Touch the passport with NFC, that would sign the hash of Ethereum public address

**4.\)** Copy the signed data and transfer it to the [https://remix.ethereum.org/](https://remix.ethereum.org/) \(we would implement an API given more time\)

**5.\)** Send the transaction

### If things break;

this is all heavily experimental, opensource libraries are stubs with wrong information, docs are scarce and written for industry people. That was tough nut to crack in 2 days.

We are sending the example passport data \(from our passport, precomputed\) to James. It’s a security risk, so we cannot post it here, so please check the Slack. This data can then be imputed into the smart-contract directly.

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

Whenever you want to secure/attest your Ethereum account, you just;

1. Open the android app
2. Input/scan ethereum address
3. take NFC enabled phone, and touch it with your passport

#### Ease of use;

Nothing to remember or write down \(passwords\), just scan with camera, then touch and go.

If your phone lacks NFC, you can use your friend's phone, this can not be hacked!

#### Implications of our solution and future work;

You can secure your accounts with attestation and that restricts you to sending tokens only to other registered/attested account.

You could also have time limits on transactions that goes out of your country \(based on passport certification authority\).

---

### Alternate uses of this opensource solution

• on-chain voting \(one Passport- one vote\)  
• on-chain KYC \(know your customer\)  
• "universal basic income -UBI" token distributions  
• Sybil protection  
• blockchain oracle \(public\) attestations  
• authentication

---





