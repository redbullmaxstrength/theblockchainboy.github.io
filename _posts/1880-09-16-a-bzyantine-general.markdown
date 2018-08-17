---
layout: post
title: Blockchain & The Byzantine Generals
date: June 19, 2013
--- 



![](../images/general.png)

So the Byzantine army is about to attack the enemy camp.  The byzantine army is distributed in squads all around the enemy camp.  They are distributed like blockchain nodes.  Each squad has a general who makes all the decisions.  If each squad attacks the enemy at the same time (all the generals make the same decision) the Byzantine army will win, however if a few squads fail to attack with the other squads, the Byzantine  army will lose.  From a general  a written request goes out to attack the enemy at midnight. The message is delivered by horseback via a messenger to all the squads.  If all the Generals are loyal to Byzantine they will all attack at midnight and win.  However, if some of the generals are traitors and a few of the squads do not attack at midnight, the
battle will be lost.  How do you prevent the message from being altered by a traitor general. What solution do you build to insure the battle is won?

A good solution is for the first general to create special locked box with two sets of keys, a private and a public key. The public key is given to the messenger and can only be turned clockwise to see what is inside of the box. The messenger will bring the box and the public key to each general via horseback.  The first general owns the private key which can be turned counter-clockwise to alter the information inside of the box. The general takes the lock box, turns the private key counter-clockwise, and puts in a message that says to attack the enemy at midnight. The lock box is then delivered to the next general and he takes his public key, turns it clockwise, and sees that the first general is issuing an attack at midnight. The lock box then gets delivered to the third general. He is an evil traitor and decides to turn the public key counter-clockwise in order to corrupt the attack message. He knows that if he does not attack and gets the next generals in the line not to attack evil wins and he is evil.  However, due to the general’s fancy lock, the public key does not give him permission to do this. The message cannot be corrupted and thus gets delivered to the other generals authentic and uncorrupted. The attack succeeds as enough squads attack to win the war.  As for the traitor general he might choose to attack knowing that if he does not the messenger or other readers of the message will see his guilt.  Even he if does not attack he was still not able to alter the course of the battle because he could not change the message to confuse the other generals.





