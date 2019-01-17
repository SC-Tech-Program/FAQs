---
layout: page
title: Technical Papers Author FAQ
permalink: /tech-papers-author/
---

If you still have questions, you can email papers@info.supercomputing.org

Paper formatting
----------------

**Q: What are the length restrictions on paper submissions?**

A: Submissions are limited to 10 pages, excluding the bibliography, using the ACM SIG proceedings template, with line numbering enabled to help with review. In LaTeX, this implies a document class of:
```LaTeX
\documentclass[sigconf,review]{acmart}
```
AD and AE appendices are automatically generated and do not count against the 10 pages.

Authors of accepted papers can provide supplemental material with their final, camera-ready version of the paper (e.g., additional proofs, videos, or images).


**Q: Do the AD and AE appendices count against the 10 pages?**

A: No.  These are created separately via an HTML form and are not considered part of the paper proper.

**Q: How should papers be formatted?**

A: For consistency across the entire proceedings, papers must be written in [ACM SIG proceedings style](https://www.acm.org/publications/proceedings-template) with line numbering enabled to help with the review process.  In LaTeX, this implies a document class of

```LaTeX
\documentclass[sigconf,review]{acmart}
```

Contribution Track
------------------

**Q: Is it mandatory for authors to select the primary track of their contribution?**

A: Yes. Authors must indicate a primary track from the ten choices on the submissions form and are strongly encouraged to indicate a secondary track.

**Q: Who will review my paper?  The program committee corresponding to my primary contribution track?  My secondary track?  Both?  Neither?**

A: Papers are assigned to the most suitable program committee for the contribution track.  The author-indicated primary and secondary track choices are used as guidelines but do not exclude more suitable program committees.

Paper Eligibility
-----------------

**Q: Can I put my paper on arXiv before submitting it to SC?**

A: Yes.  Papers that have not previously been peer-reviewed are eligible for submission to SC.

**Q: If my paper was already published in a workshop, can I also submit it to SC?**

A: Yes.  However the paper needs to have been substantially enhanced since prior publication (say, 30% new material) to be eligible for submission to SC.

The Peer-Review Process
-----------------------

**Q: What is the sequence of events that make up the peer-review process?**

A: From an author’s perspective, the following are the key steps:

1. Authors submit a title, abstract, and other metadata.
2. Authors submit their full paper and complete a form describing their computational artifacts (or lack of computational artifacts) and, optionally, text discussing how they evaluated their computational results.
3. Authors receive an initial set of reviews of their paper.
4. Authors have an opportunity to revise their paper and prepare an accompanying response to the reviewers.
5. Author revisions and accompanying response will be available to the reviewers at least a week before the PC meeting.
6. Authors are notified of their paper’s disposition: Accept, Reject, or Major Revisions Required.
7. In the case of Major Revisions Required, authors prepare a major revision for re-review.
8. After this review, the paper will be either accepted or rejected.
9. Authors of accepted papers prepare the final version of their paper.

**Q: Is there an author response/rebuttal stage?**

A: Yes.  Once authors receive their initial feedback from the reviewers, they are given the opportunity to improve their paper accordingly before the next round of reviews.  For example, if a reviewer indicates that a paper requires some critical measurement or explanation to be worthy of publication, the authors can supply that missing information.  An accompanying response document highlights the changes the authors made.  This is unlike the rebuttal stage present in many other conferences in that the focus is less on promises to fix problems for the final document and more on actually fixing the problems.

**Q: If I don’t have time to gather the additional data the reviewers requested by the revise-and-respond deadline but can do so by the final paper deadline, can my response indicate that.**

A: Yes.  Depending on what other concerns reviewers have with the paper, it may still be rejected.  Another possibility is that reviewers may want to see a major revision in this case to ensure that no information critical to the paper’s argument is missing.

**Q: Now that I’ve read the reviews of my paper, I see much better how to organize it so it will be clear to the reader. Can I do this reorganization and upload the new version during the revise-and-respond period?**

A: Yes. We encourage you to submit this kind of change as a revision, provided that you clearly document your changes. The committee members will have only a short time in which to read and act on your revision, and you must make it clear what changes you have made and why.

**Q: Between paper submission and the author response period, we’ve gotten some really cool new results for our paper. Can I upload those results during the revise-and-respond period? I’m sure that they will make the reviewers realize the importance of our approach.**

A: Yes, but you must clearly document your changes and rationale in your author response.

**Q: Doesn’t this incentivize authors to submit an extremely rough first draft, and only make updates after reviewer feedback?**

A: Perhaps, but as the old adage goes, there’s no second chance to make a first impression. Your reviewers will have had much more time to look at your first draft, and their initial scores will be based on it. SC introduced the revise-and-respond process on the belief that an actual revision is far more persuasive than promises made in a rebuttal.  That does not mean that revisions will change a reviewer’s mind if their first impression of a paper was completely negative. Because reviewers will have limited time to scrutinize your revisions, you should strive to make every phase of the submission process count.

**Q: What if a reviewer clearly didn’t read my paper carefully enough? What if the reviewer seems to lack basic knowledge of the area on which the paper focuses? How should my author response and revision address these issues?**

A: We’ve all received reviews that made us angry, particularly on first reading. The revision period is short and doesn’t allow for the cooling-off period that authors have before they write a response to a journal review. We provide you the opportunity to submit a revision and response to address these issues, but you should still be careful with the wording of your response.  For example, we recommend you don’t say: “If reviewer X had just taken the time to read my paper carefully, they would have realized that our algorithm was rotation invariant.” Instead say, “Unfortunately, Section 4 must not have been as clear as we had hoped because Reviewer X did not understand that our algorithm was rotation invariant and they were therefore skeptical about the general applicability of our approach. The revised version of the second paragraph in Section 4 should clear up this confusion.”  The revise-and-respond process offers more opportunity than what is present in other conferences to convince your reviewers of the merits of your work; use such opportunities wisely.

Double-blind reviewing
----------------------
See the full policy at [ FIXME need the final link ]

**Q: What is double-blind reviewing?**

A: Double-blind reviewing means that not only do authors not know the identities of their paper’s reviewers, but reviewers don’t know the identities of the paper’s authors until after acceptance decisions have been made.  Reviewers will not learn the identity of the authors for rejected papers.

**Q: Why does SC employ double-blind reviewing?**

A: Studies indicate that double-blind reviewing goes a long way in reducing unconscious bias (e.g., based on institution, seniority, nationality, or gender) on the part of the reviewers.  For more information, here are some entry points into the relevant literature:

* “More on Improving Reviewing Quality with Double-Blind Reviewing, External Review Committees, Author Response, and in Person Program Committee Meetings” by McKinley (2015), http://www.cs.utexas.edu/users/mckinley/notes/blind.html
* “Reviewer bias in single- versus double-blind peer review” by Tomkins (2017), https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5715744/


**Q: How should I prepare my paper for double-blind review?**

A: SC requires only that there be some level of doubt as to the authors’ identities, not that only intelligence agencies could possibly determine who the authors are.  Consequently, there are only two key pieces to SC’s double-blind policy:

1. Don’t state the authors’ names, institutions, or other identifying information anywhere in the paper.
2. Write in the third person about your prior work, software, etc.

In particular, redact nothing:

* Don’t avoid citing your own work (lest reviewers criticize the paper for not citing important prior results).
* Don’t obscure the hardware platforms you used/built, even if relatively few people have access to that hardware.
* Don’t obscure the software you used/developed, even if relatively few people have access to that software.

For example, consider the following alternatives:

> **Bad**: We enhanced our INTERCAL compiler [1] to accept keywords in Pig Latin.
>
> [1] ⬛⬛⬛⬛⬛⬛⬛⬛.  “A high-performance parallel INTERCAL compiler”, International Conference on HPC-Related Stuff, 2019.

versus

> **Good**: We enhanced Bloggs and Doe’s INTERCAL compiler [1] to accept keywords in Pig Latin.
>
> Joe Bloggs and Jane Doe.  “A high-performance parallel INTERCAL compiler”, International Conference on HPC-Related Stuff, 2019.

and

> **Bad**: We ran all of our experiments on a large HPC system at a high-security supercomputing center.

versus

> **Good**: We ran all of our experiments on the WOPR supercomputer at the Cheyenne Mountain Complex.

**Q: What if I’m okay with the reviewers knowing who I am?  Do I still need to prepare my paper double-blind?**

A: Yes.  The point is to avoid bias not only against certain groups but also in favor of certain groups.  For example, we don’t want reviewers automatically favoring a paper written by a Turing Award winner at MIT over a paper written by a first-year student at a lesser-known college.

**Q: What if I previously made my paper available under the same name and with the same authors as an institutional technical report, arXiv preprint, or other non-peer-reviewed release?  Won’t the reviewers easily be able to figure out who I am?**

A: They could, but reviewers are asked to avoid trying to learn the authors’ identities.

Artifact Description (AD) and Artifact Evaluation (AE) Appendices
-----------------------------------------------------------------

**Q: What is the AD appendix?**

A: The AD appendix, generated by the SC submission site from content gathered via a form, lets authors share with readers a description of the data, software, and hardware artifacts relied on to produce the paper’s results and provide links to persistently archived data and software products.

See the [AD/AE Appendices FAQ](AD-AE-Appendices_Authors.md) for complete information.

**Q: Does writing an AD appendix imply I can skip/shorten my paper’s experimental-setup or or other such sections?**

A: An SC paper must stand on its own and will be reviewed as such.  The AD appendix provides additional information to reviewers and readers, helping them better interpret the results and helping other researchers build on those results.

**Q: What is the AE appendix?**

A: The AE appendix, generated by the SC submission site from a free-text form field, lets authors explain the trustworthiness of their data by detailing: their approach to verification and validation, statistics gathered, uncertainty-quantification techniques applied, conditions controlled/not controlled for, and other details that convey a sense of the confidence on the reported results.  This is especially useful for results obtained in computational environments that are not widely accessible and/or an environments that are not reproducible.

**Q: Are the AD and AE appendices mandatory or optional?**

A: Starting with SC19, the AD appendix is mandatory for all papers in the Technical Program, and optional for posters and workshop papers.  (In prior years, it was requisite only for a paper to be considered for Best Paper or Best Student Paper.)  The AE appendix is optional but strongly recommended.

**Q: What if our paper does not have any associated artifacts?**

A: Although we expect this to be a rare occurrence for SC papers, the first question in the required Artifact Description form enables authors to indicate that they do not have any software, hardware, or data artifacts associated with the submitted paper.

**Q: Will the paper reviewers also be reviewing the AD and AE appendices?**

A: Yes.  Their focus will be on the paper itself, but they can refer to the appendices for clarification and convincing of the reliability of the reported results. For compatibility with the double-blind review process, URLs linking to archived artifacts will be removed before review.

**Q: Doesn’t an artifact description conflict with double-blind reviewing?**

A: Since your paper should stand on its own without the AD appendix, the paper would already have a third-party citation to software and hardware the research builds on.  Keep in mind that double-blind reviewing is for reducing the chances that a reviewer will be able to guess your identity.  You do not have to guarantee it.  If you provide links to your software in the AD appendix form question asking for links, those link will *not* be shared with PC members during the review process.


Plagiarism
----------

**Q: I understand that the SC Conference applies a plagiarism test program to submissions. What constitutes plagiarism? Is it possible for an author to plagiarize their own work?**

A: Please see [ACM’s guidelines on identifying plagiarism](https://www.acm.org/publications/policies/plagiarism).  Authors should submit new, original work that represents a significant advance from even their own prior publications.

Conflicts of Interest
---------------------

**Q: What are the SC guidelines for Conflicts of Interest (COI)?**

A: A potential conflict of interest occurs when a person is involved in making a decision that 1) could result in that person, a close associate of that person, or that person’s company or institution receiving significant financial gain, such as a contract or grant, or 2) could result in that person, or a close associate of that person, receiving significant professional recognition, such as an award or the selection of a paper, work, exhibit, or other type of submitted presentation.

The Papers Committee members will be given the opportunity to list potential conflicts of interest during the review process. Papers Committee chairs and track chairs will make every effort to avoid assignments that have a perceived COI.

According to the SC conference you have a conflict of interest with the following:

* Your PhD advisors, post-doctoral advisors, PhD students, and post-doctoral advisees;
* Family relations by blood or marriage, or equivalent (e.g., a partner);
* People with whom you collaborated in the past five years. Collaborators include: co-authors on an accepted/rejected/pending research paper; co-PIs on an accepted/pending grant; those who fund your research; researchers whom you fund; or researchers with whom you are actively collaborating;
* Close personal friends or others with whom you believe a conflict of interest exists;
* People who were employed by, or a student at, your primary institution(s) in the past five years, or people who are active candidates for employment at your primary institution(s).

Note that “service” collaborations, such as writing a DOE, NSF, or DARPA report, or serving on a program committee, or serving on the editorial board of a journal do not inherently create a COI.

Other situations can create COIs, and you should contact the Technical Papers Chairs for questions or clarification on any of these issues.

Specific technical tracks
-------------------------
**Q: What kind of papers is the Performance Measurement, Modeling, and Tools Track looking for?**

"Performance" can be broadly construed to include any number of metrics, such as execution time, bandwidth, energy, power; it can also include measures of correctness and resilience. Techniques that exploit machine learning should have a primary focus on applying their techniques to analyze or enhance system performance.  If their focus is more on the machine learning algorithm itself, then consider submitting to the new ML and HPC track.

Submissions in to the Performance track are encouraged to show the applicability and reproducibility of their results by means such as sensitivity analysis, performance modeling, or code snippets.

**Q: What constitutes a State of the Practice (SOP) paper?**

A: An SOP paper can describe a first-of-its-kind technology or methodology, or can capture a unique perspective (or experience) on issues, challenges, and solutions for dealing with aspects of unprecedented scale and complexity, particularly experience and knowledge that can be generalized to a wide range of systems and usages. Concrete case studies within a conceptual framework (i.e., experiential topics) would likely serve as the basis for SOP papers, and generalizing the experience to wider applicability should be explored.

**Q: I am concerned that if the standards for SOP are the same as for other papers, the SOP papers will be rejected for not being sufficiently academically rigorous. How will reviewers handle this?**

A: Although SOP papers will be reviewed with the same academic rigor as the papers in other tracks, the acceptance criteria will be tailored to value new and generalizable insights as gained from experience with particular HPC machines, operations, applications, or benchmarks; overall analysis of the status quo of a particular metric of the entire field; or historical review of the progress of the field.

Such papers are common in other academic disciplines, including branches of computer science. For example, software engineering highly values the “experience papers” of particular frameworks and methodologies; human–computer interaction produces numerous analyses of human behavior given particular interfaces; social sciences collect data on social phenomena and produce meaningful insights based on their statistical analysis.

**Q: I used machine learning to improve *X*.  The call for papers lists machine learning as a topic of interest for *X*, but there’s also a whole Machine Learning and HPC (ML&HPC) track.  Should I list *X* or ML&HPC as the primary contribution track?**

A: Authors should send papers whose focus is on introducing new ML techniques that are not specific to a particular Papers track to the ML&HPC track.  Authors should send papers whose work is specific to a track (Applications, Architecture and Networks, System Software, etc.) to that track.  ML&HPC may be listed as the secondary contribution track if appropriate.

Awards
------

**Q: Is there an award given for best paper?**

A: Yes. Best Paper (BP) and Best Student Paper (BSP) nominations are made during the review process and are highlighted in the conference program.  BP and BSP winners are selected at the conference by a committee who attends the corresponding paper presentations, and winners are announced at the award ceremony on the Thursday of the conference.
