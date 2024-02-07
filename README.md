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
- Paper review: 40%
- Final project: 50%
- Participation: 10%

## Project Theme: Understandable & Explainable Programming Systems
Observation is the beginning of all sciences.
For example, Heliocentrism, one of the most important scientific discovery,
started from several critical observation by Galileo Galilei.
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

## Schedule
|#|Topics|Reading/Watching|Homework|
|-|------|:--------------:|--------|
|1|[Introduction](slides/lecture1.pdf)||||
|2|[You and Your Research](https://www.cs.virginia.edu/~robins/YouAndYourResearch.html)|[<img src="icons/youtube.png" width="16" />](https://www.youtube.com/watch?v=a1zDuOPkMSw)|HW1: Essay|
|3|[How to Write a Great Research Paper](assets/simon-papers.pdf)|[<img src="icons/youtube.png" width="16" />](https://www.youtube.com/watch?v=WP-FkUaOcOM)|HW2: Essay|
|4|[How to Write Papers So People Can Read Them](assets/talk-plmw16.pdf)|[<img src="icons/youtube.png" width="16" />](https://www.youtube.com/watch?v=KfEVdMMY1aQ)|HW3: Essay|
|5|Paper Writing, Review, and Discussion||[HW4: Write your quick sort paper](quicksort.md)|
|6|[How to Give a Great Research Talk](assets/simon-talks.pdf)|[<img src="icons/youtube.png" width="16" />](https://www.youtube.com/watch?v=sT_-owjKIbA)|HW3: Essay|
|7|Research Talk||HW5: Present your quick sort|
|8|[How to Write a Grant Proposal Talk](assets/simon-proposal.pdf)|[<img src="icons/youtube.png" width="16" />](https://www.youtube.com/watch?v=nEuK54bo6RE)|HW6: Essay |
|9|Project Proposal Presentation (1)||HW7: Project Proposal|
|10|Project Proposal Presentation (2)|||
|11|Paper Presentation||HW8: Paper Review|
|12|Final Project Presentation|||

## Papers
### Program Analysis & Testing
- [Abstract Interpretation of Fixpoint Iterators with Applications to Neural Networks, PLDI'23](https://arxiv.org/abs/2110.08260)
- [Compiler Test-Program Generation via Memoized Configuration Search, ICSE'23](https://ieeexplore.ieee.org/document/10172512)

### Program Verification
- [Formally Verified Native Code Generation in an Effectful JIT: Turning the CompCert Backend into a Formally Verified JIT Compiler, POPL'23](https://dl.acm.org/doi/abs/10.1145/3571202)
- [Alive2: bounded translation validation for LLVM, PLDI'21](https://dl.acm.org/doi/10.1145/3453483.3454030)
- [Towards a Verified Range Analysis for JavaScript JITs, PLDI'20](https://www.cs.utexas.edu/~hovav/dist/vera.pdf)

### Program Synthesis
- [babble: Learning Better Abstractions with E-Graphs and Anti-unification,POPL'23](https://dl.acm.org/doi/abs/10.1145/3571207)
- [FlashFill++: Scaling Programming by Example by Cutting to the Chase, POPL'23](https://dl.acm.org/doi/abs/10.1145/3571226)
- [Inductive Synthesis of Structurally Recursive Functional Programs from Non-recursive Expressions, POPL'23](https://dl.acm.org/doi/abs/10.1145/3571263)
- [DPGen: Automated Program Synthesis for Differential Privacy, CCS'21](https://arxiv.org/abs/2109.07441)
- [Data-Driven Synthesis of Provably Sound Side Channel Analyses, ICSE'21](https://ieeexplore.ieee.org/document/9402113)
- [Optimizing Homomorphic Evaluation Circuits by Program Synthesis and Term Rewriting, PLDI'20](https://dl.acm.org/doi/abs/10.1145/3385412.3385996)

### AI-based Programming Systems
- [Prompting Is Programming: A Query Language for Large Language Models, PLDI'23](https://dl.acm.org/doi/abs/10.1145/3591300)
