# IS593: Advanced Software Security

## Logistics
- Instructor: [Kihong Heo](https://kihongheo.kaist.ac.kr) (kihong.heo@kaist.ac.kr)
- TAs:
- Time: Tue/Thr 09:00 - 10:15
- Office hour: Tue 10:15 - 11:00 (by appointment)
- Location: N5 2243

## Course Description
The main theme of this course is __"the relationship between specification and program"__ for safe and reliable software. 
This course will cover two topics under the theme:
1. **program verification**: how to automatically _prove_ whether a given program satisfies the specification,
2. **program synthesis**: how to automatically _generate_ a program that satisfies the specification.

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
  - Proposal presentation: students will present their plans for the project and rebut criticism from reviewers.
  - Final presentation: students will present their results.

## Academic Integrity Violation
Students who violate academic integrity will get F.
See [the KAIST CS hornor code](https://docs.google.com/forms/d/e/1FAIpQLSdSn63tEvq6R0G6n3Cz7jKX16RWvDy2giBKm8EVJtQHUBJoDA/viewform).

## Schedule
|Week|Topics|Reading|Homework|
|-|------|-------|--------|
|0|Functional Programming in OCaml||
|1|Introduction||HW0: OCaml Programming||
| |Introduction to Program Synthesis||HW1: Reading Critique ([Wired2021](https://www.wired.com/story/ai-write-code-like-humans-bugs/?fbclid=IwAR3kO0xXVzeTABqGscyPPYcPYuVu2fSHYSEiBpMCoKTWXKZl1Ah9H6TVGHM&mbid=social_facebook&utm_brand=wired&utm_campaign=falcon&utm_medium=social&utm_social-type=owned))|
|2|Inductive Synthesis and Enumerative Search|||
| |Search Space Pruning||HW2: Program Synthesizer|
|3|Search Space Prioritization||HW3: Reading Critique ([PLDI2018](https://dl.acm.org/doi/10.1145/3296979.3192410))|
| |Representation-based Search|||
|4|Introduction to Program Verification|||
| |First-order Logic||
|5|Hoare Logic||HW4: Reading Critique ([SNP2020](http://prl.korea.ac.kr/~pronto/home/papers/snp20.pdf))|
| |Verification Conditions|||
|6|Contrained Horn Clauses||HW5: Reading Critique ([PLDI2020](https://www.cs.utexas.edu/~hovav/dist/vera.pdf))|
| |Midterm Project Presentation (1)|||
|7|Midterm Project Presentation (2)||HW6: Program Verifier|
| |Midterm Project Presentation (3)|||
|8|No Classes (Midterm week)||[HW7: Final Project Proposal](https://kaist-asos22.hotcrp.com)|
|9|Proposal Review & Discussion|||
| |Proposal Presentation||Final Project|
|10|Paper Presentation (1)|||
|11|Paper Presentation (2)|||
|12|Paper Presentation (3)|||
|13|Final Project Presentation (1)|||
|14|Final Project Presentation (2)|||
|15|Final Project Presentation (3)|||
|16|No Classes (Final week)|||

## Papers 
### Program Synthesis
- [DPGen: Automated Program Synthesis for Differential Privacy, CCS'21](https://arxiv.org/abs/2109.07441)
- [Syntia: Synthesizing the Semantics of Obfuscated Code, UsenixSec'17](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/blazytko)
- [Data-Driven Synthesis of Provably Sound Side Channel Analyses, ICSE'21](https://ieeexplore.ieee.org/document/9402113)
- [An Inductive Synthesis Framework for Verifiable Reinforcement Learning, PLDI'19](https://dl.acm.org/doi/10.1145/3314221.3314638)
- [Optimizing Homomorphic Evaluation Circuits by Program Synthesis and Term Rewriting, PLDI'20](https://dl.acm.org/doi/abs/10.1145/3385412.3385996)
- [Synthesizing Highly Expressive SQL Queries from Input-Output Examples, PLDI'17](https://dl.acm.org/doi/10.1145/3062341.3062365)
- [Combinatorial sketching for finite programs, ASPLOS'06](https://dl.acm.org/doi/10.1145/1168919.1168907)

### Program Verification
- [Verifying Correct Usage of Context-Free API Protocols, POPL'19](https://dl.acm.org/doi/10.1145/3434298)
- [Verified Three-Way Program Merge, OOPSLA'18](https://dl.acm.org/doi/10.1145/3276535)
- [Alive2: bounded translation validation for LLVM, PLDI'21](https://dl.acm.org/doi/10.1145/3453483.3454030)
- [Reluplex: An efficient SMT solver for verifying deep neural networks, CAV'17](https://link.springer.com/chapter/10.1007/978-3-319-63387-9_5)

## Articles
- [프로그램 합성, 보안, 그리고 인공지능](https://www.boannews.com/media/view.asp?idx=92658)
- [Neural network verification: Where are we and where do we go from here?](https://blog.sigplan.org/2021/11/04/neural-network-verification-where-are-we-and-where-do-we-go-from-here/)

## Acknowlegement
A large part of the slides is based on the lecture notes by Nadia Polikarpova and Woosuk Lee. 
