# Deedy-Resume

A **one-page**, **two asymmetric column** resume and cover letter template in **XeTeX** that caters particularly to an **undergraduate Computer Science** student.
As of **v1.2**, there is an option to choose from two templates:

1. **MacFonts** - uses fonts native to OSX - _Helvetica_, _Helvetica Neue_ (and it's Light and Ultralight versions) and the CJK fonts _Heiti SC_, and _Heiti TC_. The EULA of these fonts prevents distribution on Open Source.
2. **OpenFonts** - uses free, open-source fonts that resemble the above - _Lato_ (and its various variants) and _Raleway_.

It is licensed under the Apache License 2.0.

## Motivation

Common LaTeX resume-builders such as [**moderncv**](http://www.latextemplates.com/template/moderncv-cv-and-cover-letter) and the [**friggeri-cv**](https://github.com/afriggeri/cv) look great if you're looking for a multi-page resume with numerous citations, but usually imperfect for making a thorough, single-page one. A lot of companies today search resumes based on [keywords](http://www.businessinsider.com/most-big-companies-have-a-tracking-system-that-scans-your-resume-for-keywords-2012-1) but at the same time require/prefer a one-page resume, especially for undergraduates.

This template attempts to **look clean**, highlight **details**, be a **single page**, and allow useful **LaTeX templating**.

## Preview

### OpenFonts

![alt tag](https://raw.githubusercontent.com/deedydas/Deedy-Resume/master/OpenFonts/sample-image.png)
![alt tag](https://raw.githubusercontent.com/anthonyattard/Deedy-Resume/master/OpenFonts/sample-image-cover-letter.png)

### MacFonts

![alt tag](https://raw.githubusercontent.com/deedydas/Deedy-Resume/master/MacFonts/sample-image.png)
![alt tag](https://raw.githubusercontent.com/anthonyattard/Deedy-Resume/master/MacFonts/sample-image-cover-letter.png)

## Dependencies

1. Compiles only with **XeTeX** and required **BibTex** for compiling publications and the .bib filetype.
2. Uses fonts that are usually only available to **Mac** users such as Helvetica Neue Light.

## Generating Resume/Cover Letters

1. Navigate to either MacFonts or OpenFonts depeding on your OS.
2. Generate resume with `xelatex deedy_cover_letter.xtx`
3. Generate cover letters with `xelatex deedy_cover_letter.xtx`
4. Profit

## Availability

1. MacFonts version - [as an online preview](http://debarghyadas.com/resume/debarghya-das-resume.pdf) and [as a direct download](https://github.com/deedydas/Deedy-Resume/raw/master/MacFonts/deedy_resume.pdf)
2. OpenFonts version - [as a direct download](https://github.com/deedydas/Deedy-Resume/raw/master/OpenFonts/deedy_resume-openfont.pdf)
3. **Overleaf**.com (formerly **WriteLatex**.com) (v1 fonts/colors changed) - [compilable online](https://www.writelatex.com/templates/deedy-resume/sqdbztjjghvz#.U2H9Kq1dV18)
4. **ShareLatex**.com (v1 fonts changes) - [compilable online](https://www.sharelatex.com/templates/cv-or-resume/deedy-resume)
