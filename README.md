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

## Grading
- Paper review & presentation: 40%
- Final project: 50%
- Participation: 10%

## Presentation
- Each student is required to give 4 presentations (midterm project, final project proposal, final project result, and paper presentation).
- Each student is required to give at least 1 question for each student presentation.

## Project Theme: Understandable & Explainable Program Analysis

## Academic Integrity Violation
Students who violate academic integrity will get an F.
See [the KAIST CS honor code](https://docs.google.com/forms/d/e/1FAIpQLSdSn63tEvq6R0G6n3Cz7jKX16RWvDy2giBKm8EVJtQHUBJoDA/viewform).

## Schedule
|Week|Topics|Reading|Homework|
|-|------|-------|--------|
|0|[Functional Programming in OCaml](slides/lecture0.pdf)||
|1|[Introduction](slides/lecture1.pdf)||HW0: OCaml Programming||
| |[Introduction to Program Synthesis](slides/lecture2.pdf)|PS Ch1-2, IPS Lec1|[HW1: Reading Critique](https://www.wired.com/story/ai-write-code-like-humans-bugs/)|
|2|[Inductive Synthesis and Enumerative Search](slides/lecture3.pdf)|PS Ch4.1, IPS Lec2-4||
| |[Search Space Pruning](slides/lecture4.pdf)|||
|3|[Search Space Prioritization](slides/lecture5.pdf)||[HW2: Reading Critique](https://cacm.acm.org/magazines/2018/12/232879-search-based-program-synthesis/fulltext)|
| |[Representation-based Search](slides/lecture6.pdf)||HW3: Program Synthesizer|
|4|[Program Synthesis and Verification](slides/lecture7.pdf)|||
| |[Introduction to Program Verification](slides/lecture8.pdf)|||
| |[Propositional Logic](slides/lecture9.pdf)|COC Ch1|
|5|[First-order Logic](slides/lecture10.pdf)|COC Ch2|
| |[First-order Theory](slides/lecture11.pdf)|COC Ch3|
|6|[Hoare Logic](slides/lecture12.pdf)|COC Ch5|[HW4: Reading Critique](https://cacm.acm.org/magazines/2021/7/253452-formal-software-verification-measures-up/fulltext)|
|7|[Automatic Verification using Contrained Horn Clauses](slides/lecture13.pdf)||HW5: Program Verifier|
| |Midterm Project Presentation (1)|||
|8|Midterm Project Presentation (2)|||
| |No class (midterm week)|||
|9|Midterm Project Presentation (3)|||
| |Midterm Project Presentation (4)||[HW6: Final Project Proposal](https://kaist-asos22.hotcrp.com)|
|10|Proposal Review & Discussion|||
|  |No class (Children's day)|||
|11|No class (ICSE)|||
|  |Paper Presentation (1)|||
|12|Paper Presentation (2)|||
|  |No class (Graduate admission)|||
|13|Paper Presentation (3)|||
|  |Paper Presentation (4)|||
|14|Final Project Presentation (1)|||
|  |Final Project Presentation (2)||[HW7: Reading Critique](https://blog.sigplan.org/2021/11/04/neural-network-verification-where-are-we-and-where-do-we-go-from-here/)|
|15|Final Project Presentation (3)|||
|  |Final Project Presentation (4)|||
|16|Final Project Presentation (5)|||

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

## References
- [Fuzzle](https://softsec-kaist.github.io/Fuzzle/)
- [D3](https://d3js.org)
