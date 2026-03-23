% Project Specification
% Evaluating Historical Text Corpora
% revision of \today

---
mainfont: Junicode
header-includes: |
	  ```{=latex}
	  \usepackage{fullpage}
	  \usepackage[strict]{changepage}
      \newcommand{\hideFromPandoc}[1]{#1}
      \hideFromPandoc{
        \let\Begin\begin
        \let\End\end
	  \definecolor{burgundy}{HTML}{990000}
      }

	  ```
urlcolor: burgundy
---

# Overview

Students of [M.EP.11b](https://flexnow2.uni-goettingen.de/modulbeschreibungen/120930.pdf) are expected to propose and carry out their own corpus research on a premodern or, at the latest, early Modern text corpus (no later than 1667). The requirements consist of a written proposal and an extensively documented notebook demonstrating and discussing your Python code.

## Proposal

The proposal is an ungraded but mandatory prerequisite for proceeding to the assessment stage. It should approximate 750 words in length and is due by email ahead of class on 22 June (sooner is always a good idea). If you haven't started experimenting well before this point in the term, you may not yet know what methods or approaches will prove the most promising, which is all the more reason to begin trying out as many of the approaches demonstrated in the [demo notebooks](https://github.com/langeslag/ehtc/tree/main/demo) on your corpus of choice as soon as you possibly can. See [project suggestions](https://github.com/langeslag/ehtc/blob/main/doc/Project.Suggestions.pdf) for some suggested angles, but by all means feel free to come up with your own original research plan (and/or choose a corpus not mentioned in my documentation).

The proposal should address:

- Your choice of corpus: its definition, where you will source it, and the nature of its encoding (if XML or PSD, what metadata? if HTML or plaintext, what structural units does it encode: [numbered] lines, paragraphs, sections? is it uncorrected OCR or an academic transcription?).
- Your research question or aims.
- Your proposed methods and their ability to answer your research question or realize your aims.
- Any concerns regarding the feasibility of the undertaking or limitations to your approach which you expect may affect the ability of your findings to answer your research question.

Your final project may, of course, extend beyond the methods set out in the proposal, or explore a markedly different direction if the original approach proves to be less fruitful than hoped, or if interim results prompt additional questions.

## Project

You will report on your research in the form of a Jupyter notebook, due by email on 30 September, containing both the code and circa 2,000 words of documentation and reflection in academic prose contained in the notebook's markdown cells. Make sure to save your outputs as part of the notebook (it's usually best to restart the kernel and run through everything once before saving and submitting so the sequence is clear). You don't have to supply the corpus you've used unless you've created or manually modified one yourself, but clearly indicate the source, at least by naming it and its authors and linking to its official web presence. Of course best practice is to include code near the top of the notebook that downloads the corpus if possible.

In terms of documentation, use markdown cells (and/or concise code comments) to explain what you are doing at every step. Most importantly, however, include extended discussion at the start (stating your research aims, introducing your methods, identifying your corpus) and end of your notebook to reflect on your methods and findings.

# Assessment

When finalizing your project for assessment, you would be well advised to consider the following marking grid, which indicates the most important aspects informing your grade, but not their weighting:

Aspect													 1	 2	 3	 4	 5	 6	 7	 8	 9	 10
-------------------------------------------------------	---	---	---	---	---	---	---	---	---	----
Planning and research question
Methodology
Initiative
Code documentation
Demonstrating an understanding of the code
Presentation of findings (visualization, tables, prose)
Discussion/reflection
Awareness of methodological limitations

Table: Marking grid

# Academic Integrity

Plagiarism works a little differently with code. It is common practice to learn from code shared online by others, but if any real copying is involved, please provide a code comment immediately above the borrowed function and provide a deeplink to the forum reply or HTML heading corresponding to where you sourced it.

A reliance on generative models is a more pressing concern. University guidelines effectively force instructors to wave through AI-generated coursework provided it is transparently signposted and does not misrepresent its sources. This means that you are required faithfully to complete, sign, and submit both sides of my [academic integrity form](http://langeslag.uni-goettingen.de/Academic_Integrity.pdf) with your notebook. However, you should also note the line in the marking grid above that indicates I want to see you demonstrate that you have understood your own code. Beyond that, I can only emphasize that you will not learn to code well if you don't do the hard work yourself.
