A collection of files for large multi-chapter documents like Ph.D. theses.  
(Includes the UIUC thesis class as an example.)

Inspired by:
http://www.tex.ac.uk/cgi-bin/texfaq2html?label=extref 
http://jevopi.blogspot.com/2009/07/how-to-write-very-long-documents-with.html

With that out of the way, here are some instructions/notes.

!!!!BUILD thesis.tex FIRST!!!!
The first thing you must do is build 'thesis.tex'.  The individual chapter files 
rely on the aux files from the other chapters.  To build individual chapters 
later, you must build 'thesis.tex' first.
!!!!BUILD thesis.tex FIRST!!!!


*  This package uses the uiucthesis class.  Update the version that is included 
   if the thesis requirements change.  (This version is good as of 9/6/2011.)
*  With this package you can build any chapter individually or the whole thesis.
*  If you build each chapter (and use bibtex) it will build the references for 
   just that chapter. 
*  The page numbers will be correct across chapters.
*  Cross-chapter references work correctly.
*  In each chapter, you can put a todo list and an outline at the beginning, I 
   found this to be useful.
*  It is set up to use draft mode right now, there is a line you can comment out 
   for the final version.
*  The figure folders are there and included automatically, use them if you    
   want.  Obviously I recommend it.

Feel free to contact me at russell.j.hewett at gmail dot com if you have any 
questions or suggestions.
