---
layout: essay
type: essay
title: Do Smart Questoins Matter
# All dates must be YYYY-MM-DD format!
date: 2018-01-24
labels:
  - StackOverflow
---

<img class="ui small right floated spaced image" src="../images/smart_questions.jpg">

It is often said that no one can truly know everything about a subject. This notion is particularly true with programming, which has a remarkably short knowledge half-life. Programming and software can be implemented in innumerable ways and problems which seem insurmountable can be overcome from a different perspective. Information on the web can offer this different perspective, however getting that perspective is not always easy. Asking questions on forums is the ideal way to solve certain problems and asking smart questions is one of the best ways to receive advice. Having a clear understanding of what differentiates a smart question from a generic question often means the difference between receiving an answer and being left empty-handed. Using StackOverflow as a basis, two questions will be examined and reviewed.

<blockquote cite="https://stackoverflow.com/questions/48270127/can-a-1-a-2-a-3-ever-evaluate-to-true">

Thread Topic: Can (a ==1 && a== 2 && a==3) ever evaluate to true?  

Is it ever possible that (a ==1 && a== 2 && a==3) could evaluate to true in JavaScript?  

This is an interview question asked by a major tech company. It happened 2 weeks back, but I'm still trying to find the answer. I know we never write such code in our day to day job, but I'm curious.  

</blockquote>

The above question displays some aspects of a smart question. The topic of this question clearly defines the question and additionally states the programming language used. This question however is an interview question and is in the gray area when it comes to an appropriate question. The responses to this question however are mostly positive and many different answers to the question were proposed. The question at the time of writing also had over 1900 upvotes.

<blockquote cite="https://stackoverflow.com/questions/48291923/ssh-public-key-authentication-still-asks-for-password"> 

Thread Topic: SSH public key authentication still asks for password

I am using two servers running Debian 8, which I will call server1 and server2. Currently, I am attempting to connect from server1 to server2 using scp and want to do so without a password so that it can run automatically using cron. I have attempted to install the public key file from server1 in server2 using the following commands:

ssh-keygen (blank passkey used)

ssh-copy-id -i key.pub nonrootuser@server2 

The .ssh directory and files on server2 have also had their permissions set using the following commands: 

chmod 700 .ssh

chmod 600 ~/.ssh/known_hosts

chmod 600 ~/.ssh/authorized_keys

chown -R nonrootuser:nonrootuser ~/.ssh

After using running these commands, ssh and scp still request a password. I've also tried manually coping the key.pub file to server2 and adding the contents to the end of the authorized_keys file to no avail. 

Any suggestions on what other things I should try/check for?

</blockquote>

The above question exhibits many hallmarks of a smart question. Thread topic for this question makes it clear what the problem is and what protocol is being used. In the body of the question, the user explained the context of the question in addition to what steps he/she has already undertaken. This question does not however constitute a smart question. The main problem with this question is that it was posted on StackOverflow despite the nature of the question being related to networking and server administration. This was highlighted by the comments of the post which mentioned that the question is not asked on the correct board. There were limited responses to the question, however the commenters were unable to solve the problem.
Looking at these example StackOverflow questions, it becomes clear that even though both questions leveraged smart question aspects, the reception and responses from the community can vary greatly. Should the second question have been asked in an appropriate board, the reception may have been different.
