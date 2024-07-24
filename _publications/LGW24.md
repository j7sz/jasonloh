---
title: "Pairing-Free ID-Based Signatures as Secure as Discrete Logarithm in AGM"
collection: publications
permalink: /publication/LGW24
excerpt: 'This paper is about fixing template issue #693.'
date: 2024-02-17
venue: 'ACISP 2024'
slidesurl: ''
paperurl: ''
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Identity-based signatures (IBS) allow the signer's identity information to be used as the public key for signature verification, eliminating the need for managing certificates to establish ownership of the corresponding public key. The Schnorr-like IBS due to Galindo and Garcia is known as the most efficient IBS based on the discrete logarithm (DL) problem, without the need for computationally expensive pairing operations. This makes it a lightweight and efficient solution for signature generation and verification. Unfortunately, the security reduction of Schnorr-like IBS is not tight under the standard EUF-CMA in the ID-based setting. Recently, by using the algebraic group model (AGM), where adversary computation is algebraic, the EUF-CMA security of ordinary Schnorr signatures has been proven tightly secure under DL assumption with random oracles. However, one could not trivially apply the reduction of Schnorr signatures in AGM to achieve tight security for the Schnorr-like IBS scheme because of the inability to capture the chosen identity-and-message attacks. In this work, we show that, with the adoption of AGM, it is feasible to tighten the EUF-CMA security for IBS without pairing under DL assumption with random oracles. We resolve the chosen identity-and-message attacks by adopting the OR-proof technique to generate the user’s private key containing the DL of either one of the two random group elements, leading to a new pairing-free IBS scheme. We provide a concrete security analysis for the scheme in AGM showing that by embedding the DL problem instance into one of the randomness, the algebraic adversary could only return a non-reducible forgery and representations with half of the success probability.
