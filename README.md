<div align="center">

# C / A* Grid Search With Binary Heap

**A* pathfinding built from first principles in C.**

`C11` · Educational implementation · Source available

[Concept](#concept) • [Run](#run) • [Source tour](#source-tour) • [Caveats](#caveats)

</div>

---

## Concept

Low-level route planner on a blocked grid using an admissible Manhattan heuristic, priority heap and parent-chain reconstruction. Includes an executable expected-route assertion.

## Run

```bash
make
```
Review the included `Makefile` for specific targets.

## Source tour

| In this repository | Role |
|:--|:--|
| [`Makefile`](./Makefile) | Build targets |
| [`README.md`](./README.md) | Technical context |
| [`astar.c`](./astar.c) | C implementation |

## Caveats

Treat this as a reproducible educational project. Simulation outputs depend on the project assumptions; use synthetic inputs, inspect edge cases and review the source before applying any approach to a production system.

<details>
<summary>Original documentation and implementation notes</summary>

# C / A* Grid Search With Binary Heap

Low-level route planner on a blocked grid using an admissible Manhattan heuristic, priority heap and parent-chain reconstruction. Includes an executable expected-route assertion.

```bash
make
```

For larger graphs, use decrease-key / heap generations to avoid repeated insertions. The demo is deterministic.

</details>

---

<sub>Code and commentary in the [Sharanya Pal project index](https://github.com/sharanyapal?tab=repositories).</sub>
