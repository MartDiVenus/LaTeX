isphysicalmath package

Author: Mario Fantini, marfant7@gmail.com

License: LaTeX Project Public License lppl

Copyright (C) 2024 Mario Fantini



# Overview

LaTeX is a powerful language, but to take advantage of it, to respect its quality
and to observe the discipline of matters that it interacts with: it requires some devices.

If you are interested in the form of math and physics, here comes `isphysicalmath` inside LaTeX;
as far as international scientific notation and formatting of formulas, quantities,
numerical values, factors, dimensions, measurement units.

So, `isphysicalmath` package helps user to write mathematical and physical contents, 
 according to the scientific notation (international mainly), in an elegant way.


# Dependencies

`isphysicalmath` has not dependencies.

Internally, it uses standard commands like: \textnormal, \hspace{}; however,
it performs its activity in complex math environment too.


# Documentation

The documentation is `isphysicalmath-doc.pdf` mainly. It contains:

- General Index

- Introduction

- Conventions

- Dependencies

- Usage

- In-depth usage

    - In-depth formatting

    - In-depth notation

        - option 'dc'

        - option 'comma'

- isphysicalmath url
 
- Copyright
 
- Change History


# Build isphysicalmath.sty
```
cd isphysicalmath 
latex isphysicalmath.ins
```

# Build the documentation

```
cd isphysicalmath 
latex isphysicalmath.dtx
makeindex -s gglo.ist -o isphysicalmath.gls isphysicalmath.glo
latex isphysicalmath.dtx
dvipdf isphysicalmath.dvi
```

# Credits

Thanks to all  TeX/LaTeX contributors, in  particular to Scott Pakin
for his packaging tutorial, and to CTAN team  for its tutoring, tools
and services.


# URL

Package home URL: https://github.com/MartDiVenus/LaTeX/tree/isphysicalmath

This package is located at\
   https://mirrors.ctan.org/macros/latex/contrib/isphysicalmath

More information is at\
   https://www.ctan.org/pkg/isphysicalmath


# License 

Copyright (C) 2023 by Mario Fantini <marfant7@gmail.com>

This file may be distributed and/or modified under the conditions of
the LaTeX Project Public License, either version 1.3 of this license
or (at your option) any later version.  The latest version of this
license is in:
 
    http://www.latex-project.org/lppl.txt
 
and version 1.3 or later is part of all distributions of LaTeX version
2005/12/01 or later.

This work has the LPPL maintenance status 'maintained'.
 
The Current Maintainer of this work is Mario Fantini.

This work consists of the files isphysicalmath.dtx and isphysicalmath.ins
and the derived file isphysicalmath.sty.


