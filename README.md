<div align="center">
<pre>ko@github:~$ ./research --focus graph
          ┌──○──○──┐
     (s)──┤        ├──(t)
          └──○──○──┘
GRAPH ALGORITHMS :: NETWORK SCIENCE</pre>

<h1>Ko Yamasaki</h1>

<p>
  B.Sc. candidate in Intelligent Systems at Hiroshima City University<br>
  Incoming master's student at Institute of Science Tokyo · April 2027
</p>

<p>
  <a href="https://koyamasaki.com">website</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/mosamosa-ko?tab=repositories">repositories</a>
</p>
</div>

## 01 / research

```yaml
problem:    graph-grammar membership testing
domain:     two-terminal series-parallel graphs
approach:   structural decomposition + algorithms
status:     undergraduate research in progress
visibility: private
```

I study how the recursive structure of TTSP graphs can support algorithms for deciding membership in graph-grammar languages. Results are not presented as complete or proved until they have been reviewed and are ready for release.

## 02 / build

### [`graph-algorithms-lab`](https://github.com/mosamosa-ko/graph-algorithms-lab)

[![CI](https://github.com/mosamosa-ko/graph-algorithms-lab/actions/workflows/ci.yml/badge.svg)](https://github.com/mosamosa-ko/graph-algorithms-lab/actions/workflows/ci.yml)

A public, independent implementation lab for graph algorithms and TTSP networks.

| Layer | What is implemented |
| --- | --- |
| **Structure** | Typed multigraphs, traversal, connectivity, series/parallel composition |
| **Algorithms** | TTSP generation, reduction-based recognition, S/P decomposition trees |
| **Verification** | pytest, exhaustive small instances, independent reference checks |
| **Experiments** | Reproducible benchmarks with raw measurements and environment metadata |

`Python 3.11+` · `pytest` · `Ruff` · `GitHub Actions`

## 03 / interests

```text
structure     graph algorithms · formal graph models · decomposition
learning      graph mining · graph neural networks · explainable AI
networks      network science · relational data · dynamic graphs
```

## 04 / method

```text
definition
    └──> algorithm
            └──> typed implementation
                    └──> independent checks
                            └──> reproducible experiment
```

I keep mathematical guarantees separate from empirical evidence. My work emphasizes explicit assumptions, testable interfaces, small-instance enumeration, independent oracles, and reproducible measurements.

## 05 / research queue

| Stage | Project | Intended scope |
| --- | --- | --- |
| `planned` | `gnn-from-scratch` | Message passing and GNN layers with tiny-graph reference checks |
| `planned` | `dynamic-graph-bench` | Correctness-first evaluation of algorithms under graph updates |

<p align="center"><sub>building from definitions, testing every layer</sub></p>
