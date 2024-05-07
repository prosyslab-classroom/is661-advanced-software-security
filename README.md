# IS661: Advanced Software Security (고급 소프트웨어 보안)

## Logistics
- Instructor: [Kihong Heo](https://kihongheo.kaist.ac.kr) (허기홍, kihong.heo@prosys.kaist.ac.kr)
- TAs (mailing list: is661.ta@prosys.kaist.ac.kr)
  - [Yeonhee Ryou](https://yeonhee-ryou.github.io) (류연희)
  - [Jaeseong Kwon](https://doitman.kr) (권재성)
- Time: Tue/Thr 09:00 - 10:15
- Location: N5 2243
- Office hours:
  - Instructor: Mon 10:30 - 11:30
  - TAs: Wed 10:30 - 11:30

## Course Description
The goal of this course is to develop scientific communication skills.
Students will learn how to write a research paper, give a technical
talk, and review a research paper. Students will propose and complete
a research project during the semester.

## Grading
- Homework: 40%
- Final project: 50%
- Participation: 10%

## Project Theme: Understandable & Explainable Programming Systems
Observation is the beginning of all sciences.
For example, Heliocentrism, one of the most important scientific discoveries,
started from several critical observations by Galileo Galilei.
This observation led to the development of modern astronomy.
Computer science is no exception.
Only when we observe the behavior of large and complicated software systems,
we can understand how they work and discover new knowledge.

The project theme of this course is "Be Galileo of Programming Systems".
Students will make a visualization tool for understandable and explainable
programming systems (e.g., program analyzer, fuzzer, synthesizer, compiler, etc).
The visualization tool should help users understand the behavior of the
underlying programming system. For example, such tools can provide the following benefits:
- Help computer scientists (e.g., yourself) find new research problems in programming language, software engineering, or security.
- Help non-expert users understand the behavior of software analyzers.

Students can refer to the following projects for inspiration:
- [James Webb Space Telescope](https://webb.nasa.gov)
- [Event Horizon Telescope](https://eventhorizontelescope.org)
- [Fuzzle](https://softsec-kaist.github.io/Fuzzle/)
- [Bubble-sort dance](https://www.youtube.com/watch?v=Iv3vgjM8Pv4), [Quick-sort dance](https://www.youtube.com/watch?v=3San3uKKHgg)
- [D3](https://d3js.org)

## Paper & Proposal Review
We use [HotCRP](https://kaist-asos2024.hotcrp.com).

## Academic Integrity Violation
Students who violate academic integrity will get an F.
See [the KAIST CS honor code](https://docs.google.com/forms/d/e/1FAIpQLSdSn63tEvq6R0G6n3Cz7jKX16RWvDy2giBKm8EVJtQHUBJoDA/viewform).

## Hall of Fame
Visit [this page](student_artifacts.md) and have fun with student artifacts.

## Schedule
|Date|Topics|Watching|Homework|
|----|------|:--------------:|--------|
|2/27|[Introduction](slides/lecture1.pdf)|||
|2/29|[You and Your Research](https://www.cs.virginia.edu/~robins/YouAndYourResearch.html)|[<img src="icons/youtube.png" width="16" />](https://www.youtube.com/watch?v=a1zDuOPkMSw)||
|3/5 |Discussion||HW1: Essay (due: 3/3 23:59:59)|
|3/7 |[How to Write a Great Research Paper](assets/simon-papers.pdf)|[<img src="icons/youtube.png" width="16" />](https://www.youtube.com/watch?v=WP-FkUaOcOM)||
|3/12|[How to Write Papers So People Can Read Them](assets/talk-plmw16.pdf)|[<img src="icons/youtube.png" width="16" />](https://www.youtube.com/watch?v=KfEVdMMY1aQ)||
|    |[Data Visualization](assets/data-viz.pdf)|[<img src="icons/youtube.png" width="16" />](https://www.youtube.com/watch?v=Hfx1X9WSGYQ)||
|3/14|Discussion||[HW2: Your quick sort paper](quicksort.md) (due: 3/12 23:59:59)|
|3/19|[How to Give a Great Research Talk](assets/simon-talks.pdf)|[<img src="icons/youtube.png" width="16" />](https://www.youtube.com/watch?v=sT_-owjKIbA)||
|3/21|Research Talk 1||HW3: Review (due: 3/21 23:59:59)|
|3/26|Research Talk 2|||
|3/28|Research Talk 3|||
|4/2 |[How to Write a Grant Proposal](assets/simon-proposal.pdf)|[<img src="icons/youtube.png" width="16" />](https://www.youtube.com/watch?v=nEuK54bo6RE)||
|4/4 |Project Proposal Talk 1||HW4: Project Proposal (due: 4/2 23:59:59)|
|4/9 |Project Proposal Talk 2|||
|4/11 |Project Proposal Talk 3|||
|4/16|Mid term week (no class)|||
|4/18|Mid term week (no class)|||
|4/23 |Paper Presentation 1|||
|4/25 |Paper Presentation 2|||
|4/30 |Paper Presentation 3|||
|5/2 |Paper Presentation 4|||
|5/7 |Paper Presentation 5|||
|5/9 |Paper Presentation 6|||
|5/14 |Paper Presentation 7||HW5: Paper Review (due: 5/14 23:59:59)|
|5/16 |Final Project Presentation 1|||
|5/21 |Final Project Presentation 2|||
|5/23 |Final Project Presentation 3|||
|5/28 |Final Project Presentation 4|||
|5/30 |Final Project Presentation 5||Project: Paper (due: 6/1 23:59:59)|

## Papers
### Program Analysis & Testing
- [On-The-Fly Static Analysis via Dynamic Bidirected Dyck Reachability, POPL'24](https://arxiv.org/abs/2311.04319)
- [UBfuzz: Finding Bugs in Sanitizer Implementations, ASPLOS'24](https://arxiv.org/abs/2401.04538)
- [Abstract Interpretation of Fixpoint Iterators with Applications to Neural Networks, PLDI'23](https://arxiv.org/abs/2110.08260)
- [Compiler Test-Program Generation via Memoized Configuration Search, ICSE'23](https://ieeexplore.ieee.org/document/10172512)
- [Return of CFA: Call-Site Sensitivity Can Be Superior to Object Sensitivity Even for Object-Oriented Programs, POPL'22](https://dl.acm.org/doi/abs/10.1145/3498720)
- [Finding Real Bugs in Big Programs with Incorrectness Logic, OOPSLA'22](https://dl.acm.org/doi/10.1145/3527325)
- [Demanded Abstract Interpretation, PLDI'21](https://dl.acm.org/doi/10.1145/3453483.3454044)
- [Incremental Whole-Program Analysis in Datalog with Lattices, PLDI'21](https://dl.acm.org/doi/10.1145/3453483.3454026)
- [Abacus: Precise Side-Channel Analysis, ICSE'21](https://ieeexplore.ieee.org/document/9402127)
- [Incorrectness logic, POPL'20](https://dl.acm.org/doi/10.1145/3371078)

### Program Verification
- [Formally Verified Native Code Generation in an Effectful JIT: Turning the CompCert Backend into a Formally Verified JIT Compiler, POPL'23](https://dl.acm.org/doi/abs/10.1145/3571202)
- [Alive2: bounded translation validation for LLVM, PLDI'21](https://dl.acm.org/doi/10.1145/3453483.3454030)
- [Towards a Verified Range Analysis for JavaScript JITs, PLDI'20](https://www.cs.utexas.edu/~hovav/dist/vera.pdf)

### Program Synthesis
- [Optimal Program Synthesis via Abstract Interpretation, POPL'24](https://dl.acm.org/doi/10.1145/3632858)
- [babble: Learning Better Abstractions with E-Graphs and Anti-unification, POPL'23](https://dl.acm.org/doi/abs/10.1145/3571207)
- [FlashFill++: Scaling Programming by Example by Cutting to the Chase, POPL'23](https://dl.acm.org/doi/abs/10.1145/3571226)
- [Inductive Synthesis of Structurally Recursive Functional Programs from Non-recursive Expressions, POPL'23](https://dl.acm.org/doi/abs/10.1145/3571263)
- [DPGen: Automated Program Synthesis for Differential Privacy, CCS'21](https://arxiv.org/abs/2109.07441)
- [Data-Driven Synthesis of Provably Sound Side Channel Analyses, ICSE'21](https://ieeexplore.ieee.org/document/9402113)
- [Optimizing Homomorphic Evaluation Circuits by Program Synthesis and Term Rewriting, PLDI'20](https://dl.acm.org/doi/abs/10.1145/3385412.3385996)

### AI-based Programming Systems & Large Language Models
- [Large Language Models for Code: Security Hardening and Adversarial Testing, CCS'23](https://arxiv.org/abs/2302.05319)
- [Monitor-Guided Decoding of Code LMs with Static Analysis of Repository Context, NeurIPS'23](https://openreview.net/forum?id=qPUbKxKvXq&noteId=98Ukj82fSP)
- [Prompting Is Programming: A Query Language for Large Language Models, PLDI'23](https://dl.acm.org/doi/abs/10.1145/3591300)
- [Scallop: A Language for Neurosymbolic Programming, PLDI'23](https://dl.acm.org/doi/10.1145/3591280)
