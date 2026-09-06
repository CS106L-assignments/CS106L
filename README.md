# CS106L starter-code, test, and visual-validation bundle

This bundle contains **starter code, assignment documents, and visible tests only**. It intentionally excludes every `solutions/` directory and all Git metadata.

## Layout

1. `01-GraphViz` — graph visualization algorithm. It has no local unit-test harness; validate its output visually against the course live demo and examples.
2. `01-WikiRacer/Part1` — user-facing file input/output layer.
3. `01-WikiRacer/Part2` — link extraction and ladder-search layer; includes `test-wikiscraper.sh` and `test-wikiscraper.cpp`.
4. `02-GapBuffer` — gap-buffer container with `gap_buffer_test.cc`.
5. `03-HashMap` — HashMap with functional and performance tests.
6. `04-KDTree` — k-d tree with `kd_tree_test.cc`.

GraphViz and WikiRacer are peer first-stage projects. In Winter 2020 they were alternatives; this self-study bundle includes both. WikiRacer itself is sequential: finish Part1 before Part2.

## Provenance and version scope

- GraphViz: [CS106L Winter 2020 Assignment 1](https://web.stanford.edu/class/archive/cs/cs106l/cs106l.1204/assignments.html)
- WikiRacer Part1: `https://github.com/snme/cs106L-assignment1`
- WikiRacer Part2: `https://github.com/snme/cs106L-assignment2`
- GapBuffer, HashMap, KDTree: `https://github.com/wengwz/CS106L-Self-Learning/tree/main/assignments`

This is a cross-semester self-study collection, not one byte-identical course offering. GraphViz belongs to Winter 2020; the WikiRacer repositories are public starter repositories from a later CS106L offering; GapBuffer, HashMap, and KDTree are CMake/GoogleTest-adapted practice projects.

## Important environment note

`01-WikiRacer/Part1/wikiscraper.cpp.o` is a precompiled 64-bit GNU/Linux object file. Use WSL/Linux for that original Part1 setup; do not expect the supplied binary object to link directly in native Windows toolchains.

Each project directory contains its own `README.md` and build/test instructions. No setup scripts were executed while preparing this bundle.

# CS106L Assignment Link
https://web.stanford.edu/class/archive/cs/cs106l/cs106l.1232/assignment1.html
https://web.stanford.edu/class/archive/cs/cs106l/cs106l.1204/index.html
https://web.stanford.edu/class/cs106l/

