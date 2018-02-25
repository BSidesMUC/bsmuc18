---
layout: talk
title: "Formal Methods to the Rescue? Experiences Coding in a Theorem Prover."
details: true
track: 1
accepted: true
length: 25
timeslot:
  start: 2018-04-09 10:35:00
  end: 2018-04-09 11:00:00
speakers: 
  - name: "Dr. Cornelius Diekmann"
    photo: /img/speakers/diekmann.jpg
    bio: "Cornelius did a PhD using formal methods to enhance security. He taught network security at TUM."
recording_uri: 
slides_uri: 
---

It took me over 3 years to code ~5k LoC. Not very impressive. However, that code is is correct! According to an independent self-conducted study (pun intended), it is also the best open-source iptables analyzer out there. The value is not the 5k LoC, but rather 5 Lines of Theorem which show that the 5k LoC are correct.

In this talk, I don’t want to walk you over the 5k lines of machine-generated Haskell code. Nor do I want to show you the 50k lines of formalization needed. I just want to show you the 5 Lines of the Theorem. Is this enough to convince you about the correctness of the iptables analyzer?

Neighbors, feel free to question anybody who does formalism for the sake of pretending to be a scientist. Formalism has a clear value: It is more expressive than our programming languages. And it is a nice language to precisely state the high-level requirements of our software. And here lies the true value: Computers understand rigorous formalism, too. Computers can check proofs, so you don’t have to. Just inspect 5 Lines of Theorem to get confidence in the correctness of 5k LoC. This approach seems to scale.*

*) given an infinite supply of PhD students who do the proofs for you.