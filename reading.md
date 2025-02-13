Teaching ethics in Data Science
================

One approach is an entire class, or portion of a class, that covers ethical reasoning, examples are outlined in Lesser and Nordenhaug ([2004](#ref-lesser2004ethical)) and Rochelle E. Tractenberg et al. ([2015](#ref-Tractenberg2015)).

I'm more interested in smaller scale lessons and activities that can be integrated into existing Data Science and Statistical Methods classes. I think there are two obstacles that prevent me from integrating ethics lessons in my own classes:

-   A lack of example lessons or activities that I can remix or adapt for my own classes. For a lesson to be useful to me, it needs clearly articulated pre-requisite knowledge for students, learning objectives and ideas for adapting the lesson to different contexts or levels of mastery. See [Ten Quick Tips for Reviewing Lessons](http://third-bit.com/2019/04/24/reviewing-lessons.html) for other ideas for lesson requirements.

-   Pointers to resources to help me, as a teacher, master the required background so I feel comfortable teaching topics are outside my own training in Statistics and Data Science.

This document is a record of some of my reading around these ideas, and is a work in progress.

A learning trajectory for ethical decision making
-------------------------------------------------

A series of papers by Rochelle Tractenberg and co-authors lay out a set of Knowledge, Skills and Abilities (KSAs) required for ethical decision making, with particular emphasis on responsible research and statistical practice.

The KSAs are attractive because they are, in the authors words, **learnable** and **improvable**. They therefore provide a good starting point for defining specific learning objectives for lessons and mastery goals for students.

-   Rochelle E Tractenberg and FitzGerald ([2012](#ref-tractenberg2012mastery)) defines the six KSAs along with indicators that identify varying degrees of mastery of each KSA. This paper uses Responsible Conduct of Research as defined by the NIH Office of Research Integrity to provide particular content areas for application and demonstration of the KSAs, which may be less relevant to undergraduate students in Data Science.

    **Table 1** crosses the six KSAs with the levels of mastery (Novice, Beginner, Competent and Proficient). It's particularly useful to look at the novice level (perhaps as appropriate for students in an Intro to Data Science course) and the master level (as a guide for what I should know as a teacher, although I feel nowhere near this level).

    **Table 2** crosses the six KSAs with opportunities in conventional academic training for demonstrating the levels of mastery, as an argument that most current opportunities fail to give address many of the KSAs and tend to focus on the early parts of the learning trajectory. Georgetown Univeristy is the specific example, but I suspect this pattern is common to many universities.

    **Table 3** crosses specific topics in RCR (e.g. Safe lab practices, Collaborative research, Peer review) with ways a practicioner may demonstrte them over their career from undergraduate to senior faculty.

-   Rochelle E. Tractenberg ([2013](#ref-tractenberg2013ethical)) takes the same KSAs but uses the American Statistical Association's Ethical Guidelines as content areas.

    **Table A1** crosses the KSAs with the ASA Ethical guideline areas at the Novice level, providing questions that might prompt answers that demonstrate attainment of this level.

    The ASA's guidelines have been updated since this paper, so check they translate to the current guidelines.

The KSA's certainly help provide a framework for thinking about what students need to master and how their mastery develops, (and, for instance, helped me understand gaps in my mastery), but details of specific lessons aren't given, nor where to go to fill in your own gaps in the KSAs.

Decision making frameworks
--------------------------

-   Trevino and Nelson ([2016](#ref-trevino2016managing), chap. 2) *Deciding What's Right: A Prescriptive Approach* "offers decision making tools" for ethical decisions. They start with an overview of three philosophical frameworks (consequentialist theories, deontological theories, and virtue ethics) before presenting an eight step procedure to integrate them into making an ethical decision.

    One of the more accessible summaries of the philosophical frameworks I've read. The "eight step procedure" might be a useful roadmap for students to follow as an activity with a relevant case study.

    Includes an good exercise to help students elicit their own personal values.

    The eight steps include:

    -   Gather the facts
    -   Define the ethical issues
    -   Identify affected parties
    -   Identify the consequences
    -   Identify obligations
    -   Consider your character and integrity
    -   Think creatively about potential actions
    -   Check your gut

-   The Appendix in Lesser and Nordenhaug ([2004](#ref-lesser2004ethical)) provides some background on Kantian, Utilitarian and Virtue Ethics.

-   The [Markkula Center for Applied Ethics](https://www.scu.edu/ethics/ethics-resources/ethical-decision-making/) provides some resources for ethical decision making. In particular, their [framework for ethical decision making](https://www.scu.edu/ethics/ethics-resources/ethical-decision-making/a-framework-for-ethical-decision-making/) outlines five sources of ethical standards (utilitarian, rights, justice, common good and virtue) and an process to integrate them into a decision making process.

    I particularly like the questions they use to provoke thinking from each of the five standards, e.g. "Which option will produce the most good and do the least harm? (The Utilitarian Approach)"

Resources for lessons relevant to statistics and/or data science
----------------------------------------------------------------

-   Baumer, Kaplan, and Horton ([2017](#ref-baumer2017modern), chap. 6, pp. 131--146) *Professional Ethics* provides some short cases relevant to Data Science designed to raise ethical questions. The cases are relevant and current. While they do give some useful ethical "precepts" (draw on professional standards, be open and honest, responsibilities to stakeholders), they do not outline any framework for evaluating ethical decisions and/or handling conflicting ethical recommendations.

    Relevant, interesting case ideas in the exercises section of this chapter.

    I need to check out the "further resources" mentioned at the end of the chapter.

-   Lesser and Nordenhaug ([2004](#ref-lesser2004ethical)) outlines a module of statistical ethics. I really like that is is first framed with a discussion of Kantian and Utilitarian ethics, before using these frameworks to analyse decisions in statistics. For example, nice example in clinical trials:

    -   "prioritizing the greater good over the welfare of a trial's individual subjects is clearly a utilitarian idea".

    -   "(in the spirit of rule-utilitarianism if not Kantianism) that there are certain experiments that should never be run on an individual, no matter how big the benefit for how many other people"

Ethical Behaviour
-----------------

It's not enough to know what is right, you need to **do** what is right.

-   Prentice ([2014](#ref-prentice2018)) presents an outline of six classes on behavioural ethics, or why good people do bad things. Good collection of examples of studies that have demonstrated various psychological factors that affect decision making, see Class 4 for e.g. "conformity bias", "obedience to authority".

    Class \#6 "How you can be your best self" gives specific ideas for how to help people act on their values, in particular recommending the "Giving Voice to Values" curriculum.

Ideas for lessons or activities
-------------------------------

-   Trevino and Nelson ([2016](#ref-trevino2016managing), chap. 2, pp. 50--51) present a *hippocratic oath for managers* and ask whether you can you identify the consequentialist thinking, deontological thinking and virtue ethics thinking. Perhaps after presenting these theories this exercise could be conducted with some parts of the ASA guidelines (American Statistical Association [2018](#ref-asa-guidelines)).

-   Using a case study built around one of the ASA guidelines, provide some alternative actions and ask the questions from the "Evaluate Alternative Actions" step in the [Markkula Center's for Applied Ethics framework for ethical decision making](https://www.scu.edu/ethics/ethics-resources/ethical-decision-making/a-framework-for-ethical-decision-making/). Can student's choose (and justify) an action?

Bibliography
============

American Statistical Association. 2018. “Ethical Guidelines for Statistical Practice.” <https://www.amstat.org/ASA/Your-Career/Ethical-Guidelines-for-Statistical-Practice.aspx>.

Baumer, Benjamin S, Daniel T Kaplan, and Nicholas J Horton. 2017. *Modern Data Science with R*. CRC Press.

Lesser, Lawrence M, and Erik Nordenhaug. 2004. “Ethical Statistics and Statistical Ethics: Making an Interdisciplinary Module.” *Journal of Statistics Education* 12 (3). Taylor & Francis.

Prentice, Robert. 2014. “Teaching Behavioral Ethics.” *Journal of Legal Studies Education* 31 (2): 325–65. doi:[10.1111/jlse.12018](https://doi.org/10.1111/jlse.12018).

Tractenberg, Rochelle E, and Kevin T FitzGerald. 2012. “A Mastery Rubric for the Design and Evaluation of an Institutional Curriculum in the Responsible Conduct of Research.” *Assessment & Evaluation in Higher Education* 37 (8). Taylor & Francis: 1003–21.

Tractenberg, Rochelle E. 2013. “Ethical Reasoning for Quantitative Scientists: A Mastery Rubric for Developmental Trajectories, Professional Identity, and Portfolios That Document Both.” In *Proceedings of the 2013 Joint Statistical Meetings, Montreal, Quebec, Canada*.

Tractenberg, Rochelle E., Andrew J. Russell, Gregory J. Morgan, Kevin T. FitzGerald, Jeff Collmann, Lee Vinsel, Michael Steinmann, and Lisa M. Dolling. 2015. “Using Ethical Reasoning to Amplify the Reach and Resonance of Professional Codes of Conduct in Training Big Data Scientists.” *Science and Engineering Ethics* 21 (6): 1485–1507. doi:[10.1007/s11948-014-9613-1](https://doi.org/10.1007/s11948-014-9613-1).

Trevino, Linda K, and Katherine A Nelson. 2016. *Managing Business Ethics: Straight Talk About How to Do It Right*. John Wiley & Sons.
