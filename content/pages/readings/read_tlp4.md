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
title: Encryption and National Security
uid: 3ac0a6e4-b1a5-2e70-da72-d42dad9a4c86
---

*   Required Readings for this Topic:
*   {{% resource_link 296da733-fbe4-0232-14bf-e7c4a490acc1 "The Encryption Controversy, 1994-1997" %}}
    *   {{% resource_link 1969ffb5-c1cf-c678-21f5-e510e32c3852 "1994: The Digital Telephony Act (CALEA)" %}}
    *   {{% resource_link 2eb119a8-6ab9-4df2-aa3e-11ab30e1ad94 "1994: Clipper (The Escrowed Encryption Standard)" %}}
    *   {{% resource_link 1200bae3-6dfa-b89e-79da-307caa7932b4 "1995-97: From Clipper to Key Recovery" %}}
*   [Constitutional Issues](#const_issues)
    *   [Legal Challenges to Encryption Export Regulations](#legal)
    *   [Constitutionality of Domestic Controls on Encryption](#domestic)
*   [Cryptoanarchy](#crypto)
*   [Technical background on Cryptography](#technical)
*   [More Information](#more)

{{< resource uuid="4796b100-6505-fb27-32eb-f52739e5e69b" href_uuid="4796b100-6505-fb27-32eb-f52739e5e69b" >}}

Transmittal Letter. (Courtesy of the [Electronic Privacy Information Center](http://www.epic.org/).)

Transmittal letter from FBI Director William S. Sessions to National Security Council official George J. Tenet, February 1993, forwarding a report prepared by FBI, NSA and DOJ and titled "Encryption: The Threat, Applications, and Potential Solutions". The report was classified SECRET and called for a national policy prohibiting cryptography that does not ensure real-time access to law enforcement. U.S. administrations continue to insist that they do not support domestic restrictions on encryption technology. The redacted document shown here was obtained in 1996 under the Freedom of Information Act by the Electronic Privacy Information Center.

We are at one of those important cusp points in history. The technologies of networks and of encryption make it very easy for exciting new structures to develop (cryptoanarchy, privacy, transnational entities, persistent organizations, anonymous systems, digital banks). But the same technologies make it possible for a cyberspatial police state to develop. The race is on.  
\-- Tim May, "The Coming Police State," (March 1994)

There is a very real and critical danger that unrestrained public discussion of cryptologic matters will seriously damage the ability of this government to conduct signals intelligence and the ability of this government to carry out its mission of protecting national security information from hostile exploitation.  
\-- Admiral Bobby Ray Inman (then Director of the NSA, 1979)

Cryptography is like literacy in the Dark Ages. Infinitely potent, for good and ill... yet basically an intellectual construct, an idea, which by its nature will resist efforts to restrict it to bureaucrats and others who deem only themselves worthy of such Privilege."  
\--Vin McLellan, A thinking man's creed for crypto

Unless the issue of encryption is resolved soon, criminal conversations over the telephone and other communications devices will become indecipherable by law enforcement. This, as much as any issue, jeopardizes the public safety and national security of this country. Drug cartels, terrorists, and kidnappers will use telephones and other communications media with impunity knowing that their conversations are immune from our most valued investigative technique.  
\--FBI Director Louis Freeh, Testimony before the House Judiciary Committee, March 30, 1995

Encryption technology, once the province only of affluent countries, had, with the advent of personal computers, become readily available to the humblest citizen in America and other technically advanced countries, and an unexpected spin-off of that fact was the current availability of highly advanced communications-security apparatus to the humblest nations. Now Malaysia had codes nearly as hard to break as Russia 's -- and so did Iraq, courtesy of Americans who worried about having the FBI read their fictitious e-mail adulteries.  
\-- Tom Clancy, Executive Orders, 1996

We propose to permit the export of 56-bit key length Data Encryption Standard (DES) encryption products, without key recovery, on the same terms as we now permit the export of 40-bit key length products. This relaxation would last two years, renewable annually thereafter. Export licenses would be contingent on exporters' commitment and adherence to explicit benchmarks and milestones for developing and incorporating key recovery into their products (including an identified trusted part) and building the supporting infrastructure internationally. Once key recovery is globally viable, only such products would be licensed for export.  
\-- Memo from CIA Director John Deutch to President Clinton, September 15, 1996, describing the Administration's plan for "liberalizing" export restrictions on encryption technology.

There is one comforting conclusion which is easy for a real mathematician. Real mathematics has no effects on war. No one has yet discovered any warlike purpose to be served by the theory of numbers or relativity, and it seems very unlikely that anyone will do so for many years.  
\-- G. H. Hardy A Mathematician's Apology, 1940

{{< anchor "required" >}}{{< /anchor >}}Required Readings
---------------------------------------------------------

Read all the text on this page and on the subsidiary pages in the section [The encryption controversy, 1994-1997](#contro) (This does not include following all the links.) In addition, read:

*   Barlow, Jackboots on the Infobahn
*   Overview and summary recommendations of the NRC Report, Cryptography's Role in Securing the Information Society
*   A few of the articles from 1997 on the crypto debate.
*   Greg Rawlins, Too many secrets

Note: The links in the list above connect to the place on the page where each item is described, so that you can see it in context. Follow the link from there to the actual reading.

{{< anchor "encryption" >}}{{< /anchor >}}{{< anchor "contro" >}}{{< /anchor >}}The Encryption Controversy, 1994-1997
---------------------------------------------------------------------------------------------------------------------

This is an extensive topic, which is addressed on a {{% resource_link 296da733-fbe4-0232-14bf-e7c4a490acc1 "page of its own" %}}, with three sub-pages.

{{< anchor "const_issues" >}}{{< /anchor >}}Constitutional Issues
-----------------------------------------------------------------

The regulations on encryption can be viewed as constraints on Freedom of Speech, and the Constitutionality of such regulations is not clear, either for export restrictions or domestic controls. There are legal challenges to the export restrictions currently underway, and there would certainly be immediate challenges if domestic controls were to be implemented. Due to the national security aspects of encryption, the Constitutional issues have not been pressed until recently. For good historical context, see:

Foerstel, Herbert N. _Secret Science: Federal Control of American Science and Technology_. This is a history of U.S. Government control of scientific information. Chapters 4 (cryptography) and 5 (sensitive, but not classified information) are especially relevant, but the entire book is good reading and gives a valuable historical perspective.

### {{< anchor "legal" >}}{{< /anchor >}}Legal Challenges to Encryption Export Regulations

There are currently three legal challenges to the encryption export regulations beofre the courts. The first two are bogged down in procedural matters:

*   Karn v. U.S. Department of State \[Discussion to be added.\] See Karn's archive on the case. There is also an archive of legal documents maintained by the Electronic Frontier Foundation.
*   Junger v. Daley \[Discussion to be added.\] Look here for information.

The third case has evolved into a major challenge to the export regulations:

Bernstein v. U.S. Dept. of State, et. al.

On February 21, 1995, the Electronic Frontier Foundation filed suit against the government on behalf of Prof. Dan Bernstein of the University of Illinois. The basis for the suit was the State Department's denial of Bernstein's request for permission to publish a paper on an cryptographic algorithm he invented when he was a graduate student at Berkeley. The suit claims that this is an unconstitutional restriction of speech in that algorithms and source code are protected expression under the First Amendment.

In December 1996 the U.S. District Judge Marilyn Patel ruled in favor of Bernstein, in effect striking down the State Department export regulations. The decision was somewhat moot, however, because a few weeks later the government transferred regulation of crypto export controls from the Department of State to the Department of Commerce. EFF renewed the suit against Commerce, arguing that the jurisdictional transfer did not change the underlying issues.  
In August 1997, Judge Patel once again ruled in favor of Bernstein:  
"The court declares that the Export Administration Regulations . . . insofar as they apply to or require licensing for encryption and decryption software and related devices and technology, are in violation of the First Amendment on the grounds of prior restraint and are, therefore, unconstitutional as discussed above, and shall not be applied to plaintiff's publishing of such items, including scientific papers, algorithms or computer programs."  
Although this decision technically strikes down the export control laws, the government filed an emergency request, and Patel agreed to stay her order until the Appeals Court could rule on her decision. The case was heard by the 9th Circuit Court of Appeals in San Francisco in December, 1997. In May 1999, the Court ruled 2-1, upholding Judge Patel's decision. In June 1999, the Government petitioned for a rehearing, and that petition is still being considered (as of August 1999).  
Complete documentation on the case can be found at Bernstein's Web site for the case.

### {{< anchor "domestic" >}}{{< /anchor >}}Constitutionality of Domestic Controls on Encryption

Several countries, including France, Israel, and Russia, impose control on the domestic use of encryption by their citizens. Would such controls be Constitutional in the U.S.? The answer is apparently not clear. Here are some resources on this question:

*   Froomkin, A. Michael. "The Metaphor is the Key: Cryptography, the Clipper Chip, and the Constitution." _Univ Penn Law Rev_ 709, 1995. This is a monumental (175 pages) analysis of the constitutional issues surrounding cryptography. The heart of the monograph is a discussion of whether mandatory key escrow would be constitutional. Froomkin emphasizes that the degree of constitutional protection accorded to encrypted communications will hinge on the metaphors that the courts adopt for viewing them: whether they are like languages, vaults, houses, or "cars on the information highway." There are also excellent overviews of modern cryptography and the Clipper proposal. Even though this is a long piece, it is well worth having a look at, both for its insightful and provocative legal analysis and because it collects in one place most of issues in the Clipper debate (through the end of 1994).
*   In March 1996, the Sixth Conference on Computers, Freedom and Privacy, held at MIT, conducted a moot Supreme Court hearing on the question of whether prohibiting domestic use of unescrowed encryption would be Constitutional. The material prepared for the session includes briefs and memoranda on both sides of the issue, together with oral arguments conducted before a panel of Federal judges (and available on the Web in RealAudio format). Even though this was a pretend trial, not a real one, the lawyers (and the judges) are real, and this is a thorough exploration of the legal arguments, as well as a good preview of what could happen if domestic controls were enacted.

{{< anchor "crypto" >}}{{< /anchor >}}{{< anchor "technical" >}}{{< /anchor >}}{{< anchor "more" >}}{{< /anchor >}}Cryptoanarchy
--------------------------------------------------------------------------------------------------------------------------------

It's not only the FBI that views the spread of strong cryptography as a threat to government authority. Since around 1992, an informal group of techno-libertarians, who have become known as the Cypherpunks, have been theorizing about how the ability to keep communications private can lead to cryptoanarchy. Given their libertarian bent, they tend to view this as a healthy counter to the increased power of government and the growth of the surveillance state.  
For several years, this discussion was carried out on the Cypherpunks mailing list, which served as a major forum for discussion of cryptography and privacy. The list still exits, but it has degenerated over the past year due to a deluge of spam (and the resulting flames about whether cypherpunks ought to restrict spam).  
In 1994, Tim May, one of the founders of the list and a major contributor, published a large compendium of cypherpunk material called the Cyphernomicon. Also, before looking at the whole thing, you should read the following pieces by May:

*   May, Timothy C. "The Crypto Anarchist Manifesto."
*   ———. "The Coming Police State." March 9, 1994.
*   ———. "Cyberspace, Crypto Anarchy, and Pushing Limits." April 3, 1994.
*   ———. "Crypto Anarchy and Virtual Communities." December 1994.

Here are some other pieces on cypherpunks and cryptoanarchy.

*   Christopher Anvil, "Gadget vs. Trend." This isn't about encryption at all. Rather, it is a whimsical science fiction story originally published in Analog in 1962, which was prophetic of some of the "cryptoanarchy" issues that are coming to the front with the emergence of secure encryption. Ironically, Anvil's predicted date for the release of the imaginary "Quiet Wall" invention (1976) coincided with the invention of public-key cryptography. (Copies will be distributed in class.)
*   Zimmermann, Phil. "Why Do You Need PGP?." _PGP User's Guide_ 1.  
    This is the introduction to volume 1 of the PGP User's Guide, describing the need for private communications. Although not a cryptoanarchist, Phil Zimmermann became one of the first and most famous cryto-activists, through his publication of Pretty Good Privacy (PGP), whose creation was sparked in 1991 by an early predecessor of the Clipper initiative.
*   Introduction to Blacknet. This was a hoax perpetrated by Tim May in 1993. (But the truly paranoid on the Net are of course not convinced, and at least one FBI agent was asking about it at MIT.) As an amusing aside, the Blacknet public key was broken in June, 1995 as a demonstration of modern factoring techniques.
*   Wade, Nicolas. "Method and Madness: Little Brother." The _New York Times Magazine_, September 4, 1994. This is a thoughtful piece on the tradeoffs between security and privacy, and the implications of "democratization of high technology."
*   Slater, Dashka. "Secret Agents." _Express_ \[Bay Area Weekly\], March 14, 1997. This piece provides a history of the cypherpunks and a snapshot (as of March 97) of the cryptography debate from the cypherpunks' point of view.
*   McHugh, Josh. "Politics for the really cool." _Forbes Magazine_, September 8, 1997. This article emphasizes the implications of strong cryptography for tax collection and financial transactions. What else would you expect from Forbes?

Technical Background on Cryptography
------------------------------------

We won't deal much with the technical aspects of cryptography -- there are other MIT subjects that cover this. But if you're curious, there are lots of good sources of information.

*   RSA's Frequently Asked Questions About Today's Cryptography, is maintained by RSA Data Security, Inc., and is an excellent introduction to some of the issues.
*   [The Cryptography FAQ](http://www.faqs.org/faqs/cryptography-faq/). This is another comprehensive information source.
*   Bruce Schneier, _Applied Cryptography_. John Wiley & Sons, 2nd rev. ed., 1995. This is an outstanding book on the basics of modern cryptography and its applications.
*   The Venona Project. This is a fascinating site to look at if you are interested in cryptography. Venona was the code name for the U.S. Signals Intelligence effort begun in 1943 to collect and decrypt the text of Soviet KGB and GRU messages, messages that provided extraordinary insight into Soviet attempts to infiltrate the U.S. Government. The NSA has declassified thousands of these documents and made them available at their Web site, together with information about their decryption.

More information
----------------

[WWW Cryptography Article Database](http://www.schneier.com/cryptography.html)