# A Excel VBA implementation of a Zwicky Box - DRAFT
*(note: I have used the README from https://github.com/sgrubsmyon/morphr/blob/master/README.md as template for writing my first README).*

This package provides an interactive graphical representation of a morphological field, a.k.a. morphological box, or "Zwicky box", see [1], [2], [3]. A morphological field is a tabular representation where each parameter of the problem corresponds to a row whose columns are filled with the variables of the parameter.

Frequently each variable is mutually checked for consistency with all other parameter values. This is NOT done here because we are interested in not excluding avribels due to how familiar they are. Instead this package genertes a list of all the combinations and enables you to systemtically remove (by checking the check box) those which you consider impossible, it also allows you to exclude the blindingly obvious options too. By combining these two ways of eliminating the combinations therefore greatly reduce the problem space. But by  only elimating the impossble and obvious you are more likely to find the interesting combinations. 

Morphological Analysis (MA)--- should not to be confused with morphology in linguistics, biology or image processing---is a structured method for exploring and constraining a complex multi-dimensional, possibly non-quantifiable, problem space. MA was developed by the astrophysicist Fritz Zwicky (e.g. [4], [5], [6], [7]) and is since the mid-1990s advanced and applied by the Swedish Morphological Society, in particular by Tom Ritchey et al., under the term "General Morphological Analysis" (e.g. [8], [9]).

The purpose of this package is to provide simple Morphological Analysis into an excel tool as a stepping stone to me producing a more accessible online Python based tool. hopefully this early iteration will encourage more widespread usage ofthese tools for structured scientific problem solving and decision making.

Please note that Morphological Analysis as a scientific method is not trademarked or even copyrightable. The Swedish Morphological Society write on their website:

*The term and the procedures embodied in "morphological analysis" are not trademarked or copyrighted. Morphological analysis is a basic scientific method, and is therefore no more copyrightable than "mathematical analysis" or "statistical analysis".*

-- *Swedish Morphological Society*

The code of this package is publicly available and released under the GPL-3 (GNU GENERAL PUBLIC LICENSE version 3). It is built upon RStudio's DT package, which is distributed under the same license.

[1]: https://en.wikipedia.org/wiki/Morphological_analysis_%28problem-solving%29
[2]: https://en.wikipedia.org/wiki/Morphological_box
[3]: https://de.wikipedia.org/wiki/Morphologische_Analyse_(Kreativit%C3%A4tstechnik)
[4]: Zwicky, F. (1947). Morphology and nomenclature of jet engines. Aeronautical Engineering Review, Vol. 6, No. 6, pp. 49--50.
[5]: Zwicky, F. (1948). Morphological astronomy. Observatory, Vol. 68, No 845, pp. 121--143.
[6]: Zwicky, F. & Wilson, A. (Eds.) (1967). New methods of thought and procedure: Contributions to the symposium on methodologies. Berlin: Springer.
[7]: Zwicky, F. (1969). Discovery, invention, research -- through the morphological approach. New York: The MacMillan Company.
[8]: General Morphological Analysis - A general method for non-quantified modeling, Swedish Morphological Society, 2002 (Revised 2013), Licensed under a Creative Commons Attribution
[9]: Ritchey, T. (2011). Wicked Problems -- Social Messes, Decision Support Modelling with Morphological Analaysis, Volume 17 of the series Risk, Governane and Society, Springer-Verlag Berlin Heidelberg.

# Lecture

A lecture set of lecture notes explaining how I use MA for my work can be found here {insert link}

#Example

Screen shot of instructions

Screen shot of input screen

Screen shot of first table

Screen shot of final table and options e.g. PRINT



#Contact info
This package is authored and maintained by Jim Maltby (maltbyjim@gmail.com). Feel free to contact me if you want any advice or help.
