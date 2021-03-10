LaTeX-macro
=======

## A list of my macros in LaTeX. Usage for physics papers.

I will write a list of the commands introduced. There are two versions, one for any document and one that follows the formatting of JHEP.
They are respectively included as \usepackage{mymacro} and \usepackage{mymacro-jhep}.

`\Appendices` Starts the appendices. Notice the capital "A" w.r.t. the normal LaTeX command `\appendices`  
`\eqn`, `\eqna` See [chet](https://ctan.org/tex-archive/macros/latex/contrib/chet)  
`\eqnal` Works the same way as `\eqna` but can have equations across pages  
`\titlesfont` It's the default fontfamily assigned to titles (Title, Section, Subsetion, etc...). By default it's cmr  
`\Bibliography[file]` Writes the bibliography taking the .bib file from `file`, by default../Bibliography/biblio  
`\figurename`, `\tablename`, `\eqnname` Names for, respectively, figures, tables and equations to use in the body as refs  
`\sectionname`, `\appendixname` Names for, respectively, sections and appendix to use in the body as refs  
`\author[n]{name}` Represents a single author entry. The `n` is the identifier of the affiliation  
`\affil[n]{name}` Represents the affiliation of the author with identifier `n`  
`\abstract` The abstract  
`\preprint` The CERN preprint number  
`\maketitle` Makes a title page  
`\maketitlesmall` Makes a title only in the header of the first page, for notes
`\ack` Starts the acknowledgments section
`\codein` and `\codeout` write code in the Mathematica input and output style respectively
`\tableeqn` makes equations inside a table environment enlarging the margins appropriately

Some shortcuts are introduced. Here is a partial list  
`\overbar` Better overbar  
`\overbarUp` Better overbar for upright symbols  
Letters α, β, γ have the dotted version as `\alphad`, `\betad`, `\gammad`  
Letters θ, Θ, φ, Φ have the dotted version as `\thetab`, `\phib` ...  
`\rmx` is the roman x  
Some letters have the mathcal version as `\CJ`, `\CO` ...  
Some letters have the double stroke version as `\BBR`, `\BBC` ...  
`\lifrac` Is the fraction as the in line version  
`\benum`, `\eenum` Begin and and an enumerate environment  
`\Hhline` Fat hline  
`?` Fat vertical line in tables (to use as the `|` separators)  
`\Tr` Trace operator  
`\fslash` Feynman slash  
`\mvec` Vector  
`\bvec` Boldface  
`\unit` The identity matrix  
`\hodge` The hodge star  
`\vev{content}`, `\Vev{content}` brackets `content` in angular brackets, respectively small and height matching  
`\sigmau{mu}{alpha}{alphadot}` Pauli sigma with upper mu index  
`\sigmamn{mu}{nu}{alpha}{beta}`, `\sigmabmn{mu}{nu}{alpha}{beta}` Spin generators with upper mu nu indices  
