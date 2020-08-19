# Computational Science Rosetta Stone

<p align="center">
  <img source="https://github.com/Computational-Science-Rosetta-Stone/Project-Description/blob/master/rosetta_stone_300x450_icon.jpg">
</p>

## What is this all about?
This project is intended to provide examples (minimal working examples) of how to do common scientific tasks in code. It is intended to show how to do the same tasks **across** languages. Some rules for the code are listed below.

The project could be viewed specifically as a computational science project, but is intended to cover the broadest array of scientific coding problems. Therefore, repositories and examples covering all of the following are appropriate:

+ Applied Mathematics
+ Computational Modeling
+ Computational Science
+ Data Science
+ Mathematical Modeling
+ Numerical Mathematics
+ Statistics

**and any other computational procedures in science generally**. For example, shell scripting code for managing data or coordinating other software would be more than welcome. As would code related to generating automated reports as a part of the scientific research cycle.

Currently all of the code appears in the repo **Code Examples** and that will likely remain until there is enough code to require a reorganization into different projects under the main organization.

We welcome pull requests, feature requests, issues, and direct communications about the project (but **especially** pull requests!).

## Style Notes (Preliminary)
### Example Programs
As stated above, the goal is to teach people, through examples, how to do similar tasks in different languages. We want to make efficient scientists, not necessarily the best programmers. So optimization of the examples follows this principle.

**I.** Each Example program should be a **minimal working example** rather than something more complicated. Thus, each program should show how to execute one complete task. We acknowledge that this is ambiguous and to some extent in the eye of the beholder. For the moment, you just have to convince [mdtdev](https://github.com/mdtdev). If this project expands we will need some process for this!

**II.** Programs should be **didactic** and **well-documented** with comments and notes. Programs that are submitted without these may be rejected; submissions should be built for this project, we don't want to be given examples developed for other purposes. Exceptions may be made by prior agreement, especially if there is someone available who is willing to revise and document the code.

**III.** Programs that are **easy to understand and that make processes clear** are preferred over programs that are clever or optimized for speed or memory (unless this is the point of the example).

**IV.** Programs should be idomatic to their languages insofar as this clarifies things; if scientific users would be better served by a less idomatic (and usually this implies less efficient) program, this latter can be used. However, as the goal is cross-language understanding, idiom is not a specific goal in itself.

Therefore, **code that emphasizes similarities across languages is almost always preferred over pure, idomatic code**.

**V.** (The big "however.") There is no strict limit to examples for a task. Therefore, it is possible, likely even, that multiple examples from the same language for a task can be constructed. We are open to this especially in the case of idiomatic style. So an example with `task_matlab_example.m` might also have `task_matlab-like.py` and `task_idiomatic-python.py` where the comparison of code has value to the learner. This will be clarified over time.

For example, Python code formatted more like Matlab might make sense if the problem being analyzed is the solution of differential equations. Or an R-like idiom might be preferable for statistics problems even if it is not the natural form for another language. This will be decided on a case-by-case basis.

### Organization
The primary organization is by folder. Within a folder will be a `README.md` file that will specify the problem to be solved and use keywords to make searching easier. If the process is data based, there will be a `Data` subfolder. Please keep the directory structure as flat as possible. Use minimal data and make sure that the data is either artificial or legally can be shared. Please do not use data at other sites or data built-into software (for example, do not use the built in data sets in R!), unless this can be legally extracted and shared in an open format.

Unless there is compelling reason to do so, data shoule be in a universal (open!) format, such as `.csv` or `.txt`, and read from this directly into the program. (For instance, do not store both `.csv` and, say, SPSS format data files for statistical examples. If needed, use SPSS's capability to load `.csv` data.)

Unless it is impossible, the code examples should be in single, complete files that use the usual extension for the example language. In principle, a person should be able to download the example file(s) and the `Data` directory to their local machine, and then either start the application (such as Matlab or SPSS) or open a command prompt in the directory and directly run the program from the command line. 

For scripting languages, do **not** start the programs with shebangs. For instance, the preferred style is to write Python programs that are executed as `python progran_name.py` rather than as scripts executed as `./program_name` as this is more cross-platform. (This rule may change over time.)

#### Naming Conventions
TBD. But simpler is better. `load_data.py` is preferred to `data_loading_example_in_python.py` but `load_data_idiomatic_python.py` is acceptable where needed (see above).

— Matt Turner <br>
2020.08.18
