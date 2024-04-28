# [atet](https://github.com/atet) / [**_cite_**](https://github.com/atet/cite/blob/main/README.md#atet--cite)

[![.img/logo_cite.png](.img/logo_cite.png)](#nolink)

# Collected Citations and References

This is my personal repository of useful information from around the world.

----------------------------------------------------------------------------

## Table of Contents

* [0. Introduction](#0-introduction)
* [1. Science](#1-science)
* [2. Technology](#2-technology)
* [3. Engineering](#3-engineering)
* [4. Arts](#4-arts)
* [5. Mathematics](#5-mathematics)
* [6. Business](#6-business)
* [7. Quotes](#7-quotes)

### Supplemental

* [Other Resources](#other-resources)
* [Troubleshooting](#troubleshooting)

----------------------------------------------------------------------------

## 0. Introduction

### References and Citations

This repository will use the **Chicago Manual of Style** (CMOS)[<sup>1</sup>](#other-resources) **Notes and Bibliography System** (NB).[<sup>2</sup>](#other-resources)

As an example, a document or presentation (now refered to as a work) will utilize the CMOS NB system by marking citations with a superscript number (e.g., <sup>"123"</sup>) that corresponds to a note (i.e., a full citation) detailed in the footnotes or bottom section of a work.

The superscript number must be immediately after the text in which the source was referenced (after punctuation) or after the period if it concludes a sentence:

> Current electric vehicle charging infrastructure will fully mature in less than five years according to Gartner.<sup>1</sup> Mercedes-Benz is contributing to this ecosystem by partnering with existing networks,<sup>2</sup> as well as creating their own charging infrastructure.<sup>3</sup> John Doe mentions, "Collectively, this collaborative momentum from automakers and supporting industries will realize Gartner's prediction in the near future,"<sup>4</sup> and may position Mercedes-Benz well given its investments in this space.

Lastly, a bibliography page or slide must conclude the work with a full citation. 

The following are rules for **notes**:
* Numbering of the citation superscripts are consecutive throughout the work and does not restart on the next page or slide
* Each piece of information that is referenced must have a corresponding footnote, even if the same source is referenced multiple times nonconsecutively in the same page or slide
* In the event of the same source being referenced multiple times in the same page or slide, the subsequent citation(s) could be shortened:
    * First note:
    
        `32. William A. Sahlman, “How to Write a Great Business Plan,” Harvard Business Review 75,July–August 1997, 103.`
    
    * Subsequent shortened note(s):
    
        `33. Sahlman, “Great Business Plan,” 103.`

The following are rules for the **bibliography**:
* Full notes are used with only a unique entry for each source
* Entries are arranged alphabetically regardless of the order of sources referenced in the preceding body of work
* Formatting:
    * The title "Bibliography" should be centered at the top of only the first page or slide of the bibliography section, followed by two blank lines before the first entry
    * Page or slide numbering must continue consecutively on the top right corner of the page or slide
    * If the title starts with a number, write the number as a word
    * Entries are single-spaced with one extra line between entries
    * Use hanging indents
    * Use the word "and" instead of the symbol "&"
    * For sources from the internet, use the Digital Object Identifier (DOI) instead of a URL if possible (since it may be very long)

**Journal Article**
* **Note Format**:
    * `<NOTE NUMBER>. <FIRST NAME> <LAST NAME>, "<TITLE OF ARTICLE>," <NAME OF JOURNAL> <VOLUME>, no. <ISSUE> (<MONTH/SEASON YEAR>): <PAGE RANGE>. <DOI or URL>.`
    * **Example**:
    * `1. Susan Satterfield, “Livy and the Pax Deum,” Classical Philology 111, no. 2 (April 2016): 170. https://doi.org/10.1086/686236.`
* **Shortened Note Format**:
    * `<NOTE NUMBER>. <LAST NAME>, "<SHORTENED TITLE OF ARTICLE>," <PAGE RANGE>.`
    * **Example**:
    * `2. Satterfield, “Livy,” 172–73.`
* **Bibliography Format**:
    * `<LAST NAME>, <FIRST NAME>. "<TITLE OF ARTICLE>." <NAME OF JOURNAL> <VOLUME>, no. <ISSUE> (<MONTH/SEASON YEAR>): <PAGE RANGE>. <DOI OR URL>.`
    * **Example**:
    * `Satterfield, Susan. “Livy and the Pax Deum.” Classical Philology 111, no. 2 (April 2016): 165–76. https://doi.org/10.1086/686236.`
* **Caveat**: If there are more than four authors (typical of academic journals), use *et al.* only in the notes and the full author list in the bibliography
    * `3. Rachel A. Bay et al., ...`
    * `4. Bay et al., ...`

**Website Content (Author Known)**
* **Note Format**:
    * `<NOTE NUMBER>. <FIRST NAME> <LAST NAME>, "<TITLE OF WORK>," <TITLE OF SECTION OR WEBSITE OWNER>, <DATE OF PUBLICATION, REVISION, OR ACCESS>. <URL>.`
    * **Example**:
    * `1. Athit Kao, “Collected Citations and References,” GitHub repository atet/cite, accessed on April 28, 2024, https://github.com/atet/cite.`
* **Shortened Note Format**:
    * `<NOTE NUMBER>. <LAST NAME>, "<SHORTENED TITLE OF WORK>."`
    * **Example**:
    * `2. Kao, “Cite.”`
* **Bibliography Format**:
    * `<LAST NAME>, <FIRST NAME>. "<TITLE OF WORK>." <TITLE OF SECTION OR WEBSITE OWNER>. <DATE OF PUBLICATION, REVISION, OR ACCESS>. <URL>.`
    * **Example**:
    * `Kao, Athit. “Collected Citations and References.” GitHub repository atet/cite. Accessed on April 28, 2024. https://github.com/atet/cite.`

**Website Content (No Author)**
* **Note Format**:
    * `<NOTE NUMBER>. "<TITLE OF WORK>," <TITLE OF SECTION>, <COMPANY>, <DATE OF PUBLICATION, REVISION, OR ACCESS>. <URL>.`
    * **Example**:
    * `1. “Privacy Policy,” Privacy & Terms, Google, last modified April 17, 2017, https://www.google.com/policies/privacy.`
* **Shortened Note Format**:
    * `<COMPANY>, "<SHORTENED TITLE OF WORK>."`
    * **Example**:
    * `2. Google, “Privacy Policy.”`
* **Bibliography Format**:
    * `<COMPANY>. "<TITLE OF WORK>." <TITLE OF SECTION>. <DATE OF PUBLICATION, REVISION, OR ACCESS>. <URL>.`
    * **Example**:
    * `Google. “Privacy Policy.” Privacy & Terms. Last modified April 17, 2017. https://www.google.com/policies/privacy.`

### Artificial Intelligence Content

Recent guidance by the Chicago Manual of Style regarding content from large language models (LLMs) like ChatGPT are that these LLM technologies, colloquially known as "artificial intelligence" (AI), must be acknowledged if used as a source of information.[<sup>3</sup>](#other-resources)

There are multiple scenarios with differing guidance for reference and citation format. Since this repository will display all AI-generated content for public reference, the following format will be used:

**Publicly Available AI Content**
* **Note Format**:
    * `<NOTE NUMBER>. Text generated by <LLM>, <COMPANY>, <DATE OF ACCESS>, <URL IF APPLICABLE>`
    * **Example**:
    * `1. Text generated by Claude, Anthropic, January 23, 2024, https://github.com/atet/cite/blob/main/.dat/business/20240123_Identifying_Additional_Business_Stakeholders_Beyond_the_Typical_Five.md`
* **Shortened Note Format†**:
    * `<LLM>, <DATE OF ACCESS>.`
    * **Example**:
    * `2. Claude, January 23, 2024`
* **Bibliography Format†**:
    * `<COMPANY>. Text generated by <LLM>, <DATE OF ACCESS>. <URL IF APPLICABLE>.`
    * **Example**:
    * `Anthropic. Text generated by Claude, January 23, 2024. https://github.com/atet/cite/blob/main/.dat/business/20240123_Identifying_Additional_Business_Stakeholders_Beyond_the_Typical_Five.md`

†Specific guidance was not given by CMOS for shortened note or bibliography formats.

### Boston University Academic Conduct Code

Boston University's Questrom School of Business permits AI-generated content to be used as a source of information with proper acknowledgement (Figure 1). **This repository will serve as a public reference for all AI-generated content cited by Athit Kao**.

##### **Figure 1. Excerpts from Boston University's Academic Conduct Code specifically referencing the use of AI-generated information.[<sup>4</sup>](#other-resources)**

> **Academic Conduct Code**
> 
> . . .
> 
> Boston University’s Academic Conduct Code is designed to assist in the development of a supportive and productive learning environment. It is both a description of the University’s ethical expectations of students as well as a guarantee of students’ rights and responsibilities as members of a learning community. The Code provides clarity related to policy and procedure regarding academic conduct.
>
> Effective January 1, 2024. This policy applies to all students except the following, who should refer to their academic conduct codes: School of Law students and MD students in the Chobanian & Avedisian School of Medicine.
>
> . . .
>
> III. Violations of this Code
>
> . . .
>
> B. Plagiarism. Representing the work or ideas of another* as one’s own and/or using another’s work or ideas without appropriately crediting the source. Plagiarism includes, but is not limited to, the following: copying the answers of another student on an examination; copying or **restating the work or ideas of another person/persons or artificial intelligence software** in any oral or written work (printed or electronic) **without appropriately citing the source**; using visuals, audio, or video footage that comes from another source (including work done by another student) without permission and/or acknowledgement of that source; and collaborating with someone else in an academic endeavor without acknowledging their contribution. Plagiarism can consist of acts of commission (appropriating the words or ideas of another as one’s own), or omission (failing to acknowledge/document/credit the source or creator of words or ideas).
>
> *“Another” may refer to **anything that can be a source of information** or work product, including (but not limited to) individuals, books, online sources, academic journals, and **software/programs (e.g., artificial intelligence software/programs)**.
>
> . . .

</br>

Additionally, the official perspective of Boston University on this subject confirms that LLMs are permitted as a source of information that can be used on student assignments:

> [![.img/quote_left.png](.img/quote_left.png)](#nolink) *Using ChatGPT as a **means of research to find some preliminary information (like a Google search) is okay**. However, we do not want students taking content straight from ChatGPT and putting it in a paper as opposed to writing their own content.* [![.img/quote_right.png](.img/quote_right.png)](#nolink)
>
> — Boston University Learning Facilitator —
>
> ###### Unpublished quote from correspondence with a Boston University Learning Facilitator on January 25, 2024.

</br>

Though not required by Questrom, reasonable due diligence will be performed to ensure that content in this repository is logical and factually correct before being considered as a source. All information is provided here according to the following <a href="http://www.athitkao.com/tos.html" target="_blank">Terms and Conditions</a>.</p>

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## 1. Science

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## 2. Technology

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## 3. Engineering

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## 4. Arts

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## 5. Mathematics

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## 6. Business

* [20240123 - Identifying Additional Business Stakeholders Beyond the Typical Five](./.dat/business/20240123_Identifying_Additional_Business_Stakeholders_Beyond_the_Typical_Five.md)

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## 7. Quotes

<div id="chadwick-boseman-purpose-crosses-disciplines"></div>

> [![.img/quote_left.png](.img/quote_left.png)](#nolink) *Graduating class, hear me well on this day, this day when you have reached the hilltop and you are deciding on next jobs, next steps, careers, further education – you would rather find purpose than a job or a career. **Purpose crosses disciplines**. Purpose is an essential element of you. It is the reason you are on the planet at this particular time in history. Your very existence is wrapped up in the things you are here to fulfill.* [![.img/quote_right.png](.img/quote_right.png)](#nolink)
>
> — Chadwick Boseman —
>
> ###### Quote by [Chadwick Boseman](https://en.wikipedia.org/wiki/Chadwick_Boseman), accomplished actor and Howard University alumnus, at [Howard University's 150<sup>th</sup> Commencement Ceremony on May 12, 2018](https://youtu.be/RIHZypMyQ2s?t=1891).

</br>

<div id="bill-george-purpose-of-mba"></div>

> [![.img/quote_left.png](.img/quote_left.png)](#nolink) *So I think we can rethink the role of leaders at all levels. So we got to get over this idea of the leader as this all powerful CEO, it's not. In fact, great CEOs are much more into empowerment. So I think what we need to do is rethink leadership at all levels and teach people how to lead at all levels. **And then at an MBA level, how do I become a leader of leaders**, not managing leaders, not controlling managers. But how do I learn to become a leader of leaders?* [![.img/quote_right.png](.img/quote_right.png)](#nolink)
>
> — Bill George —
>
> ###### Unpublished quote from [Bill George](https://en.wikipedia.org/wiki/Bill_George_(businessman)), a Senior Fellow at Harvard Business School and former CEO of Medtronic, being interviewed by Venkat Venkatraman, professor at Questrom School of Business, Boston University, on August 18, 2020.

</br>

<div id="david-allen-anything-not-everything"></div>

> [![.img/quote_left.png](.img/quote_left.png)](#nolink) *You can do anything – **but not everything**.* [![.img/quote_right.png](.img/quote_right.png)](#nolink)
>
> — David Allen —
>
> ###### Quote by [David Allen](https://en.wikipedia.org/wiki/David_Allen_(author)), a productivity consultant best know for his time management method, "Getting Things Done," from an [interview by Fast Company on April 30, 2000](https://web.archive.org/web/20120808105202/https:/www.fastcompany.com/40384/you-can-do-anything-not-everything).

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## Other Resources

**Description** | **URL Link**
--- | ---
<sup>1</sup>**Chicago Manual of Style** | https://www.chicagomanualofstyle.org/home.html
<sup>2</sup>**Chicago Manual of Style**: Notes and Bibliography System | https://www.chicagomanualofstyle.org/tools_citationguide/citation-guide-1.html
<sup>3</sup>**Chicago Manual of Style**: Artificial Intelligence Content | https://www.chicagomanualofstyle.org/qanda/data/faq/topics/Documentation/faq0422.html
<sup>4</sup>**Boston University**: Academic Conduct Code | https://www.bu.edu/academics/policies/academic-conduct-code/

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## Troubleshooting

Issue | Solution
--- | ---
***How can I replicate the AI-generated responses seen here?*** | Commercial LLMs are stochastic, meaning they will produce inconsistent and seemingly random results every time they are used.

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

<p align="center">Copyright © 2024-∞ Athit Kao, <a href="http://www.athitkao.com/tos.html" target="_blank">Terms and Conditions</a></p>