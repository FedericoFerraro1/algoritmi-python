# Algorithms in Python

Classic algorithms and data structures implemented from scratch in Python 3,
each with unit tests and a short note on time and space complexity.

I'm a Computer Engineering student at the University of Palermo. I'm using this
repository to learn Python properly and to study for my Algorithms exam:
every algorithm here is written by me, tested, and explained.

## Goals

- Implement each algorithm **without** using library shortcuts (no `sorted()` for sorting, etc.)
- Back every implementation with **tests** (`pytest`)
- Document **time and space complexity** in each docstring
- Keep a clean, readable commit history

## Repository structure

```
algoritmi-python/
├── sorting/
│   ├── insertion_sort.py
│   └── test_insertion_sort.py
├── searching/
├── data_structures/
├── graphs/
└── dynamic_programming/
```

Each algorithm lives in its own file, with its tests right next to it.

## Getting started

Requirements: Python 3.10+ and `pytest`.

```bash
git clone https://github.com/FedericoFerraro1/algoritmi-python.git
cd algoritmi-python
pip install pytest
python -m pytest
```

## Roadmap

### Sorting
- [ ] Insertion sort
- [ ] Merge sort
- [ ] Quicksort
- [ ] Heapsort
- [ ] Counting sort

### Searching
- [ ] Binary search

### Data structures
- [ ] Stack and queue
- [ ] Linked list
- [ ] Binary search tree
- [ ] Hash table

### Graphs
- [ ] BFS and DFS
- [ ] Dijkstra's shortest path
- [ ] Minimum spanning tree (Kruskal / Prim)

### Dynamic programming
- [ ] Longest common subsequence
- [ ] 0/1 knapsack

## Example

```python
def insertion_sort(items: list) -> list:
    """Sort a list in ascending order using insertion sort.

    Time:  O(n^2) worst/average case, O(n) best case (already sorted)
    Space: O(1) extra (sorts in place)
    """
```

## Author

**Federico Ferraro** — Computer Engineering student, University of Palermo
[LinkedIn](https://www.linkedin.com/in/ferraro-federico) · [GitHub](https://github.com/FedericoFerraro1)
