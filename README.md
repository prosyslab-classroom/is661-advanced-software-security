# IS893: Advanced Software Security

## Logistics
- Instructor: [Kihong Heo](https://kihongheo.kaist.ac.kr) (kihong.heo@kaist.ac.kr)
- TAs:
- Time:
- Office hour:
- Location:

## Course Description
The main theme of this course is __"the relationship between specification and program"__ for safe and reliable software. 
This course will cover two topics under the theme:
1. program verification: how to automatically prove whether if a given program satisfies the specification,
2. program synthesis: how to automatically generate a program that satisfies the specification.

Students will learn theories and practices of program verification and synthesis through lectures, assignments, and term projects.
This course will be highly interactive and involve a significant amount of academic communication including reading, writing, and presentations.

## Grading
- Assignments: 20%
- Midterm project: 30%
- Final project: 40%
- Participation: 10%

## Textbook
- Lecture slides will be provided
- [Program Synthesis](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/10/program_synthesis_now.pdf)
- [Introduction to Program Synthesis](https://people.csail.mit.edu/asolar/SynthesisCourse/index.htm)

## Homework
This course includes programming assignments through which students will learn how to design
and implement program analyzers.
Students will use a few tools which are described [here](TOOL.md).

All submissions will be managed using Github.
For each assignment, a unique invitation URL for Github Classroom will be posted in the [issue board](../../issues).
Once you accept the invitation, a private repository for your assignment will be created.
You can push as many commits as you want before the deadline. We will grade the final commit of your `master` branch.

The late homework policy is as follows:
- 80% credit for one day late
- 50% credit for two days late
- NO credit given after two days late

## Presentation
- Each student is required to give 4 presentations (midterm project, final project proposal, final project result, and paper presentation).
- Each student is required to give at least 1 question for each student presentation.

## Projects
- Midterm project: each student will design and implement an advanced program synthesizer.
  - Presentation: students will present their own idea to advance a naive program synthesizer.
- Final project: each student will define and solve your own problem related to program synthesis or program verification.
  - Proposal writing: students will submit their project proposal that will be reviewed by other students, TAs, and instructors.
  - Proposal presentation: students will present their plans for the project and rebut criticisms from reviewers.
  - Final presentation: students will present their resultss.

## Academic Integrity Violation
Students who violates academic integrity will get an F.

## Schedule
|Week|Topics|Reading|Homework|
|-|------|-------|--------|
|0|Functional Programming in OCaml||
|1|Introduction||HW0: Hello-world||
| |Preliminaries||HW1: OCaml Programming|
|2|Inductive Synthesis|||
| |Bottom Up Search||Project1: Program Synthesizer|
|3|Top Down Search|||
| |Search with Probabilistic Model||HW2: Reading Critique ([PLDI2018](https://dl.acm.org/doi/10.1145/3296979.3192410))|
|4|Version-Sapce Algebra|||
| |Functional Synthesis||HW3: Reading Critique ([ASPLOS2006](https://dl.acm.org/doi/10.1145/1168919.1168907))|
|5|Counterexample-guided Inductive Synthesis||
|6|Program Verification|||
| |TBD|||
|7|TBD||HW4: Program Verifier|
| |TBD|||
|8|No Classes (Midterm week)|||
|9|Midterm Project Presentation (1)||HW5: Final Project Proposal|
|10|Midterm Project Presentation (2)|||
|11|Proposal Review & Discussion|||
|  |Proposal Presentation||Project2: Final Project|
|12|Paper Presentation (1)|||
|13|Paper Presentation (2)|||
|14|Final Project Presentation (1)|||
|15|Final Project Presentation (2)|||

## Related Papers
- [CCS2021](https://arxiv.org/abs/2109.07441)
- [UsenixSec2017](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/blazytko)
