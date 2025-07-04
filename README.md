# BergeEquilibria
Code for the computation of Berge equilibria
This package includes the implementation of three algorithms for computing Berge equilibria in regualr finite normal-form games. The algorithms are written in CoCoA (a computer algebra system) and are capable of handling games with any number of players and strategies.
The algorithms are described in detail in the accompanying publication [reference to be added].

🔧 Main Algorithm Files
AllBerge.cocoa5 — Computes all Berge equilibria (including pure and mixed).
MixedBerge.cocoa5 — Computes completely mixed Berge equilibria.
PureBerge.cocoa5 — Computes pure-strategy Berge equilibria.
Each file contains the code to identify the respective equilibria using polynomial systems.

🧪 Example Usage Files
To demonstrate how to run the algorithms, the following example files are included:
ComputeBerge2.cocoa5 — Example for a 2-player game.
ComputeBerge3.cocoa5 — Example for a 3-player game.
To execute these examples:

Launch CoCoA on your machine.
Open the CoCoA shell.
Copy and paste the contents of one of the example files into the shell.
CoCoA will automatically run the computation and return the corresponding Berge equilibria.

📌 Requirements
CoCoA version 5 must be installed on your system.
You can download it from: https://cocoa.dima.unige.it
