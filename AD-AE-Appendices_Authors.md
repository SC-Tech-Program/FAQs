# AD/AE Appendices Author FAQ

Artifact Description (AD) Appendices are required for all papers submitted to the Technical Program at SC19.
Artifact Evaluation (AE) Appendices are optional, but strongly encouraged.

[AD and AE Appendix Requirements](#requirements)

[Review Process](#review)

[Impact of AD and AE Appendices](#impact)

[ACM Artifacts Available and Artifacts Evaluated Badges](#badges)

## <a name="requirements"></a>AD and AE Appendix Requirements 

**Q1. Are AD and AE appendices required in order to submit to SC19?**

A1. An AD appendix is _required_ for all Technical Program submissions.
An AE appendix is _optional_ but strongly encouraged.

**Q2. Do I need to make my software open source in order to complete the AD appendix?**

A2. No. You are not asked to make any changes to your computing environment in order to complete the appendix. 
The AD appendix is meant to _describe_ the computing environment in which you produced your results.
Any author-created software _does_ need to be open source, however, to be eligible for the ACM Artifacts Available badge (see below).

**Q3. How should I format my AD Appendix**

Q3. You don't need to worry about formatting the Appendices. You will be presented with an online form during the paper submission with questions that you will answer directly on the submission site. After answering the questions, the system will automatically generate a PDF of the Appendix for you.

**Q4. What information do I need to provide in the AD/AE Appendix online form?**

Q4. A printout of the questions included in the AD/AE Appendix online form is provided in the [`Author-Kit`](https://github.com/SC-Tech-Program/Author-Kit) repository. Be sure to familiarize yourself with these _before writing your paper_, and ideally before or while you are producing your results.

## <a name="review"></a>Review Process 

**Q. Who will review my appendices?**

A. The AD and/or AE appendices will be submitted at the same time as your paper and will be reviewed as part of the standard review process by the same individuals who review the rest of your paper.

**Q. Will the information in these appendices reveal an author’s identity, thus interfering with the double-blind review process?**

A. It is possible that information provided in an appendix could reveal some information about an author’s identity, but this is most likely no more revealing than self-citations in the bibliography. Listing the software you used does not necessarily mean you developed the software. As with self-references in your text, you should refer to software from a third-person perspective. If you think any particular piece of information requested in an appendix could unambiguously identify you, you may state: “Information will be provided if and when the paper is accepted.” Finally, if you have any unaddressed concerns about completing appendices for SC18, please contact us: maherou@sandia.gov.

## <a name="impact"></a>Impact of AD and AE Appendices 

**Q. Does the artifact description appendix really impact scientific reproducibility?**

A. The AD appendix is simply a description of the computing environment used to produce the results presented. By itself, this appendix does not directly improve scientific reproducibility. However, if this artifact is done well, it can be used by scientists (including the authors at a later date) to more easily replicate and build upon these results. Therefore, the AD appendix can reduce barriers and costs of replicating published results. It is an important first step toward full scientific reproducibility.

**Q. Does the artifact evaluation appendix really impact scientific reproducibility?**

A. A thorough artifact evaluation effort is an effective way to increase the trustworthiness of computational results from “boutique” platforms. Leadership computing platforms, novel testbeds, and experimental computing environments are of keen interest to the supercomputing community. At the same time, these platforms are often volatile and possess a higher risk of unanticipated behavior.

Furthermore, access to these systems is typically limited, making it nearly impossible for most reviewers to independently compute author results. Finally, the volatility of these platforms often makes it hard for the authors themselves to recompute their own results in the future, since changes in the environment (compilers, libraries, components, etc.) impact computational results, and there is no way to revert to previous system states.

For all of these reasons, the introduction of upstream setup testing, peri-execution time testing and post-execution analysis can improve confidence that computational results from these special platforms are correct.

## <a name="badges"></a>ACM Artifacts Available and Artifacts Evaluated Badges 

**Q. The Artifacts Available badge description on the ACM website states: “Personal web pages are not acceptable for this purpose.” I do not have free access to any repositories aside from my personal website. Does SC provide a permanent repository?**

A. No. There are numerous source hosting platforms that provide free or inexpensive hosting. You should use one of these.

**Q. Do I get any recognition for submitting an AD and/or AE appendix?**

A. **ACM Artifacts Available badge:** An accepted paper with a fully completed artifact description appendix is eligible for the ACM Artifacts Available badge if the artifacts listed in the appendix are downloadable by anyone without restriction.

**ACM Artifacts Evaluated -- Functional badge:** An accepted paper with fully completed artifact description and artifact evaluation appendices is further eligible for the ACM Artifacts Evaluated -- Functional badge if its artifacts are downloadable and positively evaluated by reviewers.

**ACM Replicated Computational Results badge:** An accepted paper that contains an AD appendix will be considered for inclusion in the SC Student Cluster Competition (SCC), where student teams will attempt to replicate the results presented in the paper. Papers will be selected based on their suitability for use in the SCC. Papers selected for the SCC will receive the ACM Results Replicated badge.

Please see the [ACM Artifact Review and Badging page](https://www.acm.org/publications/policies/artifact-review-badging) for details.
