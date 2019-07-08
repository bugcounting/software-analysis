# Software Analysis

This public repository includes material (mostly slides) I prepared for a graduate course on (formal) software analysis,
which I have been teaching at [USI](http://inf.usi.ch/) since the 2019 spring semester as part of the [Master in Software and Data Engineering](http://www.msde.usi.ch).

I will usually update this repository after each iteration of the course with fixes and possibly new material.
You will find the material used in year `20YY` in the commit tagged `yYY`.

Except where otherwise noted, the content is all copyright [Carlo A. Furia](http://bugcounting.net/) 
and distributed under Creative Commons license [Attribution-NonCommercial-NoDerivatives 4.0 International](https://creativecommons.org/licenses/by-nc-nd/4.0/) (CC BY-NC-ND 4.0). 

If you use some of this material in your own teaching, I appreciate if you drop [me](mailto:furiac@usi.ch) a line.

If you find typos or other mistakes you are welcome to post an issue (or email me if you prefer).


## Topics

The course covers a variety of software analysis techniques:

1. **Introduction to software analysis** [[slides]](Slides/Lecture01-introduction.pdf) 
               presents some _motivation_ (see also [here](https://bugcounting.net/blog/?p=274)) and outlines the course's content
2. **Concepts of logic and computation** [[slides]](Slides/Lecture02-logic_computation.pdf) 
               is a recap of _formal logic_ and _computational complexity_, whose basic notions are used in the rest of the course
3. **Software analysis: the very idea** [[slides]](Slides/Lecture03-idea.pdf) 
               discusses several aspects of all _software analysis techniques_, which will be revisited during every main topic of the course
4. **Deductive verification** [[slides]](Slides/Lecture04-deductive.pdf) 
               presents _Hoare logic_, deductive _correctness proofs_, _weakest precondition calculi_, _verification conditions_, and _separation logic_
5. **Static analysis** [[slides]](Slides/Lecture05-static_analysis.pdf) 
               presents several classic _dataflow analyses_, gives a short high-level overview of _abstract interpretation_, and discusses _type systems_ and their peculiarities as static analyses
6. **Model checking** [[slides]](Slides/Lecture06-model_checking.pdf) 
               includes three topics in the verification of finite-state systems:
                      _automata-based model checking_ (mainly with linear-time logic); 
                      software model checking using _predicate abstraction_; 
					  and _real-time model checking_ using timed automata and metric temporal logic
7. **Symbolic execution** [[slides]](Slides/Lecture07-symbolic_execution.pdf) 
               presents both classic _symbolic execution_ and the more recent _dynamic-symbolic_ execution
8. **Dynamic analysis** [[slides]](Slides/Lecture08-dynamic_analysis.pdf) 
               describes a variety of techniques for program analysis based on _tests_: _delta debugging_, _slicing_, _fault localization_, and _assertion mining_


## Tools

You can try out all (open-source) tools used in the mini tutorials included in the slides 
by using the Docker image `bugcounting/satools` hosted on [Docker Hub](https://hub.docker.com/r/bugcounting/satools).
Use the version with the same tag `yYY` as the corresponding GitHub tag the slides come from.


## Credits

Part of the course is based on the Software Verification course that I taught with Bertrand Meyer and Sebastian Nanz at ETH Zurich in the years 2009--2015.

The closing slides in each batch reference articles and other sources on which the presentation is based.

Thanks to all students taking the course who pointed out typos and gave suggestions for improving the material.
