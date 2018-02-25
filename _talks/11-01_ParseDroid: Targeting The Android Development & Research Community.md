---
layout: talk
title: "ParseDroid: Targeting The Android Development & Research Community"
details: true
track: 1
accepted: true
length: 25
timeslot:
  start: 2018-04-09 15:25:00
  end: 2018-04-09 15:50:00
speakers: 
  - name: "Alon Boxiner"
    photo: /img/speakers/nemo.png
    bio: "Alon Boxiner is an Israeli Security Expert at Check Point Security Technologies, Has over 4 years of experience from the Israeli National Cyber Defense unit. His recent researches has revealed vulnerabilities within popular services (ApkTool, Android Studio, Eclipse, LinkedIn)."
  - name: "Eran Vaknin"
    photo: /img/speakers/nemo.png
    bio: "Eran Vaknin is an Israeli Security Expert at Check Point Security Technologies, Has over 6 years of experience in cybersecurity research, His recent researchers has revealed vulnerabilities within popular services (ApkTool, Android Studio, LinkedIn, WhatsApp), Owner of 'Vproxy' mobile security tool."
recording_uri: 
slides_uri: 
---

APKTool is one of the most popular tools for reverse engineering third party, closed, binary Android applications. This tool is being vastly used by security researchers and analysts and as part of an automated analysis frameworks and online decompilers.

Given these facts, we aimed our research to the products that we use on a daily basis and successfully found some critical vulnerabilities within “APKTool”. We found that “APKTool” is vulnerable to an injection of arbitrary files anywhere in the victim’s filesystem, potentially leading to a remote code execution in both online decompiling services and offline users. 
Therefore, by attacking this infrastructure, we succeeded in hitting and influencing so many famous products, and it is impossible to estimate the amount of products used and built upon this tool.


Additionally, we have found that some of the most popular JAVA IDEs (such as Android Studio, Eclipse or IntelliJ IDEA) are vulnerable to some attack vectors as well.


The combination of all of the vulnerabilities discovered creates a new attack surface against Android developers and security researchers. 
 
In this talk, we intend to introduce the audience to the research we have carried out and show how it was used to exploit APKTool, Android Studio and online decompilers.