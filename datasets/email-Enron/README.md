Enron network, part of the Koblenz Network Collection
===========================================================================

This directory contains the TSV and related files of the enron network: The 
The Enron email network consists of 1,148,072 emails sent between employees of Enron between 1999 and 2003. Nodes in the network are individual employees and edges are individual emails.  Edges are directed and weighted. The direction is from the sender to the receiver and the weight represents the number of messages. It is possible to send an email to oneself, and thus this network contains loops. 

The edges files contains three columns: senderID, receiverID, and weight.

Sources:

* http://konect.cc/networks/enron/
* http://www.cs.cmu.edu/~enron/
* Jérôme Kunegis. KONECT – The Koblenz Network Collection. In Proc. Int. Conf. on World Wide Web Companion, pages 1343–1350, 2013. doi:10.1145/2487788.2488173
* B. Klimmt, Y. Yang. Introducing the Enron corpus. In Proc. Eur. Conf. on Mach. Learn., pages 217–226, 2004.


@inproceedings{konect,
	title = {{KONECT} -- {The} {Koblenz} {Network} {Collection}},
	author = {Jérôme Kunegis},
	year = {2013},
	booktitle = {Proc. Int. Conf. on World Wide Web Companion},
	pages = {1343--1350},
	url = {http://dl.acm.org/citation.cfm?id=2488173},
	url_presentation = {https://www.slideshare.net/kunegis/presentationwow},
	url_web = {http://konect.cc/},
	url_citations = {https://scholar.google.com/scholar?cites=7174338004474749050},
}


