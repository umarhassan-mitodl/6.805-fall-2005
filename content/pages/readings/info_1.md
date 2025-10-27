---
content_type: page
description: ''
learning_resource_types:
- Readings
ocw_type: CourseSection
parent_title: Readings
parent_type: CourseSection
parent_uid: c807d991-0c36-a7b6-1022-b5e758877384
title: Software and Copyright Law
uid: 963f6cb7-12ed-d701-648b-00b2adeb8762
---

*   [Whelan v. Jaslow](#whelan)
*   [Computer Associates v. Altai](#altai)
*   [Apple v. Microsoft](#apple)
*   [The Lotus Look and Feel Suits](#lotus)
*   {{% resource_link 6cc29e9b-b358-33cf-1d3c-42b5cd66ceed "Back to readings on information and intellectual property" %}}

The situation with software copyright is no less confusing than with software patents. If programs are "abstract machines" or "methods of operation", are they copyrightable at all? The Supreme Court gives little guidance here. One possible precedent is {{< anchor "baker" >}}{{< /anchor >}}{{% resource_link "febd0da0-5662-4fea-adc1-fbafdf240dd4" "Baker v. Selden, 101 U.S. 99 (1879)" %}} in which the Court ruled that describing a system of accounting in a textbook did not confer copyright protection on the system itself:  
The description of the art in a book, though entitled to the benefit of copyright, lays no foundation for an exclusive claim to the art itself. The object of the one is explanation; the object of the other is use. The former may be secured by copyright. The latter can only be secured, if it can be secured at all, by letters-patent.  
The Copyright Act of 1976 stipulates (section 102):  
(b)In no case does copyright protection for an original work of authorship extend to any idea, procedure, process, system, method of operation, concept, principle, or discovery, regardless of the form in which it is described, explained, illustrated, or embodied in such work.

Congress attempted to clarify the situation for computer programs (Rep. No. 473, 94th Cong., 1st Sess. 54 (1975)):

Section 102(b) is intended, among other things, to make clear that the expression adopted by the programmer is the copyrightable element in a computer program, and that the actual processes or methods embodied in the program are not within the scope of the copyright law.

and the National Commission on New Technological Uses of Copyrighted Works (CONTU), wrote in its final report (1978):  
Where could a meaningful line of demarcation be drawn? Between flow chart and source code? Between source code and object code? . . . The Commission believes that none of these is appropriate. The line which must be drawn is between the expression and the idea, between the writing and the process which is described.

Are you confused by this? Join the crowd. Almost everyone agrees that the literal code of a computer program is copyrightable. But beyond that, things are muddled.  
The following sequence of cases shows judges struggling with the distinction between "expression" and "idea" in computer programs. As you'll see, the result is far from satisfactory.

{{< anchor "whelan" >}}{{< /anchor >}}1985-1986: Whelan v. Jaslow: "Structure, Sequence, and Organization"
----------------------------------------------------------------------------------------------------------

In 1985, Jaslow Dental Laboratory sued Whelan Associates, Inc., on the grounds that Whelan's "Dentcom" program infringed Jaslow's copyright on its "Dentalab" program, even though there was no issue of any literal code being copied. (Jaslow's program was written in Event Driven Language (EDL) while Whelan's was written in BASIC.) The District Court ruled for Jaslow. Whelan appealed, and Appeals Court for the Third Circuit upheld the ruling. The Court began by stating:

.. we must determine whether the structure (or sequence and organization) . . . of a computer program is protectible by copyright, or whether the protection of the copyright law extends only as far as the literal computer code.

The Court found:  
\[T\]he coding process is a comparatively small part of programming . . . . The evidence in this case is that Ms. Whelan spent a tremendous amount of time studying Jaslow Labs, organizing the modules and subroutines for the Dentalab program, and working out the data arrangements, and a comparatively small amount of time actually coding the Dentalab program.

The conclusion was:

We hold that ... copyright protection of computer programs may extend beyond the programs' literal code to their structure, sequence, and organization,

The Court not only held that "structure, sequence, and organization" (which became known as SSO in computer copyright law) but remarked in a footnote:  
We use the terms "structure," "sequence," and "organization" interchangeably when referring to computer programs, and we intend them to be synonymous in this opinion.

{{< anchor "altai" >}}{{< /anchor >}}{{< anchor "1992" >}}{{< /anchor >}}1992: Computer Associates v. Altai: SSO Rejected
-------------------------------------------------------------------------------------------------------------------------

In this decision, the Second Circuit Court of Appeals upheld a district court ruling that Altai's program did not infringe one by Computer Associates. This was a second version of Altai's program. The first version had been written by an ex-employee of CA, who (unknown to Altai) had copied about 30% of the code from a similar CA program. Altai then wrote a clean-room second version, using programmers who had never seen the CA code. CA claimed that the second version of the program, even though it was a clean-room development, nevertheless copied the structure of the CA program.  
In the District Court opinion, the judge relied on report by Prof. Randy Davis of MIT, who was appointed as an expert to assist the Court. Davis pointed out that the SSO test does not make sense, since a program consists of both text and behavior. The code is text (static structure), but the user of the program deals with its behavior (dynamic structure) which may not be copyrightable. Thus, to analyze copyrightability in terms of "structure" is ambiguous, and to identify structure with "sequence" and "organization", as the Whelan Court had done, is fallacious.  
The Second Circuit agreed, and it criticized the Whelan Court's SSO analysis as showing "a flawed understanding of a computer program's method of operation," and a "somewhat outdated appreciation of computer science."  
The Court concurred with the Whelan decision that copyright can be infringed even if no literal code is copied, but it continued: "that conclusion does not end our analysis. We must determine the scope of copyright protection that extends to a computer program's non-literal structure."  
In place of SSO, the Court proposed using a three-step abstraction-filtration-comparison process to gauge the similarity of two computer programs. This process first describes the two programs at various levels of abstraction; then, at each stage, filters out the elements that are not subject to copyright; finally, it compares the results. Most courts now try to follow this procedure, even though it can be complex and highly subjective.

{{< anchor "apple" >}}{{< /anchor >}}1989-1992: Apple v. Microsoft
------------------------------------------------------------------

In 1989, Apple filed suit against Microsoft and Hewlett-Packard, claiming that the Windows graphical user interface (Windows 2.03 and HP's New Wave) infringed Apple's copyright on the "look and feel" of the Macintosh desktop. (As Apple argued: "We invented the desktop metaphor.") Apple eventually lost in district court in 1992.  
This was a complex decision in which the copyright infringement claims for the various elements of the desktop were thrown out on a variety of grounds. One important basis for the ruling was the court's finding that the appropriate standard to apply was whether the two GUI presentations were "virtually identical," whereas Apple had argued that the appropriate standard was "substantial similarity." The decision of the lower court was upheld by the 9th Circuit in 1994.

*   Joseph Myers, Apple v. Microsoft: Virtual Identity in the GUI Wars, 1 _Richmond Journal of Law & Technology_ 5 (1995). This article reviews the history of the case and explains the significance of the decision.
*   The following material is on reserve for the course:
    *   Apple's second supplemental list of similarities between Windows and NewWave (filed April, 1991).
    *   Oral arguments in court before Judge Walker, April 14, 1992, and ruling
    *   Summary of the April 14, 1992 ruling
    *   Judge Walker's August 7, 1992 ruling

{{< anchor "lotus" >}}{{< /anchor >}}1990-1995: The Lotus Look and Feel Suits
-----------------------------------------------------------------------------

The _Lotus v. Borland_ lawsuit was a major test of the copyrightability of the "look and feel" of computer programs. At issue was whether the menu structure -- the arrangement of commands in the menu hierarchy in Lotus 1-2-3 -- is copyrightable. Here is a brief history of the case, with links to further material:  
In 1990, Lotus sued Paperback Software and Mosaic Software, who had produced spreadsheets that had the same interface as 1-2-3. There was no issue here of copying code, but Lotus claimed that copying the interface itself constituted copyright infringement. Lotus won, and both companies went out of business. The following material on this decision is on reserve for the course:

*   Judge Keeton's ruling in _Lotus Development Corporation v. Paperback Software International and Stephenson Software, Ltd_. U.S. District Court, District of Massachusetts, June 28, 1990.
*   Samuelson, Pamela. "How to interpret the Lotus decision and how not to." _Communications of the ACM_, November 1990.

Lotus then sued Borland over Quattro. Even though Quattro's user interface was different from that of 1-2-3, Quatttro was able to interpret Lotus macros (which followed the Lotus menu hierarchy), and Lotus claimed that this was also copyright infringement. The District Court agreed, and Borland appealed the decision. The following material is on reserve for the course:

*   Judge Keeton's ruling in _Lotus Development Corporation v. Borland International_, U.S. District Court, District of Massachusetts, July 31, 1992.
*   Two amicus curiae briefs in the appeal of _Lotus v. Borland_, one on behalf of a group of computer science professors, and one on behalf of a group of copyright law professors.

The U.S. First Circuit held for Borland, reversing the District Court's decision on unexpected grounds. Borland's appeal, and the amicus briefs, had argued, using the guidelines set forth in _Altai_ ([see above](#1992)) that the two programs were not sufficiently similar. But according to the appeals court, the issue was not "substantial similarity" at all. Rather, they held that the menu structure of Lotus 1-2-3 was a "means of operation" and reasoned based on _Baker v. Selden_ ([see above](#baker)) that the menu structure was not copyrightable in the first place:  
Concluding, as we do, that users operate Lotus 1-2-3 by using the Lotus menu command hierarchy, and that the entire Lotus menu command hierarchy is essential to operating Lotus 1-2-3, we do not inquire further whether that method of operation could have been designed differently. The "expressive" choices of what to name the command terms and how to arrange them do not magically change the uncopyrightable menu command hierarchy into copyrightable subject matter.

*   Appeals court decision ({{% resource_link bec25eb3-7d34-2f16-0850-05289525844d "PDF" %}}) of March 9, 1995, reversing the District Court's 1992 ruling.

Lotus appealed the decision to the Supreme Court:

*   Lotus's petition to the Supreme Court for a writ of certiorari ({{% resource_link 57eeb3c9-8bd3-947a-72f7-01fa15fead0f "PDF" %}}), June 7, 1995.
*   Borland's brief in opposition ({{% resource_link 25af7f00-6680-8a96-0aea-450ee5215e28 "PDF" %}}) to petition for certiorari, July, 1995.
*   Lotus's reply ({{% resource_link 3feefa73-5cd9-b205-98f6-af0099c5eb2e "PDF" %}}) in support of the petition.

On September 27, 1995, the Supreme Court granted Lotus's petition. The finding that user interfaces might consist of inherently uncopyrightable "means of operation" had pulled the rug out from under the proponents of strong user-interface copyright. The case generated major interest, and several amicus curiae briefs were filed:

*   {{% resource_link "3178f591-3443-46e9-8df9-c87ad4cb8c18" "Amicus brief" %}} filed in the Supreme Court in support of Lotus's position by DEC, Gates Rubber Company, Intel, and Xerox.
*   Amicus brief ({{% resource_link f156e94c-1f8f-6cf1-6706-66668b57ce9d "PDF" %}}) filed in the Supreme Court against the Lotus position, on behalf of a group of computer science professors.
*   Amicus brief ({{% resource_link b1db764b-412c-a7f6-d585-ab656ab715b7 "PDF" %}}) filed in the Supreme Court against the Lotus position, on behalf of the League for Programming Freedom.
*   Amicus brief ({{% resource_link 73c0b4b4-6d16-c2f8-081f-87edc2a8c3fa "PDF" %}}) filed in the Supreme Court against the Lotus position, on behalf of a group of copyright law professors.

Oral arguments were held on January 8, 1996. People expected that the Supreme Court would use this as an occasion to issue a major ruling on intellectual property issues for software, and perhaps to clarify the relative roles of patents and copyrights for software. But a week after the oral arguments, the Court announced that it would issue no decision at all. The Justices had split 4-to-4 (Justice Stevens having recused himself):

*   Newsbytes News Network. "High Court Punts On Lotus vs. Borland." Washington DC, U.S.A. January 17, 1996.

The inability of the Justices to decide left the Appeals Court ruling standing by default, with the Supreme Court neither explicitly affirming nor rejecting this central issue in software copyrightability.