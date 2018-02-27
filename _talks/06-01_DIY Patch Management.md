---
layout: talk
title: "DIY Patch Management"
details: true
track: 1
accepted: true
length: 45
timeslot:
  start: 2018-04-09 11:25:00
  end: 2018-04-09 12:10:00
speakers: 
  - name: Florian Junge
    photo: /img/speakers/fjunge.jpg
    bio: "Coming from an academic background in security, both, Ingo Bente and Florian Junge, not only implemented security solutions in several big and small companies but also did some research in this field. Topics include trusted networks, DTLS security of IOT devices and enhancement of various security technologies such as SIEM and Android."
  - name: Ingo Bente
    photo: /img/speakers/ibente.jpg
    bio: "Today, Ingo Bente and Florian Junge take care of the security at SinnerSchrader as director information security and senior security engineer, respectively. Here, they support their colleagues who develop applications for major enterprise customers. Because of the agile methodology used in most projects, both concentrate on a hands-on approach and personal contact and do not rely on heavy weight,silver bullet promising applications and processes. They describe their security understanding as full stack - from people to products."
recording_uri: 
slides_uri: 
---

Installing software patches is a no brainer when it comes to security. 
Over the past years, several stories about major flaws have been covered in the media. 
Those who follow the coverage understand that being up to date with the latest MacOS or Windows patches has become a necessity. 
For consumer computer it is easily done: click a button, sometimes reboot, and you are good to go.

Yet, when it comes to larger IT infrastructures, promptly patching seems to be a hard problem. Otherwise, recent ransomware attacks that exploit vulnerabilities months after a patch was made available would not have such a great impact that makes everybody go into panic mode.

In this talk, we will tell the story of how we managed to fix our own patch management procedures. 
What used to be a manual, checklist based and thus inconsistent approach in a heterogenous environment, has now become largely automated.
Daily, host-based scans search for software packages with known vulnerabilities.
Results are logged to a central ELK stack. 
Dashboards provide insights for management. 
The actual patching is done by leveraging unattended-upgrades with some custom code. 
The result: an IT-infrastructure that keeps itself up-to-date. 
Bonus: no money was spent on commercial software.