---
layout: post
title: Blockchain Document Protection
date: June 19, 2018
--- 



![](../images/encrypt.jpg)



**<u>You Can Protect Against Document and IP Theft with Blockchain</u>**



Intellectual property theft is widespread and costs companies billions of dollars in damages.
Unauthorized music, movie and document sharing are very common and have become
much easier because of all the new cloud services such as drop box, google docs, bit torrent and
cloud based storage.  We hear a lot about services such as artbit and artsmesh protecting
the music industry using blockchain.  They are well known, but less talked about are the ways
to protect documents and spreadsheets with blockchain technology.  

This article will talk about protecting documents by cryptographically hashing them. This is a 
step beyond the typical watermarks found on PDF documents.  The new watermarks will have
a blockchain ID, a timestamp, a token ID and the reader software will check the token for
validity before you can open/decrypt the document. 

**<u>Key points of the DRM system:</u>**

-A digital certificate is produced to confirm ownership and rights. This digital certification is stored in the
  document watermark, the blockchain and the document registry/database.  Application vendors can supply this technology (hopefully they are listening to me).

-The ledger also known as the blockchain has a record of ownership and stores the certificate in an immutable fashion so it there is no way to corrupt the information.  Ownership information or purchaser information always remains intact.

-Finalizing a version of the document can push the identifying data into the registry/database
  and create the watermark. 

-The registry database will also record usage logs.

-The watermarks are machine readable and usages will be recorded in the registry database.

-The token Id in the watermark that allows access can also be revoked at any time. Opening applications will check the registry DB each time the document is opened for validity. It must pass the validity check before it is decrypted.  The token ID is like a digital fingerprint that must be authenticated.

-Rules can be setup that create workflows before the content is displayed, perhaps workflows like purchase now. 

-An application will allow token revocation by updating the registry database that can contains the document ACL’s. If new people are to access the document they will have to register for it. All this gets written in new blocks.

**<u>How Does This Apply?</u>**

Let’s say you work at ACME corporation and you have a very sensitive contact list for disaster recovery
purposes.  The document contains the contact info for all your executives and the contact info
for your offsite storage facility (hopefully not passwords).  This type of document will probably be passed around maybe to fulfill your DR efforts but perhaps it will also be passed around as an executive contact list.  It would not be uncommon to find people storing this document on One Drive, Slack, SharePoint and a Wiki system. Older outdated versions of the document might even exist that will hurt your DR process because it provides instructions that are no longer valid.   From your intranet, a vendor
might leak it to other vendors for sales purposes.  Once leaked bad actors could use if for social engineering hacks/theft. 

As a security professional, you might notice all the improper use of the document and want to act to fix various scenarios.  Here are some scenarios and actions that can be taken.

<u>Use Case One:</u>  First let’s say you wanted to remove the outdated document because it could harm DR efforts.  In this case, you would simply revoke the token from everyone and they could no longer open it or decrypt it…forcing them to download the newer document.

<u>Use Case Two:</u> In this situation, you feel the document is still valid for some people to have but you
notice it is now on public drop boxes and usage logs show it is being access outside your organization.
Usage logs show Sunny Sunil as the last owner of the publicly distributed document. In this case you could simply pull the allow ACL for Sunny Sunil and his version of the document will now be locked and can’t be decrypted.  When Sunny Sunil cries foul you could educate him on security issues.
                    	
<u>Use Case Three:</u>  The DR contact list was decrypted, and is now on a mega download site in screenshot form.  You hear about this but don’t know which mega download site it is on and what other public sites are now posting it. You need to send out some take down notices to some webmasters ASAP but what webmasters?  Your saving grace is that watermark. You simply offer a bounty that is paid in crypto currency to anyone who reports the illegal use of the document and who the pirate is.  To make sure the finder’s fee is paid to legitimate people you use a platform that has ratings for the people reporting violations.

<u>Use Case Four:</u>  You heard the document got out but that is the only detail you have but your
CTO says scour the internet because it had a password and we just got hacked.  Can you realistically scan the internet with your companies compute power, probably not.  However, you can participate in a SETI Network where large groups of people donate excess compute power to search for piracy.  The SETI members can be rewarded in crypto currency for donation compute time, with the power of the SETI network you can scan the web and the dark web.



If you want more details of how this system could work please contact the Blockchain Boy. I am looking at combining this with the
InterPlanetray File System (yes that is a real thing). This article has a copyright held by the Blockchain Boy.  Please do not reproduce or leverage without written permission.




