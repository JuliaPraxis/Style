# Naming Packages


- Use titlecase
  - :thumbsup: CategoryTheory
  - :thumbsdown:  categorytheory, categoryTheory

- Do not use "Julia" in the package name
  - :thumbsup: CategoryTheory
  - :thumbsdown:  CategoryTheoryForJulia

- Prefer clarity to brevity  
  - :thumbsup: VectorArithmetic
  - :thumbsdown:  VecArith
  
- Prefer specificity to generality  
  - :thumbsup: VectorArithmetic
  - :thumbsdown:  VectorProcessing

- Prefer communication to jargon  
  - :thumbsup: ColorVision
  - :thumbsdown:  TristimulusEncoding

- Prefer plural to singular when packaging a type
  - :thumbsup: ProjectiveReals
  - :thumbsdown:  ProjectiveReal

- Prefer words to acronyms when acronym may confuse
  - :thumbsup: GraphModellingLanguage, ParseHTML
  - :thumbsdown:  GML, ParseHypertextMarkupLanguage

- Write an initial acronym thus:
  - :thumbsup: HtmlParser, HtmlLinkChecking
  - :thumbsdown:  HTMLParser, HTMLparser, HTMLLinkChecking


------  
    
Please see [the manual](http://docs.julialang.org/en/latest/manual/packages/#guidelines-for-naming-a-package).
