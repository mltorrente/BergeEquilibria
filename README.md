# BergeEquilibria
Code for the computation of Berge equilibria.

This package includes the implementation of various algorithms for computing Berge equilibria in regular finite normal-form games. 

The algorithms are written in CoCoA http://cocoa.dima.unige.it (version 5.4.1, freely available under the GNU General Public License) and are capable of handling games with any number of players and strategies.

The algorithms are described in detail in the accompanying publication Riedel, Frank; Torrente, Maria-Laura (2025) : Berge equilibria: An algebraic
approach, Center for Mathematical Economics Working Papers, No. 750, Bielefeld University, Center
for Mathematical Economics (IMW), Bielefeld. https://www.econstor.eu/bitstream/10419/324279/1/1931589682.pdf


# Main Algorithm Files
- AllBerge.cocoa5 — Computes all Berge equilibria (including pure and mixed).
- MixedBerge.cocoa5 — Computes completely mixed Berge equilibria.
- PureBerge.cocoa5 — Computes pure-strategy Berge equilibria.
- ExistenceCMBE.cocoa5 - Determines the existence of completely mixed Berge equilibria.
  
Each file contains the code to identify the respective equilibria using polynomial systems.

# Example Usage Files
To demonstrate how to run the algorithms, the following example files are included:
- ComputeBerge2.cocoa5 — Example for a 2-player game.
- ComputeBerge3.cocoa5 — Example for a 3-player game.

To execute these examples:
- Launch CoCoA on your machine.
- Open the CoCoA shell.
- Copy and paste the contents of one of the example files into the shell.

CoCoA will automatically run the computation and return the corresponding Berge equilibria.

# Requirements
CoCoA version 5 must be installed on your system.

You can download it from: https://cocoa.dima.unige.it
