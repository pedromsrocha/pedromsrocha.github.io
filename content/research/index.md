I'm currently working in
the development and implementation of programming language CLASS. [Here](http://ctp.di.fct.unl.pt/CLASS/) you can find a stable open-source version of the implementation together with several examples. 

A bit about CLASS: some programming languages have strong foundations in Logic,
by exploring something known as the [Curry-Howard correspondence](https://en.wikipedia.org/wiki/Curry%E2%80%93Howard_correspondence). My PhD advisor 
and collaborators had established an [instantiation](https://link.springer.com/chapter/10.1007/978-3-642-15375-4_16) of this correspondence, by connecting
[Linear Logic](https://en.wikipedia.org/wiki/Linear_logic) and [Session Types](https://en.wikipedia.org/wiki/Session_type). During my PhD we extended this connection in order 
to accommodate shared mutable state, which is an essential building block
of modern software development. The resulting language CLASS lies at sweet spot 
between expressiveness and safety: we can code 
realistic concurrent programs involving memory-efficient linked data structures and
and sophisticated thread synchronisation. The logical foundations guarantee that well-typed 
CLASS programs do not go wrong: they never deadlock, do not leak memory and they always terminate. 

Below you can find my publications and some of my talks.  

### Publications ✏️

* Pedro Rocha and Luís Caires. [Safe Session-Based Concurrency with Shared Linear State](http://ctp.di.fct.unl.pt/CLASS/CLASS-NOV22.pdf). European Symposium on Programming, April 2023 (to appear). 
    * Companion evaluated and accepted [software](https://doi.org/10.5281/zenodo.7506064) with open-source license. 
* Pedro Rocha. [A Logical Foundation for Session-Based Concurrent Computation](http://hdl.handle.net/10362/146523). PhD thesis, NOVA School of Science and Technology, July 2022. 
* Pedro Rocha and Luís Caires. [Propositions-as-types and Shared State](https://doi.org/10.1145/3473584). Proc. ACM Program. Lang., 5(ICFP), August 2021. 
    * Companion evaluated and accepted [software](https://doi.org/10.5281/zenodo.5037493) with open-source license, [published](https://dl.acm.org/do/10.5281/zenodo.5037493/full/) in ACM Digital Library.
* Pedro Rocha and Luís Caires. [A Propositions-as-Types System for Shared State. Technical Report](http://ctp.di.fct.unl.pt/~lcaires/papers/PTSStech-report2021.pdf), NOVA Laboratory for Computer Science and Informatics, October 2021. 
* Pedro Rocha, Sérgio Pequito, Soummya Kar, A. Pedro Aguiar, and Paula Rocha. [Sensor Placement for Real-Time Dynamic State Estimation in Power Systems: Structural Systems Approach](https://ieeexplore.ieee.org/abstract/document/7094634). In 2014 48th Asilomar Conference on Signals, Systems and Computers, pages 1133–1137, 2014. 
* Pedro Rocha. [Output Selection for Large Scale Structural Systems:a Matroid Theory Approach](https://repositorio-aberto.up.pt/handle/10216/73404). Master’s thesis,Faculty of Engineering of University of Porto, July 2014. 

### Talks 🗣

* Safe Session-Based Concurrency with Shared Linear State. European joint conferences on theory and practice of software. Paris, April 2023 (upcoming). 
* A Logical Foundation for Safe Concurrent Programming with Shared State. Mobility Reading Group, Imperial College London. September, 2022.
* Propositions-as-Types and Shared State. Lasige, Faculty of Sciences of University of Lisbon. September 2021.
* Propositions-as-Types and Shared State. Mobility Reading Group, Imperial College London. May 2021.
* Towards Curry-Howard for Shared Mutable State. TYPES 2019. Oslo, Norway. June 2019.
* Curry-Howard for Shared Mutable State and Nondeterminism. 2nd International Workshop on Recent Advances in Concurrency and Logic (RADICAL 2019). Amsterdam, The Netherlands. August 2019.
* Sorting the πref -calculus. Days in Logic 2018. University of Aveiro, Portugal. January 2018.