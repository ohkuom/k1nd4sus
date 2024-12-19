---
layout: post
title: "Failing and passing CRTO"
date:   2024-11-30 16:00:00 +0100
categories: [Certifications]
author: kuom
---
# tl;dr
Red Team Ops is a red team course from Zero-Point Security that teaches how to perform a Red Team engagement, how to use Cobalt Strike and how to perform various Windows attacks. <br>
The CRTO (Certified Red Team Operator) is the certification that comes with it. <br>
It's really good.

![](/assets/crto.png)
# Course material
The Red Team Ops material is gold. It's one of the cheapest course out there (£365.00) and the content is worth every penny.<br>
It's very specific to Active Directory and Cobalt Strike so I wouldn't reccomend it to anyone who wants a generic introduction into penetration testing.
At times the course material might be a bit dry, but Rasta Mouse (the author) provides external references that you could use to broaden your knowledge.
## Discord
The Zero-Point Security Discord is a mine of knowledege and I've found myself referencing it more than the course material itself. <br> 
Rasta is very active on the channel so he answers a lot of the questions directly. If you experience any issue, search for a few keywords and you will probably find the answer.
## Laboratory
The Lab is a guided Red Team assessment, starting with performing the attacks without Defender enable and then redoing the assessment with it enabled.
A bit different from box-like labs where you have machines or environment to pwn on your own. <br>
I think this is because it's more of a research-oriented lab, where you have the opportunity to test evasion techniques and tools crafting with more freedom. 
# Failing
The primary reason I failed this exam is that I understimated how important the evasion part was. <br>
I managed to achieve 4 flags (6 are required to pass the exam) and then my beacon started to crash. It was of course due to Defender detecting me, but I couldn't figure out what in particular. <br>
Everything you need to know is in the course material, that's a fact, but you need to be careful on the attacks you choose and the way you implement them. This course is really good at guiding you into building an OPSEC mindset, and even if you have to bypass just Windows Defender, the same concepts and techniques also apply to other AV/EDR solutions. <br><br>
Since the exam is an Active Directory environment similar to the lab, I carefully checked my artifact/resource kits and my malleable C2 profile again with Defender enabled and tried various tools to be sure they worked as intended even in a monitored environment.<br>
**Use your notes.** I know there are cheatsheets online but it's way easier to find the correct command in your own notes that you created during testing stuff on the labs. Copying and pasting from the course material won't help you if you don't know what you are doing.

# Passing
After months delving deeper into evasions, which has become one of my favourite topics, I decided to try the exam again. <br>
I started my exam attempt straight after work, at 19:00. With the notes of previous exam attempt, I managed to get the first 4 flags in the first 2 hours. The 5th one was a tough one for me, I spent all the night on it without making any progress.<br> I slept 4 hours or so (**don't be like me, rest!**) and started again at 14:00. Around 17:00 I managed to get the 5th flag and immediately after the 6th. Passed it! Yay! <br>
I was too excited (and tired, I can't lie) that I didn't even tried to get the other 2. Yeah, I'm lazy.

# Next
I signed for the Red Team Ops II course, the natural continuation of this course, given the fact I want to focus on crafting my own evasive payloads and know more about Windows Internals.<br>
I will write another blog post as soon as I will pass it.