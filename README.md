# rewriting-technical-mathematica
Rewriting the Technical Interview (https://aphyr.com/posts/353-rewriting-the-technical-interview), in Mathematica.

This is nowhere near as neat as the original, and it's much more brittle, but it does the job.

Presented both as .nb and as .txt files (for those who don't fancy parsing M-expressions in their heads).

Note that if you naively copy-paste the C sample from the blog post, you will run into the fact that a few of the semicolons are in fact Greek question marks. My code does not attempt to deal with that in any way; Mathematica's parsing deals with the two characters very differently, and it is surprisingly hard to just do a character replacement using the machinery I've got here.
