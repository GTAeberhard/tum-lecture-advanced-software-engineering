# TUM Lecture - _Developing an Autonomous Vehicle: A Use-Case in Software Engineering_

![LaTeX Build](https://github.com/GTAeberhard/tum-lecture-advanced-software-engineering/actions/workflows/build-latex.yml/badge.svg)

I was invited by 
[Prof. Florian Matthes](https://wwwmatthes.in.tum.de/pages/88bkmvw6y7gx/Prof.-Dr.-Florian-Matthes)
to give a guest lecture at the Technische Universität München for the course
[Advanced Software Engineering](https://wwwmatthes.in.tum.de/pages/c9ulr7t9nrqs/Advanced-Topics-of-Software-Engineering).
The original lecture took place on February 7, 2022. It was held again on January 30, 2023.

The topic of the lecture is the application of software engineering in the field
of autonomous vehicles.

## Compiling the Lecture

The lecture in this repository is created with LaTeX using the [`beamer`](https://ctan.org/pkg/beamer) package.
To compile the lecture on Ubuntu, be sure to have [`texlive`](https://www.tug.org/texlive/) installed on your system.
Additionally, the [`pygments`](https://pypi.org/project/Pygments/) Python package should be installed so that the
[`minted`](https://ctan.org/pkg/minted) package is able to compile.

The [`beameraudience`](https://ctan.org/pkg/beameraudience) package is used to skip some slides which provide more
in-depth information on certain topics, but could not be presented due to time during the lecture. To compile the 
lecture with all of the slides, pass the option `audience=long` to the `beameraudience` package declaration.

The folder `.vscode` provides some toolchain configurations for the 
[LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) Visual Studio Code
extension.
