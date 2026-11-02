# Project 7: Program and Statement Kernels

CSE 2231 — Autumn 2026

Eclipse project: **ProgramAndStatement**

Starter files imported from the course-provided `ProgramAndStatement.zip`. The assignment implementation and additional tests have not been completed.

## Open in Eclipse

1. Clone this repository.
2. Choose **File > Import > General > Existing Projects into Workspace**.
3. Select the repository directory as the root and import **ProgramAndStatement**.
4. Use the course Java setup, including the `OSU_CSE_LIBRARY` classpath variable, JUnit 4, and the OSU Checkstyle configuration. The supplied project also references the course FindBugs plugin.
5. Enable assertions (`-ea`) in the JUnit and tester launch configurations.

The course component library is not bundled with this repository. Eclipse will rebuild the generated classes in `bin/`, which Git ignores.

## Assignment work

1. Complete `createNewRep` and the required kernel methods in `src/Program2.java`. Use the library's `Statement1` when creating the initial representation.
2. Exercise the implementation with `src/ProgramTester.java`, BL inputs in `data/`, and the JUnit fixture `test/Program2Test.java`. Add appropriate inputs and test cases in `test/ProgramTest.java`.
3. Complete `createNewRep` and the required kernel methods in `src/Statement2.java`, using the supplied `assembleIf` and `disassembleIf` methods as a guide.
4. Exercise the implementation with `src/StatementTester.java`, BL inputs in `data/`, and the JUnit fixture `test/Statement2Test.java`. Add appropriate inputs and test cases in `test/StatementTest.java`.
5. Replace the starter author placeholders with the team members' names.

The starter has unfinished method bodies, so passing tests are expected only after the assignment is implemented. Source files and the supplied tests are preserved as downloaded.

## Submission

Submit the entire **ProgramAndStatement** Eclipse project as a ZIP through Carmen, following the course instructions. Coordinate with your teammates so only one member submits the agreed group solution.

[Course starter archive](https://cse22x1.engineering.osu.edu/2231/assignments/projects/program-statement-kernels/ProgramAndStatement.zip)
