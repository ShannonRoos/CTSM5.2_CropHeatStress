# Heat stress implementations:
New crop heat stress module is introduced.
i. vegetation temperature is here an optional output variable
ii. New CropheatStress.F90 file with heat stress function
iii. currently still two optional methods (hardcoded) to target crop either by accelerating LAI senescence or affecting allocation of grainC to food.


# copyright heat stress implementation:
MIT License

Copyright (c) [2026] [Shannon de Roos]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


------------------------

# CTSM

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3739617.svg)](https://doi.org/10.5281/zenodo.3739617)

## Overview and resources

The Community Terrestrial Systems Model.

This includes the Community Land Model (CLM5.0 and CLM4.5) of the Community Earth System Model.

For documentation, quick start, diagnostics, model output and
references, see

http://www.cesm.ucar.edu/models/cesm2.0/land/

and

https://escomp.github.io/ctsm-docs/

For help with how to work with CTSM in git, see

https://github.com/ESCOMP/CTSM/wiki/Quick-start-to-CTSM-development-with-git

and

https://github.com/ESCOMP/ctsm/wiki/Recommended-git-setup

For support with model use, troubleshooting, etc., please use the [CTSM
forum](https://bb.cgd.ucar.edu/cesm/forums/ctsm-clm-mosart-rtm.134/) or other appropriate forum (e.g., for
infrastructure/porting questions) through the [CESM forums](https://bb.cgd.ucar.edu/cesm/).

To get updates on CTSM tags and important notes on CTSM developments
join our low traffic email list:

https://groups.google.com/a/ucar.edu/forum/#!forum/ctsm-dev

(Send email to ctsm-software@ucar.edu if you have problems with any of this)

## CTSM code management team

CTSM code management is provided primarily by:

Software engineering team:
- [Erik Kluzek](https://github.com/ekluzek)
- [Bill Sacks](https://github.com/billsacks)
- [Sam Levis](https://github.com/slevisconsulting)
- [Adrianna Foster](https://github.com/adrifoster)
- [Sam Rabin](https://github.com/samsrabin)
- [Greg Lemieux](https://github.com/glemieux)
- [Ryan Knox](https://github.com/rgknox)

Science team:
- [Will Wieder](https://github.com/wwieder)
- [Dave Lawrence](https://github.com/dlawrenncar)
- [Danica Lombardozzi](https://github.com/danicalombardozzi)
- [Keith Oleson](https://github.com/olyson)
- [Sean Swenson](https://github.com/swensosc)
- [Peter Lawrence](https://github.com/lawrencepj1)
- Gordon Bonan

FATES Project:
- https://github.com/NGEET/fates?tab=readme-ov-file

Perturbed Parameter Experiment (PPE) Science team:
- [Katie Dagon] (https://github.com/katiedagon)
- [Daniel Kennedy] (https://github.com/djk2120)
- [Linnea Hawkins] (https://github.com/linniahawkins)
