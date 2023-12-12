# IS661: Advanced Software Security

## Logistics
- Instructor: [Kihong Heo](https://kihongheo.kaist.ac.kr) (kihong.heo@kaist.ac.kr)
- TAs (mailing list: is661.ta@prosys.kaist.ac.kr)
  - TBA
  - Time: TBA
- Office hour (by appointment):
  - Instructor: TBA
  - TAs: TBA
- Location: TBA

## Course Description
The goal of this course is to develop scientific communication skills.
Students will learn how to write a scientific paper, give a technical
talk, and review a research paper. Students will propose and complete
a research project during the semester.

In particular, the course consists of two parts:
- Paper review: each student is assigned several research papers to
  review. Students will learn how to critically read and understand
  a paper.
- Project: each student will propose and complete a research project
  during the semester. Students will learn how to find a research
  problem, propose a solution, and evaluate the solution.

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
underlying programming system. For example, the visualization tool can
provide the following benefits:
- Help researchers (e.g., yourself) find new research problems in program systems
- Help non-expert users understand the behavior of program analyzers

Students can refer to the following projects for inspiration:
- [James Webb Space Telescope](https://webb.nasa.gov)
- [Event Horizon Telescope](https://eventhorizontelescope.org)
- [Fuzzle](https://softsec-kaist.github.io/Fuzzle/)
- [D3](https://d3js.org)

## Academic Integrity Violation
Students who violate academic integrity will get an F.
See [the KAIST CS honor code](https://docs.google.com/forms/d/e/1FAIpQLSdSn63tEvq6R0G6n3Cz7jKX16RWvDy2giBKm8EVJtQHUBJoDA/viewform).

## Schedule
|#|Topics|Reading|
|-|------|-------|
|1|[Introduction](slides/lecture1.pdf)||||
|2|[How to Write a Great Research Paper](assets/simon-papers.pdf) [<img src="icons/youtube.png" width="16" />](https://www.youtube.com/watch?v=WP-FkUaOcOM)||
|3|[How to Write Papers So People Can Read Them](assets/talk-plmw16.pdf) [<img src="icons/youtube.png" width="16" />](https://www.youtube.com/watch?v=KfEVdMMY1aQ)||
|4|Paper Writing, Review, and Discussion||
|5|[How to Give a Great Research Talk](assets/simon-talks.pdf) [<img src="icons/youtube.png" width="16" />](https://www.youtube.com/watch?v=sT_-owjKIbA)||
|6|Student Presentation||
|7|[How to Write a Grant Proposal Talk](assets/simon-proposal.pdf) [<img src="icons/youtube.png" width="16" />](https://www.youtube.com/watch?v=nEuK54bo6RE)||
|8|Final Project Proposal (1)||
|9|Final Project Proposal (2)|||
|10|Paper Presentation (1)|||
|11|Paper Presentation (2)||
|12|Paper Presentation (3)||
|13|Paper Presentation (4)||
|14|Final Project Presentation (1)|||
|15|Final Project Presentation (2)|||

## Papers
### Program Synthesis
- [DPGen: Automated Program Synthesis for Differential Privacy, CCS'21](https://arxiv.org/abs/2109.07441)
- [Syntia: Synthesizing the Semantics of Obfuscated Code, USENIXSEC'17](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/blazytko)
- [Data-Driven Synthesis of Provably Sound Side Channel Analyses, ICSE'21](https://ieeexplore.ieee.org/document/9402113)
- [An Inductive Synthesis Framework for Verifiable Reinforcement Learning, PLDI'19](https://dl.acm.org/doi/10.1145/3314221.3314638)
- [Optimizing Homomorphic Evaluation Circuits by Program Synthesis and Term Rewriting, PLDI'20](https://dl.acm.org/doi/abs/10.1145/3385412.3385996)
- [Synthesizing Highly Expressive SQL Queries from Input-Output Examples, PLDI'17](https://dl.acm.org/doi/10.1145/3062341.3062365)
- [Combinatorial sketching for finite programs, ASPLOS'06](https://dl.acm.org/doi/10.1145/1168919.1168907)
- [Synthesis of Data Completion Scripts using Finite Tree Automata, OOPSLA'17](https://dl.acm.org/doi/10.1145/3133886)

### Program Verification
- [Verifying Correct Usage of Context-Free API Protocols, POPL'19](https://dl.acm.org/doi/10.1145/3434298)
- [Verified Three-Way Program Merge, OOPSLA'18](https://dl.acm.org/doi/10.1145/3276535)
- [Alive2: bounded translation validation for LLVM, PLDI'21](https://dl.acm.org/doi/10.1145/3453483.3454030)
- [Reluplex: An efficient SMT solver for verifying deep neural networks, CAV'17](https://link.springer.com/chapter/10.1007/978-3-319-63387-9_5)
- [Formally Verified Mathematics, CACM'14](https://dl.acm.org/doi/pdf/10.1145/2591012)
- [Verifying Constant-Time Implementations, USENIXSEC'16](https://www.usenix.org/conference/usenixsecurity16/technical-sessions/presentation/almeida)
- [Towards a Verified Range Analysis for JavaScript JITs, PLDI'20](https://www.cs.utexas.edu/~hovav/dist/vera.pdf)
- [VERISMART: A Highly Precise Safety Verifier for Ethereum Smart Contracts, SNP'20](http://prl.korea.ac.kr/~pronto/home/papers/snp20.pdf)
