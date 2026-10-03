# DSA in Java

A collection of Data Structures and Algorithms implemented in **Java**, built for learning, practice, and interview preparation.

![Java](https://img.shields.io/badge/Java-17%2B-orange?logo=openjdk)
![License](https://img.shields.io/badge/License-MIT-blue)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

---

## Table of Contents

- [About](#about)
- [Repository Structure](#repository-structure)
- [Topics Covered](#topics-covered)
- [Getting Started](#getting-started)
- [How to Run](#how-to-run)
- [Practice Problems](#practice-problems)
- [Progress Tracker](#progress-tracker)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

---

## About

This repository contains clean, well-commented Java implementations of core data structures and algorithms, along with solved problems from platforms like LeetCode, GeeksforGeeks, and HackerRank. Each solution includes time and space complexity notes.

## Repository Structure

```
dsa/
├── arrays/
├── strings/
├── linked-list/
├── stack-queue/
├── recursion-backtracking/
├── searching-sorting/
├── hashing/
├── trees/
├── heaps/
├── graphs/
├── dynamic-programming/
├── greedy/
├── bit-manipulation/
├── problems/            # Platform-wise solved problems
└── README.md
```

## Topics Covered

| Topic | Concepts |
|-------|----------|
| Arrays | Two pointers, sliding window, prefix sum, Kadane's algorithm |
| Strings | Palindromes, anagrams, KMP, Rabin-Karp |
| Linked List | Singly, doubly, circular, cycle detection, reversal |
| Stack & Queue | Monotonic stack, deque, priority queue, expression evaluation |
| Recursion & Backtracking | Subsets, permutations, N-Queens, Sudoku solver |
| Searching & Sorting | Binary search variants, merge sort, quick sort, heap sort |
| Hashing | HashMap, HashSet, frequency counting, custom hash table |
| Trees | Binary tree, BST, AVL, traversals, LCA, Trie, Segment tree |
| Heaps | Min/Max heap, top-K problems, heap sort |
| Graphs | BFS, DFS, Dijkstra, Bellman-Ford, Kruskal, Prim, Topological sort, Union-Find |
| Dynamic Programming | Knapsack, LIS, LCS, DP on grids, DP on strings, bitmask DP |
| Greedy | Interval scheduling, Huffman coding, activity selection |
| Bit Manipulation | Masks, XOR tricks, counting set bits |

## Getting Started

### Prerequisites

- Java JDK 17 or higher
- Git
- Any IDE (IntelliJ IDEA, Eclipse, VS Code) or just a terminal

Check your Java version:

```bash
java -version
```

### Clone the repository

```bash
git clone https://github.com/<your-username>/dsa.git
cd dsa
```

## How to Run

Compile and run any file from the terminal:

```bash
cd arrays
javac TwoSum.java
java TwoSum
```

Or open the project in your IDE and run the `main` method of any class.

## Practice Problems

Solutions follow a consistent format:

```java
/**
 * Problem: Two Sum
 * Platform: LeetCode #1
 * Approach: HashMap for O(1) lookups
 * Time Complexity: O(n)
 * Space Complexity: O(n)
 */
public class TwoSum {
    public static int[] twoSum(int[] nums, int target) {
        // implementation
    }

    public static void main(String[] args) {
        // test cases
    }
}
```

## Progress Tracker

| Topic | Solved | Total Target |
|-------|--------|--------------|
| Arrays | 0 | 50 |
| Strings | 0 | 30 |
| Linked List | 0 | 25 |
| Stack & Queue | 0 | 25 |
| Trees | 0 | 40 |
| Graphs | 0 | 40 |
| Dynamic Programming | 0 | 50 |
| **Total** | **0** | **260** |

## Contributing

Contributions, suggestions, and optimizations are welcome.

1. Fork the repository
2. Create a branch: `git checkout -b feature/new-solution`
3. Commit your changes: `git commit -m "Add: solution for <problem>"`
4. Push to the branch: `git push origin feature/new-solution`
5. Open a Pull Request

Please keep code well-commented and include complexity analysis.

## License

This project is licensed under the [MIT License](LICENSE).

## Author

**Your Name**
- GitHub: [@your-username](https://github.com/your-username)
- LinkedIn: [your-profile](https://www.linkedin.com/in/your-profile)

---

If this repo helps you, consider giving it a star.
