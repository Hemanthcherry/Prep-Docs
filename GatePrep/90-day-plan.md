# GATE 2027 CS — 90-day plan

Class A, B, or C decides how much time, practice, and revision a topic gets. It does not remove a topic. All 176 official rows in `syllabus-checklist.md` appear in this plan. Mastery is recorded only in `progress-dashboard.md`.

## Day shape

Planning assumption: 6 hours a day.

| Part of the day | Time | What it covers |
| --- | --- | --- |
| General Aptitude | 45 minutes, every day | All 40 GA rows. This is the 68-hour GA budget. |
| Computer Science block | about 5 hours 15 minutes on study days | The block for that day, below. |
| Mock day | 3-hour paper + analysis, GA kept short | Counts toward the 60-hour mock budget. |

Ten mock papers and 30 hours of weak-A redo sit on the days marked below. They are not extra days beyond 90.

If a real day is 4 hours or 8 hours, stretch or compress the block dates. Keep the order. Do not delete a C row to catch up. Cut depth inside an A topic’s extra problems before you cut a C topic’s two GATE-level problems.

## Why this order

- C programming, then data structures, then algorithms.
- Discrete mathematics is in the first three blocks because algorithms and theory of computation use it.
- Digital logic finishes before computer organization.
- Theory of computation finishes before compiler design.
- Operating systems and computer organization share one block.
- Databases come after algorithms.
- Networks come after operating systems.
- General Aptitude runs from day 1, because it is 15 of 100 marks.
- Engineering mathematics is not saved for the end. The numerical core is finished before algorithms.

## General Aptitude, every week

The 45-minute slot rotates. A rows come more often. C rows still come every week.

| Day | Official rows in the slot |
| --- | --- |
| Monday | GA-1.11 reading. GA-2.8 ratios. GA-2.9 percentages. |
| Tuesday | GA-2.1 bar graphs. GA-2.2 pie charts. GA-2.7 tables. GA-2.3 other graphs. |
| Wednesday | GA-2.12 permutations and combinations. GA-2.13 series. GA-2.10 powers. GA-2.11 exponents and logarithms. |
| Thursday | GA-2.14 mensuration and geometry. GA-3.1 deduction. GA-3.4 numerical relations. |
| Friday | GA-1.1 tenses. GA-1.2 articles. GA-1.4 prepositions. GA-1.6 verb-noun agreement. GA-1.8 words. GA-1.9 idioms. GA-1.10 phrases. GA-1.12 narrative sequencing. GA-3.3 analogy. GA-2.4 2-dimensional plots. GA-2.15 elementary statistics. |
| Saturday | GA-4.2 rotation. GA-4.4 mirroring. GA-4.7 paper folding. GA-4.9 patterns. One of GA-4.1, GA-4.3, GA-4.5, GA-4.6, GA-4.8. |
| Sunday | GA-1.3 adjectives. GA-1.5 conjunctions. GA-1.7 other parts of speech. GA-2.5 3-dimensional plots. GA-2.6 maps. GA-3.2 induction. Then a short closed-book mix of the A rows from Monday to Thursday. |

Sunday is where the C verbal, C spatial, and induction rows get their quota. They are not left to a final week.

## Computer Science blocks

Hours are the topic budgets from the dashboard. A block’s length is those hours at about 5 hours 15 minutes of CS per study day.

### Days 1–8 — Programming and logic

C programming before any data-structure design. Boolean algebra and Karnaugh maps start here because digital logic feeds computer organization later.

| IDs | Class mix | Hours |
| --- | --- | --- |
| PDS.1 Programming in C, PDS.2 Recursion, PDS.3 Arrays, PDS.4 Stacks, PDS.6 Linked lists | A | 22.5 |
| PDS.5 Queues | B | 2.5 |
| EM-D.1 Propositional logic, EM-D.2 First order logic, EM-D.4 Relations, EM-D.5 Functions | A | 8 |
| EM-D.3 Sets | A | 1.5 |
| DL.1 Boolean algebra, DL.3 Karnaugh map | A | 7 |

Block total: 41.5 hours.

On day 8, do the first revision pass of the A rows from this block (included in the hours).

### Days 9–15 — Trees, counting, circuit design

| IDs | Class mix | Hours |
| --- | --- | --- |
| PDS.7 Trees, PDS.8 Binary search trees, PDS.9 Binary heaps | A | 13.5 |
| PDS.10 Graphs | B | 2.5 |
| EM-D.13 Counting, EM-D.14 Recurrence relations | A | 4 |
| EM-D.15 Generating functions | C | 1 |
| EM-D.6 Partial orders, EM-D.7 Lattices, EM-D.9 Groups | B | 4.5 |
| EM-D.8 Monoids | C | 1 |
| DL.5 Combinational design, DL.6 Sequential design | A | 7 |
| DL.2 Algebraic minimization, DL.4 Tabular method | B | 4 |

Block total: 37.5 hours.

Generating functions and monoids are C. They still get their two basic and two GATE-level problems on days 12 and 14. They are not optional reading.

### Days 16–24 — Engineering mathematics numerical core, and number representation

This is the main numerical mathematics block: linear algebra, calculus, probability, and fixed/floating arithmetic.

| IDs | Class mix | Hours |
| --- | --- | --- |
| EM-L.1 Matrices, EM-L.3 Linear systems, EM-L.4 Eigenvalues | A | 6 |
| EM-L.2 Determinants | A | 1.5 |
| EM-L.5 LU decomposition | B | 1.5 |
| EM-C.1 Limits, EM-C.2 Continuity and differentiability | B | 3 |
| EM-C.3 Maxima and minima, EM-C.5 Integration | B | 2 |
| EM-C.4 Mean value theorem | C | 1 |
| EM-P.1 Random variables, EM-P.3 Normal, EM-P.4 Exponential, EM-P.5 Poisson, EM-P.6 Binomial, EM-P.8 Standard deviation, EM-P.9 Conditional probability, EM-P.10 Bayes | A | 16 |
| EM-P.7 Mean, median, mode | A | 1.5 |
| EM-P.2 Uniform distribution | B | 1 |
| EM-D.10 Connectivity, EM-D.11 Matching, EM-D.12 Colouring | B | 4.5 |
| DL.7 Fixed-point representation, DL.8 Floating-point representation, DL.9 Fixed and floating arithmetic | A | 9 |

Block total: 47 hours.

Mean value theorem is C and is scheduled on day 20 with maxima and integration, not dropped.

### Days 25–32 — Algorithms

Starts only after arrays, trees, heaps, graphs, counting, and recurrence relations.

| IDs | Class | Hours |
| --- | --- | --- |
| ALG.2 Sorting, ALG.3 Hashing, ALG.4 Time complexity, ALG.6 Greedy, ALG.7 Dynamic programming, ALG.8 Divide-and-conquer, ALG.9 Traversals, ALG.10 Minimum spanning trees, ALG.11 Shortest paths | A | 36 |
| ALG.1 Searching, ALG.5 Space complexity | B | 4 |

Block total: 40 hours.

### Day 33 — Sectional mock 1

Syllabus in the paper: Engineering Mathematics, Digital Logic, Programming and Data Structures, Algorithms, plus the usual General Aptitude. Same-day analysis. Log misses against the dashboard ids. Do not open a new subject today.

### Days 34–40 — Theory of computation

| IDs | Class | Hours |
| --- | --- | --- |
| TOC.1 Regular expressions, TOC.2 Finite automata, TOC.3 Context-free grammars, TOC.4 Push-down automata, TOC.5 Regular languages, TOC.6 Context-free languages | A | 27 |
| TOC.9 Undecidability | A | 4 |
| TOC.7 Pumping lemma, TOC.8 Turing machines | B | 5 |

Block total: 36 hours.

### Days 41–45 — Compiler design

Starts after theory of computation.

| IDs | Class | Hours |
| --- | --- | --- |
| CD.2 Parsing, CD.3 Syntax-directed translation, CD.5 Intermediate code | A | 12 |
| CD.1 Lexical analysis, CD.4 Runtime environments, CD.6 Local optimisation, CD.7 Constant propagation, CD.8 Liveness, CD.9 Common subexpression elimination | B | 15 |

Block total: 27 hours.

The three named data-flow analyses are B. Each gets its own problems on days 44 and 45.

### Day 46 — Sectional mock 2

Theory of computation, compiler design, and a short mix of algorithms and mathematics. Analysis the same day.

### Days 47–60 — Computer organization and operating systems together

Digital logic is already done. These two subjects share cache, interrupts, DMA, and memory, so the days alternate rather than finishing one and then starting the other.

| Days | IDs | Hours |
| --- | --- | --- |
| 47–48 | COA.1 Instruction set, COA.2 Addressing modes | 9 |
| 49 | COA.3 ALU design, COA.4 Hardwired control, COA.5 Microprogrammed control | 7.5 |
| 50 | COA.6 Memory interfacing (C, full quota), COA.9 Interrupt, COA.10 DMA | 6 |
| 51–52 | COA.7 Memory-hierarchy performance, COA.8 Cache mapping | 9 |
| 53–54 | COA.11 Pipelining, COA.12 Pipeline hazards | 8.5 |
| 55 | OS.1 System calls (C, full quota), OS.2 Processes, OS.3 Threads | 8.5 |
| 56–57 | OS.4 Inter-process communication, OS.5 Synchronization | 7 |
| 58 | OS.6 Deadlock, OS.8 I/O scheduling (C, full quota) | 6 |
| 59 | OS.7 CPU scheduling, OS.11 File systems | 6.5 |
| 60 | OS.9 Memory management, OS.10 Virtual memory | 8 |

Block total: 76 hours. COA is 40. OS is 36.

COA.6, OS.1, and OS.8 are the C rows. Each has a named day above.

### Day 61 — Sectional mock 3

Computer organization and operating systems, with a few digital-logic and cache-style numericals. Analysis the same day.

### Days 62–68 — Databases

After algorithms, so indexing and B/B+ tree cost arguments sit on top of trees and hashing.

| IDs | Class | Hours |
| --- | --- | --- |
| DB.1 ER-model, DB.3 Relational algebra, DB.5 SQL, DB.7 Normal forms, DB.9 Indexing, DB.10 B and B+ trees, DB.11 Transactions, DB.12 Concurrency control | A | 28 |
| DB.2 Relational model, DB.4 Tuple calculus, DB.6 Integrity constraints, DB.8 File organization | B | 8 |

Block total: 36 hours.

### Days 69–76 — Computer networks

After operating systems, so TCP and the socket API have a process and I/O context. The rows are the GATE 2027 list only.

| Days | IDs | Hours |
| --- | --- | --- |
| 69 | CN.1 Layering, CN.2 Circuit switching, CN.3 Packet switching, CN.4 Virtual circuit | 8 |
| 70 | CN.5 Performance metrics, CN.6 Error detection | 6 |
| 71 | CN.7 Medium access control, CN.8 Ethernet, CN.16 Socket API (C, full quota) | 4.5 |
| 72–73 | CN.9 Distance vector, CN.10 Link state, CN.11 IPv4 fragmentation, CN.12 CIDR | 12 |
| 74 | CN.13 NAT, CN.17 DNS, CN.18 HTTP | 4.5 |
| 75–76 | CN.14 TCP flow control, CN.15 TCP congestion control, plus the second revision pass for the A network rows | 6 |

Block total: 41 hours.

CN.16 is C and is on day 71 with its two basic and two GATE-level problems.

### Days 77–90 — Full mocks, closed-book A topics, and the C revision pass

No new official topic starts here. Every row has already had its first pass.

| Day | Work |
| --- | --- |
| 77 | Full mock 4. Analysis the same day. Each miss is tagged with a dashboard id. |
| 78 | Redo the A ids missed on mock 4. Closed-book set only. |
| 79 | Full mock 5, then analysis. |
| 80 | Redo those A ids. |
| 81 | Full mock 6, then analysis. |
| 82 | Redo, and the single revision pass for every C id: GA-1.3, GA-1.5, GA-1.7, GA-2.5, GA-2.6, GA-3.2, GA-4.1, GA-4.3, GA-4.5, GA-4.6, GA-4.8, EM-D.8, EM-D.15, EM-C.4, COA.6, OS.1, OS.8, CN.16. |
| 83 | Full mock 7, then analysis. |
| 84 | Redo the A ids that are still not closed-book. |
| 85 | Full mock 8, then analysis. |
| 86 | B-row second revision for any B id whose revision box is still open. |
| 87 | Full mock 9, then analysis. |
| 88 | A-row third revision: formulas and one fresh numerical from each weak A subject. |
| 89 | Full mock 10, then analysis. |
| 90 | Formula sheets only for rows whose Mastered cell is still `no`. No new material. |

That is 7 full mocks plus the 3 sectional mocks on days 33, 46, and 61: 10 mocks, 60 hours with analysis. The redo days are the 30-hour weak-A budget.

## What “done for today” means

At the end of a topic’s last day inside its block, the dashboard may show Theory, Basic, and GATE-level checked. PYQ stays open until the question is a verified past paper with year, paper, marks, and official key. Mastered stays `no` until all seven boxes are checked, including the later revision and the closed-book set.

A C topic uses the smaller quota. The seven boxes are the same.

## If a block overruns

Finish the current A topic’s GATE-level quota, then the C topic’s smaller quota, then move. Leave the B advanced problem for the subject-end revision rather than pushing the next dependency block past its start date. Algorithms do not start before trees, heaps, counting, and recurrence relations. Compiler design does not start before finite automata and context-free grammars. Computer organization does not start before combinational design, sequential design, and number representation.
