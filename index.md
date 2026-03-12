---
layout: homepage
---

## About Me

Hi, I am a PhD student at Oregon State University studying theoretical computer science, advised by [Dr. Amir Nayyeri](https://web.engr.oregonstate.edu/~nayyeria/). 

## Research Interests

- **Combinatorics:** Within combinatorics, graph theory is of particular interest to me. I spend time thinking about various problems in graph theory; extremal problems, coloring, optimization, forbidden substructures, etc.
- **Algorithms** I enjoy thinking about algorithmic aspects, especially combinatorial algorithms. Combinatorial structures provide a rich playground for algorithms research.


## Things I'm Currently Thinking About
#### I will try to keep this section udpated as frequently as possible; last update March 2026
- The past year or so has still involved hidden graph reconstruction but I've really been mostly thinking about width parameters in graphs. A nice [paper](https://drops.dagstuhl.de/storage/00lipics/lipics-vol351-esa2025/LIPIcs.ESA.2025.69/LIPIcs.ESA.2025.69.pdf) by David Eppstein, Michael Goodrich, and Alfred Liu from UCI on the width parameter BFS-width and its relation to the well-studied bandwidth was presented at ESA 2025 last year. This inspired our most recent paper (submitted to a conference recently, will post here as soon as appropriate) extending their work to study the relationship between BFS-width and the cutwidth and pathwidth parameters, with a tiny application in graph reconstruction at the end (as BFS-width is a natural parameter to study for many BFS-based algorithms like the simplest reconstruction algorithms). 
  #### Nov 2024
- Thinking generally still about hidden graph reconstruction allowing for different oracles; many papers start using adversarial arguments and information theoretic arguments elegantly to prove lower bounds, which is always a blast to see! These techinques seem to play nicely with graph reconstruction problem variants, but there are probably bigger, more general sledgehammer techniques in this area out there.
- Expanding from just graph reconstruction, there are a few interesting questions; using shortest path metric oracles, which properties of graphs can you verify in better than soft O(n^2) time? Connectivity properties seem natural to look at with shortest path metric oracles
  #### Aug 2024
- A neat conjecture in graph theory: for a nontrivial connected graph F, there exists an F-irregular graph if and only if F is not isomorphic to K2. The forward direction is easily provable and there exists a P3-irregular graph, but I have no idea beyond this and I can't seem to find people seriously working on this.

## General Updates

- **[Aug. 2024]** I've created a [blog](https://chiragkaudan.github.io/ThoughtsBlogged/) containing my thoughts about (mostly) math things I find interesting.




{% include_relative _includes/publications.md %} 

