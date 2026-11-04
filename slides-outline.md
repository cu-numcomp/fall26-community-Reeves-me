*Slide 1: Introduction*
Just open up the presentation with that the open source software community I choose to learn about was mlpack
*Slide 2: What is mlpack?*
Mlpack is a open-source C++ machine learning library that started in 2007 at Georgia Tech and eventually moved to github in 2014, [1708.05279] Designing and building the mlpack open-source machine learning library 
More specifically, it is an intuitive, fast, and flexible header-only C++ machine library with bindings to other languages (Quoted from ReadMe,  mlpack/mlpack: mlpack: a fast, header-only C++ machine learning library )
To help define this a little better,  header-only means the full definitions of all macros, functions and classes comprising the library are seen by the compiler in header file form, that has no separate implementation files or precompiled binaries: Header-only - Wikipedia 
This specific method of being fast and header only machine learning library, is what separated it from its competitors, such that it can be used as a "swiss army knife” for C++ based machine learning (github Read Me, mlpack/mlpack: mlpack: a fast, header-only C++ machine learning library)
As a header only library it depends on only three libraries: Armadillo, ensmallen, and cereal
As of recent the latest mlpack software mlpack 4 had the goal of refactoring to allow for a an easier prototyping to deployment pipeline, including bindings to other languages like Python or Julia.
Their License states it is free for commercial use as long as you include a citation, mlpack/LICENSE.txt at 4.8.0 · mlpack/mlpack 
*Slide 3: What problem did mlpack attempt to fix?*
According to the earliest documentation I could find on mlpack titled “MLPACK: A Scalable C++ Machine Learning Library” which was originally published in march 2013 states the key issue that mlpack aimed to originally solve, curtin13a.dvi 
They specifically stated that the problem was that few if any free machine learning libraries “offer efficient algorithms to the average user,” primarily focusing on the issue of scalability and 
*Slide 4: Who are the stockholders/sponsors?*
…
*Slide 5: How collaboration happens and who uses this software?*
…
*SLide 6: How do they define/measure their softwares*
…
*Slide 7: What are they good at vs what they are poorer at*
…
*Slide 8: What regression model do they use?  And is it made in the interest of good conditioning or choices of stability*
…
*Slide 9: An example of on of the regression models they use: and how it relates back to our class*
…
*Slide 10: Actually runned example of the mlpack from the model*
…
*Slide 11: More Broad view of them models the view (i.e. a list of models)*
..

Overall Should answer what is the intent of this open software and then how it relates back to this class with an example and an idea for experiment that would be interesting for a group project.  Should answer most if not all of the following questions:

*What key problems are solved?*
[] Rootfinding? Interpolation? Regression?
[] Is it general-purpose software or domain-specific? What makes it unique?
*Who are the stakeholders*
[] Who develops the software, who uses it, who pays for it?
[] What are they looking for?
[] How do they communicate and collaborate?
[] Who uses the software?
[] Who is impacted (positively or negatively) by use of the software?
*Metrics and features*
[] How do concepts like accuracy, conditioning, stability, and cost appear?
[] If the software is fast, how is "fast" defined?
[] If the software is accurate, what does accuracy mean? Could you make a plot, say accuracy vs cost? How would you label the axes to make it relevant to a stakeholder?
[] Would different stakeholders want different axes (because they care about different things)?
[] Are there modeling decisions made in the interest of good conditioning? Are there algorithmic choices made for stability?
