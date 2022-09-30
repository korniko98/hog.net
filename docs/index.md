# User Guide

<p style="text-align:center;">
<img src="/hog.net/img/banner.png" width="250">
</p>

## Introduction
Welcome to **hog.net**, a beginner-level "Harry Potter" themed querying exercise / detective game / analytical CTF challenge / interactive fanfiction made by [Amitai Cohen](https://twitter.com/AmitaiCo), in which you explore the local network of the Hogwarts School of Witchcraft and Wizardry.

In this exercise, you are tasked with answering research questions by querying the databases available on the local school network:

* **Books.hog.net** – soft copies of select books from the school library
* **Comp.hog.net** – personal computers of hog.net users
* **EOwl.hog.net** – the magical equivalent of email
* **Floochat.hog.net** – instant messaging logs between hog.net users (based on the FLOO protocol)
* **News.hog.net** – news reports and articles from the international wizarding community
* **Users.hog.net** – information about hog.net users

You can watch a demo [here](https://youtu.be/5rrZdS-vb0w) (please enable subtitles / closed captions).

If you're looking for a primer on this sort of querying, please read [this blogpost](https://amitaico.substack.com/p/querying-in-research).

Once you have completed the exercise, you can check your work by revealing the solutions.

If you’d like to contribute to this project or share any feedback, please fill out the [self-assessment and feedback issue template](https://github.com/korniko98/hog.net/issues/new?assignees=&labels=feedback&template=self-assessment-and-feedback-questionnaire.md&title=Self-assessment+and+feedback+questionnaire) on GitHub.

## Instructions

Answer the exercise questions in the next section (it is recommended that you read all questions prior to solving the exercise).

When writing your solutions, be sure to include references in footnotes and use proper estimative language (“probably”, “possibly”, etc.). Here is an example of a well-referenced answer:

### Question #0

What is Dumbledore’s favorite snack?
??? success "Reveal solution"
    ![q0](/hog.net/img/q0.svg)

### Technical Instructions

* To query the databases, click ++s++, ++f++ or ++slash++ to open the search bar, and enter your search terms.
* To search for an intersection of multiple terms, use "+" (e.g. "+ronw +scabbers" will only return items that include both "ronw" and "scabbers").
* To exclude a term from the current query, use "-" (e.g. "ronw -scabbers" will only return items that include "ronw" but not "scabbers").
* To browse the various databases, use the left-hand navigation sidebar.
* To search within the current page, use your browser's built-in search function (++ctrl+f++).
* To copy the location of a certain page (for recording it as a reference in a footnote, for example), use “Copy link address” (when using Chrome).
* To go to a specific page (copied from a reference, for example), navigate to it via your browser's address bar.

## Exercise Questions

### Question #1
What passed by Gryffindor tower?
??? success "Reveal solution"
	![q1](/hog.net/img/q1.svg)
### Question #2
What type of coffee does Hagrid prefer?
??? success "Reveal solution"
	![q2](/hog.net/img/q2.svg)
### Question #3
Where is Ron's lost wand?
??? hint "Need a hint?"
	![h3](/hog.net/img/h3.svg)
??? success "Reveal solution"
	![q3](/hog.net/img/q3.svg)
### Question #4
Complete Hermione’s essay on Muggle Studies (include it in your solution in its entirety).
??? hint "Need a hint?"
	![h4](/hog.net/img/h4.svg)
??? success "Reveal solution"
	![q4](/hog.net/img/q4.svg)
### Question #5
Who broke into a professor's office, and why?
??? hint "Need a hint?"
	![h5](/hog.net/img/h5.svg)
??? success "Reveal solution"
	![q5](/hog.net/img/q5.svg)
### Question #6
Who was walking about barefoot throughout the school, and why?
??? hint "Need a hint?"
	![h6](/hog.net/img/h6.svg)
??? success "Reveal solution"
	![q6](/hog.net/img/q6.svg)

## Sources

Some items in this database are based on material from the following sources:

* [Wizarding World](https://www.wizardingworld.com/)
* [Harry Potter Wiki](https://harrypotter.fandom.com/)
* [Joshua Neil Arthur](https://twitter.com/jnarthur/)
* [Phenomenalia](https://www.etsy.com/shop/Phenomenalia/)
* [The STAC dataset](https://www.irit.fr/STAC/corpus.html)
* ["The Red Hand of Doom" playthrough by Adam Bunnell](https://redhandofdoomnarrative.blogspot.com/)
