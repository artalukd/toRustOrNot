# Papers

- https://arxiv.org/pdf/2107.11912.pdf [N-body Simulation, Rust vs C]
- https://www.reddit.com/r/rust/comments/brre8o/a_scaling_comparison_of_rust_rayon_and_c_and/
- https://ehnree.github.io/documents/papers/rustvsc.pdf
- http://www.macs.hw.ac.uk/~kp167/homepage/files/MScthesis.pdf

# Github
- https://github.com/trsupradeep/15618-project
- https://github.com/parallel-rust-cpp/shortcut-comparison
- https://parallel-rust-cpp.github.io/

# Slides
- https://fileadmin.cs.lth.se/cs/Education/EDAN26/F07.pdf

# Requirements
## Comparing Several Parallel Programming Languages

You need to compare the languages based on:
programmability (i.e. how easy it is to program with the language)
scalability (handling large number of threads)
runtime overhead of the language (measure how long it takes to create threads, terminate threads, synchronize, etc)
the amount of control given to the programmer (can the programmer decide which thread goes to which core, can the programmer decide which variables to be shared and which ones to be prviate, etc).

To test each of the above, you need to write a set of benchmark programs in each of the languages and compare. 
Each program must test one of the above points.

One of your conclusions, after the comparison, is to come up with a set of guidelines on when to use each language from the one you compared.

- http://kth.diva-portal.org/smash/get/diva2:648395/FULLTEXT01.pdf [C++/C#/Java comparison]
- https://ieeexplore.ieee.org/document/1303318 [Programability]
