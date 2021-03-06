# bu2s

BU2S is a forward-time, mutation-based, infinite-sites, individual-based, stochastic population genetic simulator.
It includes mutation, selection, migration, recombination, and drift.  A full explanation of the biological scenarios simulated with this program can be found in the following two publications:

1. Flaxman SM, Wacholder AC, Feder JL, and Nosil P. 2014.  Theoretical models of the influence of genomic architecture on the dynamics of speciation.  Molecular Ecology 23:4074-4088. [doi: 10.1111/mec.12750](http://dx.doi.org/10.1111/mec.12750).
2. Flaxman SM, Feder JL, and Nosil P.  2013.  Genetic hitchhiking and the dynamic buildup of genomic divergence during speciation-with-gene-flow. Evolution 67:2577-2591. [doi: 10.1111/evo.12055](http://dx.doi.org/10.1111/evo.12055).

(see [https://www.researchgate.net/profile/Samuel_Flaxman/publications](https://www.researchgate.net/profile/Samuel_Flaxman/publications) for downloads of PDFs)

Example data sets produced by the code for the publications above are available at DataDryad.org ([http://dx.doi.org/10.5061/dryad.kc596](http://dx.doi.org/10.5061/dryad.kc596), and [http://dx.doi.org/10.5061/dryad.t894r](http://dx.doi.org/10.5061/dryad.t894r)) 

Additional capabilities since the publication of those articles includes (1) modeling neutral sites in the genome and (2) collection of additional population genetic metrics.

System Requirements for compiling and running the program:

* a Linux/UNIX-style terminal or terminal emulator
* a C compiler (gcc is the default in the Makefile)
* make

To use:

(1) Download the "Source" directory from this GitHub repository.

(2) In a Linux/UNIX terminal type the following (not the dollar signs; those represent the prompt):
    
    $ cd Source
    $ make clean
    $ make

The executable generated by make ("bu2s") can then be run with the command:
    
    $ ./bu2s

A list of command line options and their explanations can be obtained with the command:
    
    $ ./bu2s -?


This work is licensed under a Creative Commons Attribution 3.0 Unported License ([http://creativecommons.org/licenses/by/3.0/](http://creativecommons.org/licenses/by/3.0/)).
You can use it for any purpose you wish, so long as you acknowledge the author and preserve any existing copyright notices in any copies you create or distribute.

Absolutely NO warranty is implied for any portion of the code.  There are many options built into the code which have not yet been vetted.  Only those options used in the publications mentioned above should be considered to be reliable at this point in time.

Please email questions, comments, complaints, ideas, requests, and awesome cat pictures to samuel.flaxman@colorado.edu

