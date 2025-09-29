---
content_type: page
description: ''
hide_download: true
hide_download_original: null
learning_resource_types:
- Readings
ocw_type: CourseSection
parent_title: Readings
parent_type: CourseSection
parent_uid: c807d991-0c36-a7b6-1022-b5e758877384
title: '1995-97: From Clipper to Key Recovery'
uid: 1200bae3-6dfa-b89e-79da-307caa7932b4
---

*   {{% resource_link 296da733-fbe4-0232-14bf-e7c4a490acc1 "Back to the Encryption Controversy: 1994-1997" %}}
*   {{% resource_link 3ac0a6e4-b1a5-2e70-da72-d42dad9a4c86 "Back to readings on Encryption and National Security" %}}

By mid-1994, Clipper was dead as a serious proposal, although the debate continued to seethe -- and the pressure from industry to address the awkward export regulations mounted. The need to do something was brought home in August 1995 when David Byers in Sweden and Eric Young in the UK, and (independently) Damien Doligez in France demonstrated that they could break the 40-bit RC4 encryption algorithm used in Netscape's SSL (the only encryption algorithm generally approved for export from the U.S., and claimed by the Administration to be adequate for commercial applications) using clusters of workstations running for 8 days. (This feat was duplicated in January 1996 at MIT by Andrew Twyman, using a single graphics workstation.)

Fall 1995: Clipper II
---------------------

In September and December 1995, the Administration sponsored public meetings under the auspices of the National Institute of Standards and Technology (NIST), aimed at raising support for a new approach to the cryptography dilemma. The basic principle was that the U.S. would permit export of products using stronger algorithms -- up to 56-bit DES -- provided these included spare keys that would be deposited with authorized "escrow agents" who would respond to government requests. Additional criteria included that products must be designed so that the escrow mechanism cannot be circumvented, and that escrowed encryption products cannot interoperate with non-escrowed encryption products.

This approach was seen as an improvement over Clipper, but industry support was generally cold. The proposed 56-bit DES limit was still considered inadequate, and the various criteria were criticized as unclear and difficult to implement, and with inadequate safeguards against abuse. The initiative was opposed as a "Clipper II" and (because of the non-interoperability criterion) an attempt to impose key escrow on domestic use of encryption. Here are links to further details:

*   Markoff, John. "U.S. to Urge A New Policy On Software." _New York Times_, August 18, 1995.
*   Diffie, Whitfield. "Washington's Computer Insecurity." _New York Times op-ed piece_, August 19, 1995.
*   Lewis, Peter H. "Privacy for computers? Clinton sets the stage for a debate on data encryption." _New York Times_, September 11, 1995,
*   Corcoran, Elizabeth. "Feuding again erupts over encryption exports." _Washington Post_, September 16, 1995.

May 1996: The NRC Report
------------------------

In 1994, at the height of the original Clipper controversy, the National Research Council began a study of U.S. cryptography policy. This was finally published in May, 1996, as _Cryptography's Role in Securing the Information Society_. Even though a year has since gone by in this rapidly changing area, the 700-page NRC report is the still the single best and most comprehensive source for information about cryptography policy and its implications.

The report contained several major recommendations, including:

*   No law should bar the manufacture, sale, or use of any form of encryption within the United States.
*   Export controls on cryptography should be progressively relaxed but not eliminated.
*   National cryptography policy should be developed by the executive and legislative branches on the basis of open public discussion and governed by the rule of law.

The third recommendation seems the most general, but it is perhaps the most important one. Most members of the NRC panel had been given security clearances and had received classified briefings from the law-enforcement and intelligence communities. The panel concluded that although the classified information contained important details, these did not make a difference in the overall policy debate, which should therefore be conducted in public fora rather than in closed hearings.

The panel also recommended that the U.S. government begin to experiment with escrowed encryption in order to gain experience with it. But it criticized efforts to promote rapid, widescale deployment of key escrow systems, saying that the technical issues and potential risks were not sufficiently understood. Largely as a result of this criticism, the Administration quickly distanced itself form the report.

*   National Research Council Committee. "Cryptography's Role in Securing the Information Society." May 30, 1996. Prepublication Copy. (Overview of the report and summary recommendations.)

May 1996: Key-management Infrastructures ("Clipper III")
--------------------------------------------------------

McConnell, Bruce, and Edward Appel. "Enabling Privacy, Commerce, Security and Public Safety in the Global Information Infrastructure." May 1996. The Administration introduced a new idea for dealing with control of cryptography, with the publication of the above draft memorandum by Bruce McConnell, and Edward Appel, who co-chaired the White House's Interagency Working Group on Cryptography Policy.

This approach went further than ever before in recognizing that industry must play a major role in any solution to the cryptography problem. Rather than focusing on cryptographic algorithms themselves, the report highlighted the importance of a _key-management infrastructure_(KMI) through which users of cryptography are able to identify the the people they are communicating with. This identification can be accomplished by having keys registered and digitally signed by _certification authorities_ (CAs), which serve as "digital notarys public" to attest to the identity of the person nominally associated with a given key. (There are other possible techniques, such as the "web of trust" used in PGP.)

The Administration paper emphasized the importance of key-management infrastructures and suggested a collaborative effort by government and industry to develop a KMI in which, when keys are registered with a certification authority, they are also escrowed with an associated key escrow agent that would respond to government requests for access to keys. The report suggested that encryption products whose keys are escrowed in this way would be eligible for export. It also called for developing a framework of international agreements about sharing keys and providing access to escrowed information.

The proposal was viewed as significant progress by the Administration in recognizing the importance of expanding the use of encryption. But it was criticized -- and immediately dubbed "Clipper III" by opponents -- on the grounds that it would effectively make key escrow (even for domestic encryption) a precondition for participation in the Global Information Infrastructure by incorporating escrow into the basic framework of identification on the network.

The Electronic Frontier Foundation's [Clipper III Archive](http://w2.eff.org/Privacy/Key_escrow/Clipper_III/) contains several statements critical of the proposal.

Summer 1996: Key Recovery and Inducements for Industry Cooperation
------------------------------------------------------------------

**Note**: By the summer of 1996, "key escrow" had amassed so much criticism that proponents of the idea started using the term "key recovery" to mean essentially the same thing. There have been several attempts to explain the difference, usually by companies that have developed key escrow schemes. The explanation usually boils down to "Key escrow was that old unacceptable idea, but this particular feature of our product includes makes it _recovery_ rather than _escrow_."

Starting in late summer, the Administration began trying to garner industry support for key recovery along the lines laid down in the May KMI paper. In a series of meetings with computer and software companies through the fall, the following policy was hammered out:

1.  The Administration would shift jurisdiction over export of cryptographic hardware and software from the State Department to the Commerce Department. Industry liked this, since it considers the Commerce Department to be more receptive to industry views.
2.  Companies could apply for and receive immediate approval to export encryption products using 56-bit DES, _provided_ they presented a plan to install key recovery in their exported encryption products within two years.
3.  Encryption products of any strength would be eligible for export approval, if they incorporate key recovery.

This policy generally received reluctant cooperation from industry. On the one hand, companies insisted that export regulations place them at a disadvantage with respect to foreign competition, and they were loathe to supporting any plan that would continue to regulate encryption export. On the other hand, the were eager to obtain approval for their 56-bit DES products (even though these are not adequate for high-security applications).

In October, eleven companies -- Apple, Atalla, Digital, Groupe Bull, Hewlett-Packard, IBM, NCR, RSA, Sun, Trusted Information Systems and UPS -- became charter members of the _Key Recovery Alliance_, whose aim is to develop key-recovery techniques to meet the needs of customers and to allow easing of export restrictions. The Alliance emphasized that there are valid commercial reasons for key recovery (such as people gaining access to their data if they lose their keys), but they took pains to make clear that they oppose any attempts by governments to mandate key recovery. Since then, Alliance membership has gr own to 60 companies.

1997: Situation Still Murky
---------------------------

At the very end of December 1996 the Administration, as promised, published new regulations transferring export control of cryptography from the State Department to the Commerce Department's Bureau of Export Administration.

Here are the regulations ({{% resource_link 904fa657-cb85-6702-4bdd-aadb23310b8c "PDF" %}}), as published on December 30, 1996.

Technically, these regulations are an "interim rule", but as of this date (September, 1998), they are still in effect, while the Administration revises them in response to comments. Reception from industry remains grudging: Overall, companies are filing plans to gain export approval for 56-bit DES, while continuing to oppose any export restrictions. Their mantra here is "We oppose government regulation of encryption, but we will provide key-recovery products in response to customer demand".

1997 was also the year in which the crypto dilemma attracted Congress's attention in a big way, with numerous hearings and several bills introduced, with industry and civil liberties groups lobbying for relaxing export controls, while law-enforcement (notably the FBI and the Justice Department) lobbied for tighter controls.

*   One influential document in the debate was [The Risks of Key Recovery, Key Escrow, and Trusted Third-Party Encryption](http://academiccommons.columbia.edu/catalog/ac%3A127127), by a group of cryptographers and computer scientists (Hal Abelson, Ross Anderson, Steven Bellovin, Josh Benaloh, Matt Blaze, Whitfield Diffie, John Gilmore, Peter Neumann, Ronald Rivest, Jeffrey Schiller, and Bruce Schneier) published in May 1997 with the assistance of the Center for Democracy and Technology. The group cautions that key recovery for government access (where keys must be made accessible to law-enforcement on short notice without the knowledge of the user) has inherent risks and expenses that are not well understood, and advises against rapid, wide-scale deployment of such systems.

Congressional legislation in 1997 was all over the map, with bills introduced ranging the elimination of export controls outright, to bills outlawing the sale of non-escrowed encryption products, even domestically. By the end of the legislative session, the encryption debate has become too chaotic to result in any legislation.

*   {{% resource_link c7febcf1-84c0-a209-b4c3-d44c8619abd0 "Selected articles on the Crypto Debate circa 1997" %}}. Note the flare-up after September 3, when FBI Director Louis Freeh proposed regulation of domestic encryption, just as he had announced as his intent ever since the debate over Digital Telephony.
*   "Encryption Bills Considered By Congress in 1997." Summary (with comments) provided by the Electronic Frontier Foundation on 10 October 1997. This is far from an unbiased report, since the EFF is adamantly opposed to any regulations on encryption, but is nevertheless helpful to see all the bills discussed in one place.

Another element of the crypto debate that became critical in 1997 was the reaction of other governments. The Administration's vision of a Key Management Infrastructure requires significant international cooperation on to develop a framework for inter-government access to keys and encrypted information, and the U.S. has been lobbying strongly for other governments to adopt the key recovery approach. The following report which was issued by European Commission appears to throw cold water on the U.S. efforts.  
European Commission. "Towards a European Framework for Digital Signatures and Encryption." October 8, 1997.

See the following article on the European Commission report: Andrew, Edmund L. "Europeans Reject U.S. Plan On Electronic Cryptography -- Threats to Privacy and Commerce Are Cited." _The New York Times_, October 9, 1997.

1998: Going Slow (so far)
-------------------------

So far, 1998 has been a year of slow going. The Secure Public Networks Act (S. 909), passed by the Senate Commerce Committee in July, 1997, would mandate the use of key recovery on networks built using federal funding, and also as a precondition to gaining certificates for electronic commerce. This bill has not yet come before the full Senate.

One interesting development was the [demonstration by the Electronic Frontier Foundation](https://www.cnet.com/news/record-set-in-cracking-56-bit-crypto/) that 56-bit DES could be cracked in 56 hours using a special-purpose machine that can be built at modest cost, thus underlining the inadequacy of 56 bits as a limit on exportable encryption.

Harking back to CALEA and the beginning of this survey -- the U.S. Telephone Association filed suit against the FBI and the Department of Justice on August 19 to block the implementation of CALEA, on the grounds that the implementation cost-recovery regulations and FBI rules exceed the FBI's statutory authority. On September 11, 1998, the FCC helped defuse the tension between the FBI and the telecommunications industry by delaying the date for CALEA compliance (originally scheduled for October 1998) until June 2000.

Overall, though, most action seems to be behind the scenes positioning. Whether anything will emerge before the end of the legislative session remains to be seen.

For an overview of latest events, see the information pages maintained by the [Internet Privacy Coalition](http://www.epic.org/crypto/) and the [Center for Democracy and Technology](http://www.cdt.org/).