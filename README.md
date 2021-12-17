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
| |Hoar logic|||
|7|Verification conditions||HW4: Reading Critique ([SNP2020](http://prl.korea.ac.kr/~pronto/home/papers/snp20.pdf))|
| |Contrained Horn Clauses||HW5: Reading Critique ([PLDI2020](https://www.cs.utexas.edu/~hovav/dist/vera.pdf))|
|8|No Classes (Midterm week)||HW6: Program Verifier|
|9|Midterm Project Presentation (1)||HW7: Final Project Proposal|
|10|Midterm Project Presentation (2)|||
|11|Proposal Review & Discussion|||
|  |Proposal Presentation||Project2: Final Project|
|12|Paper Presentation (1)|||
|13|Paper Presentation (2)|||
|14|Final Project Presentation (1)|||
|15|Final Project Presentation (2)|||

## Papers 
### Program Synthesis
- [DPGen: Automated Program Synthesis for Differential Privacy, CCS'21](https://arxiv.org/abs/2109.07441)
- [Syntia: Synthesizing the Semantics of Obfuscated Code, UsenixSec'17](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/blazytko)
- [Data-Driven Synthesis of Provably Sound Side Channel Analyses, ICSE'21](https://ieeexplore.ieee.org/document/9402113)
- [An Inductive Synthesis Framework for Verifiable Reinforcement Learning, PLDI'19](https://dl.acm.org/doi/10.1145/3314221.3314638)
- [Optimizing Homomorphic Evaluation Circuits by Program Synthesis and Term Rewriting, PLDI'20](https://dl.acm.org/doi/abs/10.1145/3385412.3385996)
- [Synthesizing Highly Expressive SQL Queries from Input-Output Examples, PLDI'17](https://dl.acm.org/doi/10.1145/3062341.3062365)

### Program Verification
- [Alive2: bounded translation validation for LLVM, PLDI'21](https://dl.acm.org/doi/10.1145/3453483.3454030)

## Articles
- [프로그램 합성, 보안, 그리고 인공지능](https://www.boannews.com/media/view.asp?idx=92658)
