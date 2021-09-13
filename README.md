# Capstone
Pre-processing
Prep Test index format:
For the purposes of the LSAT, the typical format of "Prep Test/Section/Question Number as used. e.g. [21.0,02,05] indicates Prep test 21, Section 2, Question 5. Two irregularies exist. First, a decimal was utilized for prep test reference. This would allow for Prep Test exams to remain both in chronological as well as numerical order since six LSAT prep test exams were released periodically throughout the years. See here https://www.powerscore.com/lsat/help/pub_ident.cfm. e.g. "June 2007" was imported as [51.5,01,01] since June 2007 falls chronolically between prep test 51 (Dec 2006) and 52 (Sept 2007).

Second, section numbers 01 and 02 were utilized consistently throughout the data set since the LSAC consistently provided their exams in LG,LR,LR,RC order throught all of their practice exams online, see https://www.lsac.org/lsat/prep#lsatprepplus . Since the official LSAT rotates these sections for different students on test day, the section numbers may not correspond with the actual exam a test taker experienced or that is downloaded from a test provider's website such as https://www.kaplan.com .

Pipe addition and removal from pipeline
Most Python cells within a Jupyter notebook may be run multiple times within the span of running an entire notebook. However, multiple Spacy pipes labeled the same name may not be re-added/overwritten. Therefore, several instances of code to delete pipes are commented throught this project. These instances may be uncommented, run, then commented again to facilitate this process.

Code output review:
Jupyter notebook as a module titled "collapsible headings" which allows code folding based upon Markdown headers. see here https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/collapsible_headings/readme.html . While this is not necessary for the production of this notebook, it helps to view the overall continuity of flow since there are a number of code snippets designed to allow the reviewer a glimps into how the data is being processed and returned. Examples of this non-essential, but helpful code can be found within markdown text titles similar to the following.

"REVIEW sample variable START"

"REVIEW sample variable END"
