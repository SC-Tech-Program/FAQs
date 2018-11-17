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

**Q5. Who will review my appendices?**

A5. The AD & AE Appendices will be reviewed _with your paper_ by the Technical Program committee, but the artifact URLs will be removed from the version they review, as a precaution in support of double-blind review.
In addition, the **AD/AE Appendices Committee** will review the unredacted appendices, and will check that artifacts are indeed available in the URLs provided. They will also help authors improve their appendices, in a double-open arrangement.

**Q6. How will review of appendices interact with the double-blind review process?**

A6. The AD appendix should describe the data, software and hardware artifacts involved in producing the results.
Reviewers _could_ discover the author's identity if they embark on an online search, but they will be asked _not to_, in support of double-blind review. Author-provided artifact URLs will be redacted from the appendices provided to the reviewers.

## <a name="impact"></a>Impact of AD and AE Appendices 

**Q7. What's the impact of an Artifact Description appendix on scientific reproducibility?**

A7. Reproducibility depends on, as a first step, sharing the provenance of results with transparency, and the AD appendix is an instrument of documentation and transparency. A good AD appendix helps researchers document their results, and helps other researchers build from them.

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
