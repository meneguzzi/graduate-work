# Checklist for MSc Deliverables

The following checklist applies to MSc deliverables in Aberdeen. Do not forget to read my [tips on writing good science](http://www.meneguzzi.eu/felipe/writing.shtml), and double check the [MSc Manual](https://abdn.blackboard.com/ultra/courses/_64576_1/outline/edit/document/_4002582_1?courseId=_64576_1&view=content).
Since I want all academic documents written in LaTeX, please use this handy [template for final year projects](https://bitbucket.org/mflash/ep-tcc/src/master/).
You should probably use [Overleaf](https://www.overleaf.com/) to write your LaTeX documents so you can easily share it with me for feedback.
Please do not email me Word Documents or PDFs, I will comment directly on your LaTeX sources. 
If you don't know anything about LaTeX, I suggest you check out this [Quick tutorial on LaTeX](https://github.com/VoLuong/Begin-Latex-in-minutes) available on Github.
Finally, besides the specific points I make in this checklist, be mindful of the following quality items for anything scientific you write:

- [ ] Figures and Tables must always have a numbered caption and be referenced in the text. A Figure may be worth a thousand words, but it must be described in a couple of dozen to make sense in the text. 
- [ ] Level of detail: when talking about multiple subjects in a section, be sure to use a consistent level of detail. It reads very poorly if you describe a certain technique in a three-sentence paragraph while put the code in C for another technique in the same section.
- [ ] Arguments and citations: any objective statement (which ought to be most of your text) you write in your text must be backed either by your own work (self-contained) or by a citation to somebody else's peer-reviewed work. Be very careful about statements of the type '*Algorithm X and Y are the most widely used for frombotzing deterons*'

## Project Plan

The text you deliver as your plan must clearly outline what you want to *study* throughout the semester. You do not necessarily need to have a specific problem set out yet. However, you must know clearly what is the general area in which you want to solve a problem, and show that you have used the first few weeks to read about it. This is what I expect of the text my students hand in:

- [ ] Abstract: the abstract must answer the following questions
  - [ ] What is the problem your project aims to address?
  - [ ] Why is this problem interesting?
  - [ ] How do you aim to solve the problem?
  - [ ] What follows from your solution?
- [ ] Introduction: check that your introduction satisfies the following items:
  - [ ] Avoid jargon <br/> Do you avoid jargon that you only explain in the rest of the text?
  - [ ] Clarity <br/> Can anyone from computer science read the introduction and understand what you want to achieve?
  - [ ] Does it clearly describe the problem?
  - [ ] Does the introduction clearly state the contributions?
  - [ ] Does the introduction motivate the problem you are trying to solve?
<!-- - [ ] Literature Review: the literature review should convey your knowledge of the subject of the proposal, so check for
  - [ ] Does it provide basic definitions of the area?
  - [ ] Terminology dropping from the sky <br/> new technical terms must be explained before they are used, avoid talk about a deteronic frombotzer if you have not said what this is
  - [ ] Consistency of terminology <br/> do not use different terms to refer to the same technical entity, once you define something as X always refer to it as X
  - [ ] Are the references up to date <br/> i.e. do you cite work that was published in the last 5-10 years -->
- [ ] Objectives: this is the objective of your design, it will generally focus on studying something to plan for its implementation
  - [ ] General objective <br/> i.e. a brief statement of what it is you want to accomplish
  - [ ] Specific objectives <br/> i.e. a list of concrete goals (you can think of them as 'deliverables')
- [ ] Risk Assessment:
  - [ ] Does it account for unusual requirements <br/> such as data, hardware, or any critical resource not usually available at the university?
  - [ ] Do you have a mitigation plan for the lack of the above?
- [ ] Outline Timetable:
  - [ ] Real timeline <br/> Does it contain work for all months of the work? Do not count the month you wrote this.
  - [ ] Realistic plan <br/> Avoid doing too many actions in the same month
  - [ ] Achievable plan <br/> You must be able to deliver what you said you would
  - [ ] Avoid copying specific objectives <br/> but the work to reach them can drive this timeline
- [ ] Bibliography: check the bibliography for the following items
  - [ ] Are all references rendering correctly with BibTex (check for foreign language characters and odd symbols)?
  - [ ] Are all references correct? Remember DBLP, ACM, Google Scholar and other automated databases **do** contain errors
  - [ ] Are any important references missing?

## MSc Dissertation

- [ ] Abstract: the abstract must answer the following questions
  - [ ] What is the problem your contribution addresses?
  - [ ] Why is this problem interesting?
  - [ ] How do you solve the problem?
  - [ ] What follows from your solution?
- [ ] Table of Contents
- [ ] Glossary/Abbreviations (if your work is acronym heavy)
- [ ] Introduction: check that your introduction satisfies the following items:
  - [ ] Avoid jargon <br/> Do you avoid jargon that you only explain in the rest of the text?
  - [ ] Clarity <br/> Can anyone from computer science read the introduction and understand what's the objective?
  - [ ] Does it clearly describe the problem?
  - [ ] Does the introduction clearly state the contributions?
- [ ] Literature Review Chapters: must convey your knowledge of the subject of the work, so check for
  - [ ] Self-containment <br/> Is the literature review enough to understand how you solve the problem?
  - [ ] To the point <br/> Do you have content that is not really relevant for the work? You may need to remove stuff from the material you wrote before to match the problem you actually solved
  - [ ] Balanced chapters/sections <br/> the review chapter can be divided into multiple chapters, make sure subjects are well-balanced in the chapters
  - [ ] Basic definitions <br/> Does it provide basic definitions of the area?
  - [ ] Terminology dropping from the sky <br/> new technical terms must be explained before they are used, avoid talk about a deteronic frombotzer if you have not said what this is
  - [ ] Consistency of terminology  <br/> do not use different terms to refer to the same technical entity, once you define something as X always refer to it as X
- [ ] Implementation/Development: here you should describe the details of your contribution so that others can replicate it. Check for
  - [ ] Replicability: is there enough detail that one of your colleagues can replicate your work **without looking at your code**?
  - [ ] Internal consistency: is the terminology and technical concepts used here consistent with what you defined in the literature review?
- [ ] Evaluation: for works with an empirical evaluation component. Check for
  - [ ] Environment description: do you clearly describe your testing rig? 
  - [ ] Results: do you include an objective description of your results (tables, graphs, et)?
  - [ ] Assessment: do you explain the meaning of the results and the implication of them to the problem?
- [ ] Conclusion: here, you summarize what are your contributions and how you envision them going forward
  - [ ] Contributions: what did you achieve in this work?
  - [ ] Limitations: what are any problems or limitations to your contribution?
  - [ ] Future work: what can be done to improve your work?