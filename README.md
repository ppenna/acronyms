LaTeX Acronyms Library
======================

This repository gathers a bunch of acronyms that I have been collecting
during the past years. They mostly concern the Computer Science field.
The following libraries are featured:

- [x] Computer Architecture
- [x] High Performance Computing
- [x] Miscellaneous
- [x] Operating System

How to Use this Library
------------------------


#### 1. Add this Library to Your Project

```
cd path/to/your/project
git submodule add https://github.com/ppenna/acronyms.git
```

#### 2. Add Library Files to the Preamble of Your Main LaTeX File

```
\usepackage[acronym,nowarn]{glossaries}
\glsdisablehyper
\input{acronyms/computer-architecture.tex}
\input{acronyms/high-performance-computing.tex}
\input{acronyms/misc.tex}
\input{acronyms/operating-systems.tex}
\makeglossaries

```

#### 2. Update Your Library Once in a While

```
cd /path/to/your/project
cd acronyms
git checkout master
git pull
```

How to Contribute
-----------------

Just open a pull request ;-)
