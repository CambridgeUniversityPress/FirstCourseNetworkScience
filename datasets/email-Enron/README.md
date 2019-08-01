Enron network
=============

This directory contains the edges file of the Enron email network. 
The network consists of 1,148,072 emails sent between employees of Enron between 1999 and 2003. Nodes in the network are individual employees and edges are individual emails.  Edges are directed and weighted. The direction is from the sender to the receiver and the weight represents the number of messages. It is possible to send an email to oneself, and thus this network contains loops. 

The edges file contains three columns: senderID, receiverID, and weight.

Sources:

* http://konect.cc/networks/enron/
* http://www.cs.cmu.edu/~enron/
* Jérôme Kunegis. KONECT – The Koblenz Network Collection. In Proc. Int. Conf. on World Wide Web Companion, pages 1343–1350, 2013. doi:10.1145/2487788.2488173
* B. Klimmt, Y. Yang. Introducing the Enron corpus. In Proc. Eur. Conf. on Mach. Learn., pages 217–226, 2004.
