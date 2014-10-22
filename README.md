Run schleuder on a pi
=====================

This is only an Idea. yet ...

The problem:
I want to run a schleuder list.
But I don't want the keys to be on a 
keyserver.

Solution:
Use a pi sitting on your home network to decrypt and
encrypt all the mails. The keys never leave the pi.

How:
Create a usual email-account. 
Let fetchmail on the pi poll for new mails.
Pass the new mails to schleuder.
Send the newly encrypted mails out again.

You now have a totally fine working schleuder.
Even if you just use an freemail address and the
provider doesn't even have to offer schleuder.

FAQ
====

Q: What is schluder
A: See https://schleuder2.nadir.org/

Q: How do I configure selfschleuder.
A: A webinterface would be nice. 

Q: Does it use webschleuder
A: Not at the moment
