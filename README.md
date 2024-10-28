# Not so awesome Web3 Security Researcher roadmap

Of course, this is not awesome. This is not the curated list of blue underlined [words](https://blank.page/) that you will click, read, and jump to the next one, hoping to finish as fast as possible—or maybe hoping not to finish at all. You are going to become a security **RESEARCHER**. Yeah, **RESEARCHER**. No one is going to find vulnerabilities for you or point out the functions where they are hiding. You are going to have to dig, **research**, and find them **yourself**. So the path to becoming a security researcher? It’s all about research.

If you really want to become a Web3 Security Researcher, let’s set this straight from the start: **there are no deadlines**. If you are thinking “2 months, 6 months, 1 year, 10 years” to become a researcher, forget those timelines. Relax. The only rule is to never waste a single day without learning something new. And yes, read this to the end!

Tigran Piliposyan

<a href="https://twitter.com/tpiliposian" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow"></a>

## Contents

- [Introduction](#introduction)
- [X](#x)
- [EVM and Solidity](#evm-and-solidity)
- [DeFi](#defi)
- [X2 or Blogs](#x2-or-blogs)
- [CTFs](#ctfs)
- [Contests and Bug Bounties](#contests-and-bug-bounties)
- [Continuous Learning](#continuous-learning)
- [Closing Remarks](#closing-remarks)
- [Traditional Roadmaps](#traditional-roadmaps)

## Introduction

Alright, before we get too deep into this, let me introduce myself. I am Tigran Piliposyan ([@tpiliposian](https://twitter.com/tpiliposian)), a Security Researcher at [Hexens](https://hexens.io/) for over a year now. I’m not here to pretend I’m some all-knowing security wizard sitting and cracking smart contracts left and right. No, I’m just someone who started from **ABSOLUTE** zero at age 29, leaving my previous workplace, with a family and two daughters to care for, and starting something completely new. I didn’t even know that there was a Web2, and now suddenly it’s Web3, or what blockchain even was! I didn’t know any programming languages either. (A bit more about that story [here](https://x.com/tpiliposian/status/1699805833167614299)).

I learned everything I could find. I went through all the roadmaps, consumed every piece of content available, and to be honest, it was kind of funny. It felt like the true start of a researcher’s journey, which I guess is the right way to begin. But once I actually started working, looking back, I realized I had wasted a lot of time simply because I didn’t know what to read or listen to first, what should come before or after. If someone had just sat down with me and told me step by step what to research, it would have been amazing.

Yes, the Hexens team helped me, but they couldn’t sit with me all day long. Plus, I was still working at the Central Bank, so I had to juggle this in parallel. It’s been a grind. And I always had this idea to write a roadmap, but I didn’t want it to be just another batch of links. Instead, I decided to write it in a way that feels like someone is sitting with you, guiding you on your journey to becoming a security researcher. But if you still prefer the traditional style—I’ve collected a few solid roadmaps in the [Traditional Roadmaps](#traditional-roadmaps) section.

And if you’re reading this, I’m guessing you’re ready for the same kind of grind—minus a few bumps and bruises because, hey, I’ve made enough mistakes for both of us.

## X

Let’s start with the easiest part: X (or Twitter, as many of us still call it). You might think Twitter is just for memes and celebrity drama, but for the Web3 security world, it’s the place to be. No, seriously—pretty much the entire Web3 security community lives on Twitter. It’s like a continuous stream of information, with people sharing everything from vulnerabilities to in-depth analyses and the latest research. To be honest, it’s not just for security researchers—developers or anyone who wants to be a top professional should stay tuned to updates, new technologies, and any breaking news.

The cool thing about this space is that everyone’s out there posting content. You’ll find security researchers sharing their knowledge, bug bounty hunters celebrating their discoveries, and protocols announcing bounty programs for anyone to find bugs in their smart contracts. And it’s all happening in real-time. Twitter is where you’ll get the fastest updates on new exploits, bug disclosures, and hacks, often before they even hit the news.

At first, I didn’t even have an account. When I first met with Hexens' CEO, [@Hexen1337](https://x.com/Hexen1337), he advised me to create one, and it quickly became a key tool for learning and growing. I followed accounts of security experts, read through long tweet threads dissecting the latest exploits, and stayed up to date with everything happening in the industry.

So, if you’re serious about becoming a Web3 security researcher, do yourself a favor: get on Twitter, follow the right people, and dive into the flow. After reading this, you can even post about it, give your feedback, or mention me—it would be a pleasure! You can also post throughout your journey. I know people who are now very famous, and they started by sharing every step of their journey.

## EVM and Solidity

Alright, by now, I assume you’ve set up your Twitter account, found some cool profiles to follow, and have started diving into the Web3 security. You’ve probably noticed how amazing the community is—everyone’s sharing what they’ve learned, posting insights, and spreading knowledge everywhere.

But now it’s time to start learning seriously. At first, I thought about splitting this into separate chapters: one for the **Ethereum Virtual Machine (EVM)** and another for **Solidity**. But then I realized that might get a bit dry. Plus, it’s much more effective to learn the theory while practicing at the same time. So, I decided to combine them into one chapter. Trust me, learning these in parallel will be more engaging and practical.

Maybe when you go to your first interview, the first questions you’ll face will be like, “What types of accounts are there in Ethereum?” or “Who is `tx.origin`, and who is `msg.sender`?”—stuff like that. A great way to learn all this is through the book [Mastering Ethereum](https://github.com/ethereumbook/ethereumbook). It covers all the basics. If you’re completely new to blockchain, I recommend starting with some articles or videos to get the basic concepts of blockchain. Once you have that, dive into the Ethereum book. At the same time, I started working through [CryptoZombies](https://cryptozombies.io/) for learning Solidity. It’s a fun way to get hands-on with the programming language, starting from absolute zero. Another great resource is [Patrick Collins](https://www.youtube.com/@PatrickAlphaC/videos) on YouTube. You can find everything you need to start there, and more. Use it to learn Solidity now, and remember his channel for later. I also wanted to mention [Cyfrin Updraft](https://www.cyfrin.io/updraft) and [Secureum Bootcamp](https://www.secureum.xyz/bootcamp/) I haven’t done myself, but I’ve seen a lot of people find success with it, so it’s definitely worth looking into.

Now, let's pin down some ideas here—not just for this chapter, but for the rest of your learning journey (and maybe for life in general. Yeah, I used to laugh at philosophy when I was a student, but now I catch myself doing it sometimes, lol). **If you’re learning something, make sure you understand it deeply**. It might feel like a waste of time now, but it’ll save you from having to go back later and relearn what you skipped, you probably won’t have the time or even the desire to go back and fix it. And when you leave gaps like that, they turn into weaknesses.

Lastly, what I’m suggesting here isn’t the one and only way to do it. Everyone learns differently, so explore other resources too. **But you don’t need to rush.** Focus on understanding the basics first.

**JUST DO NOT GET STUCK AT THIS STEP.** When I was going through this, I collected a millions of articles, thinking I needed to read everything right away. Believe me, you’ll read them all in one day, maybe... focus on what’s in front of you right now.

## DeFi

Ah, this is my favorite part, as I worked for over 10 years in traditional finance. It was my strength when I first started, as I didn’t have a technical background.

Just make sure you’re comfortable with everything up to this point and feel good about your Solidity skills. If not, don’t rush, but also don’t get stuck, cover what’s needed, and let's understand finance a bit.

Before we dive into the security side of things, it’s important to understand DeFi. You’ve probably heard terms like “liquidity pools,” or “flash loans,” etc. There are concepts in DeFi, and having a solid grasp of them is essential. I’d recommend starting with the biggest platforms like Uniswap, Aave, and Compound to see how they operate. A lot of great resources can be found on the [Whiteboard Crypto](https://www.youtube.com/@WhiteboardCrypto) YouTube channel. I learned a ton from them—it’s super easy to understand, and in my opinion, it’s all you need at this stage. Go start with their [What is DeFi?](https://www.youtube.com/watch?v=17QRFlml4pA) video and just keep researching. There’s also [Finematics](https://www.youtube.com/@Finematics), though I personally preferred Whiteboard Crypto when I was learning.

**Don’t spend too long on this part either, because I strongly believe that the best way to learn deeply is during your audits.** For now, you just need a big-picture understanding of everything.

Remember this book about AMMs, it's gold, now it may be a bit hard, but it’s a must-read: [Automated Market Makers: A Practical Guide to Decentralized Exchanges and Cryptocurrency Trading](https://www.oreilly.com/library/view/automated-market-makers/9781484286166/).

## X2 or Blogs

Yeah, back to Twitter again. If you’ve already found and started following some good blogs, that’s great. But if not, I want to make sure you know about a few that I personally read and have learned a lot from (and still do):

- [RareSkills](https://x.com/RareSkills_io) ([blog](rareskills.io/blog))
- [DevDacian](https://x.com/DevDacian) ([blog](https://dacian.me/))
- [Zellic](https://x.com/zellic_io) ([blog](https://www.zellic.io/blog/))
- [Trail of Bits](https://x.com/trailofbits) ([blog](https://blog.trailofbits.com/))
- [Hexens](https://x.com/hexensio) ([blog](https://hexens.io/blog)) (we’re working on the blog section right now, and I hope it will be ready by the time this goes open-source. Expect some cool stuff there!)
- [MixBytes](https://x.com/MixBytes) ([blog](https://mixbytes.io/blog))
- [Cyfrin Audits](https://x.com/CyfrinAudits) ([blog](https://www.cyfrin.io/blog))

If you’re more into listening, here’s a list of podcasts worth checking out:

- [Andy Li](https://x.com/andyfeili) | [YouTube](https://www.youtube.com/andyli)
- [JohnnyTime](https://x.com/RealJohnnyTime) | [YouTube](https://www.youtube.com/JohnnyTime)
- [HackenProof](https://x.com/HackenProof) | [YouTube](https://www.youtube.com/@hackenproof)
- [Proof Of Podcast](https://x.com/ProofOf_Podcast) | [YouTube](https://www.youtube.com/@ProofOfPodcast)
- [OpenSense](https://x.com/opensensepw) | [YouTube](https://www.youtube.com/@opensensepw)
- [Cyfrin Audits](https://x.com/CyfrinAudits) | [Spotify](https://open.spotify.com/show/45aUdY9eDwYyE9EZzPaig4)
- [Blockchain Security Series](https://x.com/SecuritySeries) | [Podcasts](https://linktr.ee/blockchainss)
- [The Bytecode](https://x.com/the_bytecode) | [YouTube](https://www.youtube.com/@shafu0x)
- [deliriusz](https://x.com/deliriusz_eth) | [YouTube](https://www.youtube.com/@deliriusz)

## CTFs

Honestly, there’s not too much to say here. Some people absolutely love CTFs, I felt, especially those coming from Web2 security. Personally, I’m not a huge CTF guy, but I did go through [Ethernaut](https://ethernaut.openzeppelin.com/) and [Damn Vulnerable DeFi](https://www.damnvulnerabledefi.xyz/) when I was starting, and it was pretty fun. So if you’re into challenges, give them a try. They’re a great way to get hands-on experience. But the most important part comes in the next chapter.

## Contests and Bug Bounties

Woah, we've made it to the most important part. Here’s where things get real. Up until now, all you needed was a solid grasp of the basics. But this is where deep learning starts.

There’s [Solodit](https://solodit.cyfrin.io/), a fantastic resource filled with millions of bug reports. It’s a great way to learn, but the best strategy isn’t just reading bug descriptions without context (especially for high or critical ones).

Here’s an ideal approach: take a scope from one of the contest platforms (I’ll list them below), try your own audit, and then review all the findings you missed. Understand them, and repeat. This is the phase for truly in-depth learning. For example, if you’re working on a liquid staking or governance project, dive into every article you can find to understand those systems inside and out—that’s how you’ll grow as a security researcher.

Here are the top contest platforms:

- [Code4rena](https://code4rena.com/)
- [Cantina](https://cantina.xyz/welcome)
- [Codehawks](https://codehawks.cyfrin.io/)
- [Sherlock](https://audits.sherlock.xyz/contests)
- [Hats finance](https://app.hats.finance/audit-competitions)

There are also bug bounty platforms where you can hunt for bugs in live contracts, like [Immunefi](https://immunefi.com/) and [Remedy](https://hunt.r.xyz/). By the way, I’ve collected 2023-2024 Immunefi critical [bug fixes](https://github.com/tpiliposian/Immunefi-bugfixes), which could be super useful learning material, too!

## Continuous Learning

## Closing Remarks

## Traditional Roadmaps

1. [OffcierCia/DeFi-Developer-Road-Map](https://github.com/OffcierCia/DeFi-Developer-Road-Map)
2. [razzorsec/AuditorsRoadmap](https://github.com/razzorsec/AuditorsRoadmap)
3. [Anugrahsr/Awesome-web3-Security](https://github.com/Anugrahsr/Awesome-web3-Security)
4. [saeidshirazi/Awesome-Smart-Contract-Security](https://github.com/saeidshirazi/Awesome-Smart-Contract-Security)
5. [Quillhash/QuillAudit_Auditor_Roadmap](https://github.com/Quillhash/QuillAudit_Auditor_Roadmap)

