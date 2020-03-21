---
layout: default
title: "Author Information"
---

## `acmart` Format

<!-- (BCP) Lots of stuff out of date here!  I propose to just delete it and tell people to look at the submission instructions for each conference. -->

<!-- (AF) Agreed, specially since there is no uniformity across conferences. -->

ACM commissioned the construction of a [Master Article
Template](http://www.acm.org/publications/proceedings-template) that
consolidates all previous ACM journal and proceedings formats
(including SIGPLAN's legacy [`sigplanconf` format](/Resources/LaTeXClassFile)) and
is designed to enable a uniform production workflow for authors and
publishers.  The `acmart` format includes a number of sub-formats, two
of which are relevant to SIGPLAN authors:

 * `acmsmall` sub-format: a one-column format used by papers published
   as an issue of [PACM on Programming Languages
   (PACMPL)](http://pacmpl.acm.org)

 * `sigplan` sub-format: a two-column format used by papers published
   as traditional SIGPLAN proceedings

ACM provides [technical
support](http://www.acm.org/publications/proceedings-template#h-technical-support)
for authors working with the `acmart` format.  General comments and
problems about the `acmart` format may be communicated through the
SIGPLAN [Information
Director](mailto:infodir_sigplan@acm.org?subject=ACM%20acmart%20format).

### LaTeX class, bibliography style, and template files

For LaTeX users, the [PACMPL package
(`acmart-pacmpl.zip`)](/sites/default/files/acmart/current/acmart-pacmpl.zip)
and [SIGPLAN proceedings package
(`acmart-sigplanproc.zip`)](/sites/default/files/acmart/current/acmart-sigplanproc.zip)
are light-weight packages that include only the essential files for an
author:

 * [PACMPL template (`acmart-pacmpl-template.tex`)](/sites/default/files/acmart/current/acmart-pacmpl-template.tex)  
   or [SIGPLAN proceedings template (`acmart-sigplanproc-template.tex`)](/sites/default/files/acmart/current/acmart-sigplanproc-template.tex)
 * [class file (`acmart.cls`)](/sites/default/files/acmart/current/acmart.cls)
 * [class file documentation (`acmart.pdf`)](/sites/default/files/acmart/current/acmart.pdf)
 * [bibliography style file (`ACM-Reference-Format.bst`)](/sites/default/files/acmart/current/ACM-Reference-Format.bst)

The `acmart` format is also available from ACM's [Master Article
Template](http://www.acm.org/publications/proceedings-template) page
and as a [CTAN package](http://ctan.org/pkg/acmart) (and is
distributed with most popular TeX distributions).  However, these are
heavy-weight packages, including the documented LaTeX (`.dtx`) file,
samples of all of the different sub-formats, and bibliography and
image files used by the samples, that most authors won't want or need.
The [PACMPL template
(`acmart-pacmpl-template.tex`)](/sites/default/files/acmart/current/acmart-pacmpl-template.tex)
and [SIGPLAN proceedings template
(`acmart-sigplanproc-template.tex`)](/sites/default/files/acmart/current/acmart-sigplanproc-template.tex)
are not distributed in the heavy-weight packages; authors are
encouraged to use the templates if they obtain the `acmart` format via
the heavy-weight packages (or through their TeX distribution).

The `review` option is strongly encouraged, but not required, for
submissions. (The `review` option will add line numbers, which make it
easier for reviewers to reference specific parts of the paper in their
comments, but should have absolutely no other effect on the
typesetting.)

### Word templates

For Word users, the `acmart` format is available from ACM's [Master
Article
Template](http://www.acm.org/publications/proceedings-template) page.

- - -

{% comment %}

## SIGPLAN Proceedings Format

The [SIGPLAN Proceedings Format](/Resources/ProceedingsFormat) page
summarizes the formatting guidelines for ACM SIGPLAN Proceedings.  The
goal is to ensure that proceedings have a consistent, high-quality
appearance.

{% endcomment %}

## PACMPL

If you are publishing in PACMPL, please see its [Author Guidelines](https://dl.acm.org/journal/pacmpl/author-guidelines).

## Republication Policy

Please review SIGPLAN's
[republication policy](/Resources/Policies/Republication).

## ACM Author Rights

* [ACM Information for Authors: Author Rights & FAQs](http://authors.acm.org/main.html)
* [ACM Author Rights & Publishing Policy](http://www.acm.org/publications/policies/copyright_policy) 
* [New Options for ACM Authors to Manage Rights and Permissions](http://www.acm.org/news/featured/author-rights-management)
* [Using/Including 3rd Party Material & Permissions](http://www.acm.org/publications/third-party-material)

## Writing

If you would like some advice on how to write submissions, here are
some suggestions by

-   Derek Dreyer:
    [How to Write Papers So People Can Read Them](https://www.youtube.com/watch?v=L_6xoMjFr70)
-   Simon Peyton Jones:
    [How to write a good research paper, give a good research talk, and write a good grant proposal](http://research.microsoft.com/~simonpj/papers/giving-a-talk/giving-a-talk.htm)
-   Donald E. Knuth, Tracy Larrabee and Paul M. Roberts:
    [Mathematical Writing](http://tex.loria.fr/typographie/mathwriting.pdf)
-   Mary-Claire van Leunen and Richard Lipton:
    [How to Have Your Abstract Rejected](/Resources/Advice/VanLeunen-Lipton)
-   William Pugh:
    [Advice to Authors of Extended Abstracts](/Resources/Advice/Pugh)
-   Mark Wegman:
    [What it's like to be a POPL referee; or how to write an extended abstract so that it is more likely to be accepted](http://doi.acm.org/10.1145/14947.14955)
-   P. R. Halmos:
    [How to Write Mathematics](http://www.stat.rice.edu/~riedi/Halmos.html)
-   Joel E. Cohen:
    [To A Young Scientist](/Resources/Advice/Cohen)

## Additional Support

Are you a student needing additional support to present your paper
at the conference? The SIGPLAN
**[Professional Activities Committee (PAC)](/PAC)** can help you.
