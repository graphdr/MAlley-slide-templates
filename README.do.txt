======= MichaelAlley-slides-styles =======

This repository contains slide templates for Michael Alley's famous
*assertion-evidence* slide style design. This effective slide design
is described in the book "The Craft of Scientific Presentations: Critical Steps to Succeed and Critical Errors to Avoid": "http://www.amazon.com/Craft-Scientific-Presentations-Critical-Succeed/dp/1441982787/ref=sr_1_fkmr0_1?ie=UTF8&qid=1428766493&sr=8-1-fkmr0&keywords=the+cract+of+scientific+presentations", by Michael Alley, Springer, 2nd edition, 2013.

FIGURE: [doconce/fig-talk/Craft_of_Scientific_Presentations_2nd_cover, width=150]

!bquote
Simply copy the slide template for the slide format you want to use,
give the file a proper name, and fill in your own content.
!equote

===== Template contents =====

The slide templates contains styles for

  * title slide
  * mapping slide
  * the common assertion-evidence slide
  * summary slide

===== Slide formats =====

The slide template comes in several formats:

 * "PowerPoint": "https://github.com/hplgit/MAlley-slide-templates/tree/master/PowerPoint", "download to local viewing": "https://github.com/hplgit/MAlley-slide-templates/raw/master/PowerPoint/AE_presentation_template.ppt"
 * "LibreOffice": "https://github.com/hplgit/MAlley-slide-templates/tree/master/LibreOffice", "download for local viewing": "https://github.com/hplgit/MAlley-slide-templates/raw/master/LibreOffice/AE_presentation_template.odp"
 * "Google Presenter": "https://github.com/hplgit/MAlley-slide-templates/tree/master/Google%20Presenter", "download": "https://raw.githubusercontent.com/hplgit/MAlley-slide-templates/master/Google%20Presenter/AE_presentation_template.gslides"
 * "HTML5 reveal.js": "https://github.com/hplgit/MAlley-slide-templates/blob/master/html5/AE_presentation_template-reveal-white.html": "view": "http://hplgit.github.io/MAlley-slide-templates/html5/AE_presentation_template-reveal-white.html"
 * "HTML5 deck.js": "https://github.com/hplgit/MAlley-slide-templates/blob/master/html5/AE_presentation_template-deck-beige.html", "view": "http://hplgit.github.io/MAlley-slide-templates/html5/AE_presentation_template-deck-beige.html"
 * "LaTeX Beamer slides": "https://github.com/hplgit/MAlley-slide-templates/blob/master/beamer/AE_presentation_template-beamer.pdf", "view": "http://hplgit.github.io/MAlley-slide-templates/beamer/AE_presentation_template-beamer.pdf"
 * "Remark slides": "https://github.com/hplgit/MAlley-slide-templates/blob/master/html/AE_presentation_template-remark.html", "view": "http://hplgit.github.io/MAlley-slide-templates/html/AE_presentation_template-remark.html"
 * "Plain HTML slides, solarized colors": "https://github.com/hplgit/MAlley-slide-templates/blob/master/html/AE_presentation_template-solarized.html", "view": "http://hplgit.github.io/MAlley-slide-templates/html/AE_presentation_template-solarized.html"

===== Brief description of formats =====

=== Interactive slide tools ===

Interactive slides tools offer a graphical user interface to design slides
in a visual way - you click and drag until you are satisfied. This is
user-friendly, and if slide elements are not perfectly postioned, it is easy
to graphically move them the way you want.

For slides with much mathematics and computer code, the support in interactive
tools is modest. There are LaTeX-based equation editors for PowerPoint and
LibreOffce, but they are tedious to use for large amounts of formulas.
Another solution is to convert each formula to an online picture using
URL: "http://www.codecogs.com/latex/eqneditor.php". Here you can copy
and paste existing formulas from LaTeX documents.
Computer code is not well supported in interactive tools.
Syntax highlighting is impossible and you are left with setting the
code in monospace font. Consequently, slides with much mathemtics and
computer code look better in markup languages like LaTeX/Beamer,
HTML5, or Remark.

Tools for interactive slide design include "Microsoft PowerPoint": "http://en.wikipedia.org/wiki/Microsoft_PowerPoint", Apple's "Keynote":, and
"Google Presenter": "http://computers.tutsplus.com/tutorials/getting-started-with-google-slides--cms-21359" (Google slides). The latter is very easy to
use and features tools for online collaboration, though PowerPoint and Keynote
are technically more advanced tools than Google Presenter.

MOVIE: [https://www.youtube.com/watch?v=RrpjzquqUIo] Google presentation tutorial

=== Markup-based slide tools ===

Slides can alternatively be designed using a markup language, usually
"LaTeX": "http://en.wikipedia.org/wiki/LaTeX", "HTML": "http://en.wikipedia.org/wiki/HTML", "Markdown": "http://en.wikipedia.org/wiki/Markdown", or "DocOnce": "http://hplgit.github.io/doconce/doc/web/index.html".
Instead of (e.g.) clicking on an italic button
to get italic text, one writes in plain text `<em>some text</em>` in HTML,
`\emph{some text}` in LaTeX, or
`*some text*` in Markdown and DocOnce. The whole slide presentation is a plain
text file with instructions. A main problem with markup languges is that you
have much less control of where slide elements appear on the slide compared
with the interactive, visual tools. However, markup languages have many
advantages:

 * excellent support for mathematics and computer code
 * sometimes quicker writing (especially Markdown and DocOnce)
 * easy to generate slides from text (papers, books)
 * easy to change notation, terms, etc. in a large set of slides

For at least two decades, "LaTeX/Beamer":
"http://en.wikipedia.org/wiki/Beamer_(LaTeX)" has been a dominating
tool for writing slides with mathematics and computer code. Recently,
LaTeX/Beamer has experienced considerable competition from
"reveal.js": "http://lab.hakim.se/reveal-js/#/" and to some extent
"deck.js": "http://imakewebthings.com/deck.js/". Both these tools are
based on modern HTML5 and CSS technology and combines in some way the
strength for mathematics and computer code from LaTeX/Beamer with the
visual appearance of PowerPoint, Keynote, and Google Presenter.
Especially in more mathematically or computer science oriented
communities, there is significant use of LaTeX/Beamer and reveal.js,
with the Markdown-based Remark tool as a new interesting alternative
coming up (Markdown-based tools are gaining increasing popularity in
general).