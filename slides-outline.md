**Slide 1: Introduction**

Just open up the presentation with the open-source software community I chose to learn about: mlpack

**Slide 2: What is mlpack?**

 - Mlpack is an open-source C++ machine learning library that started in 2007 at Georgia Tech and eventually moved to GitHub in 2014, [[1708.05279] Designing and building the mlpack open-source machine learning library ](https://ar5iv.arxiv.org/html/1708.05279)
 - More specifically, it is an intuitive, fast, and flexible header-only C++ machine learning library with bindings to other languages ([Quoted from ReadMe,  mlpack/mlpack: mlpack: a fast, header-only C++ machine learning library ](https://github.com/mlpack/mlpack))
 - To help define this a little better,  header-only means the full definitions of all macros, functions, and classes comprising the library are seen by the compiler in header file form, with no separate implementation files or precompiled binaries: [Header-only - Wikipedia ](https://en.wikipedia.org/wiki/Header-only)
 - This specific method of being a fast, header-only machine learning library is what separated it from its competitors, such that it can be used as a "Swiss Army knife” for C++-based machine learning ([GitHub Readme, mlpack/mlpack: mlpack: a fast, header-only C++ machine learning library](https://github.com/mlpack/mlpack))
 - As a header-only library, it depends on only three libraries: Armadillo, ensmallen, and cereal
 - As of recently, the latest mlpack software, mlpack 4, had the goal of refactoring to allow for an easier prototyping-to-deployment pipeline, including bindings to other languages like Python or Julia.
 - Their License states it is free for commercial use as long as you include a citation: [mlpack/LICENSE.txt at 4.8.0 · mlpack/mlpack](https://github.com/mlpack/mlpack/blob/4.8.0/LICENSE.txt)

**Slide 3: What problem did mlpack attempt to fix?**

 - According to the earliest documentation I could find on mlpack titled “MLPACK: A Scalable C++  - Machine Learning Library” which was originally published in March 2013, it states the key issue that mlpack aimed to solve originally, they specifically stated that the problem was that few, if any, free machine learning libraries “offer efficient algorithms to the average user,” primarily focusing on the issue of scalability and efficiency through the use of LAPACK and the Armadillo matrix library, such that MLPACK becomes the machine learning analog to the general-purpose LAPACK that *"eliminates unnecessary copying of data sets and performs expression optimization unavailable in other languages"* [MLPACK: A Scalable C++ Machine Learning Library](https://dl.acm.org/doi/pdf/10.5555/2567709.2502606)
 - The four major goals of development the team focused on when making this pack were as follows: one, implement scalable and fast machine learning algorithms. Two, design an intuitive, consistent, and simple API for non-expert users. Three, implement a variety of machine learning methods, and finally, four, provide cutting-edge machine learning algorithms unavailable elsewhere. [MLPACK: AScalable C++ Machine Learning Library](https://dl.acm.org/doi/pdf/10.5555/2567709.2502606)

**Slide 4: Who are the stockholders/sponsors?**

 - Sponsor: NumFocus
 - Support from: Georgia Tech, Freie Universität Berlin, Symantic, NSF, and Google
 - Google specifically has continued to work with mlpack for over a decade via Google Summer of Code.
 - [2023 mlpack 4](https://www.mlpack.org/papers/2023mlpack.pdf)

**Slide 5: How does collaboration happen, and who uses this software?**

- The software is specifically made for anyone interested in using and/or learning about Machine Learning, though they do specify it is more for researchers and ML engineers.
- The contributors to this project are anyone in the community, as they have had over 220 contributors in the history of the software.[2023 mlpack 4](https://www.mlpack.org/papers/2023mlpack.pdf)
- Collaboration happens through git pull requests, where they further specify in their Contributions.md the specific format for how to contribute, with a specific style guide explaining your understanding and how it fixes a feature. As well, in the explanation, they specify that you have to explain it as if you were explaining it to a new user. [contribution.md](https://github.com/mlpack/mlpack/blob/master/CONTRIBUTING.md)

**Slide 6: How do they define/measure their software?**

 - …
 - [A generic and fast C++ optimization framework](https://arxiv.org/pdf/1711.06581v1), about mlPack

**Slide 7: List of the regression models they use? And are the models made for good conditioning or choices of stability?**
 
 - …

**Slide 8: An example of one of the regression models they use, and how it relates back to our class**

 - …

**Slide 9: An actual example of the mlpack from the model, that was just explained**

 - …

**Information to fill out**

Overall Should answer what is the intent of this open software and then how it relates back to this class with an example and an idea for experiment that would be interesting for a group project.  Should answer most if not all of the following questions:

**What key problems are solved?**

- [X] Rootfinding? Interpolation? Regression?
- [X] Is it general-purpose software or domain-specific? What makes it unique?

**Who are the stakeholders**

- [X] Who develops the software, who uses it, who pays for it?
- [X] What are they looking for?
- [X] How do they communicate and collaborate?
- [X] Who uses the software?
- [X] Who is impacted (positively or negatively) by use of the software?

**Metrics and features**

- [] How do concepts like accuracy, conditioning, stability, and cost appear?
- [] If the software is fast, how is "fast" defined?
- [] If the software is accurate, what does accuracy mean? Could you make a plot, say accuracy vs cost? How would you label the axes to make it relevant to a stakeholder?
- [] Would different stakeholders want different axes (because they care about different things)?
- [] Are there modeling decisions made in the interest of good conditioning? Are there algorithmic choices made for stability?
