# 🗄️ DSA Pattern Vault

A sleek, single-file interactive reference for mastering Data Structures & Algorithms — organized by pattern, sorted by difficulty, and built to survive interview season.

![DSA Pattern Vault](https://img.shields.io/badge/Patterns-39-63d2ff?style=flat-square) ![Problems](https://img.shields.io/badge/Problems-250%2B-a78bfa?style=flat-square) ![Easy](https://img.shields.io/badge/Easy-36-34d399?style=flat-square) ![Medium](https://img.shields.io/badge/Medium-149-fb923c?style=flat-square) ![Hard](https://img.shields.io/badge/Hard-67-f87171?style=flat-square) ![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## ✨ Features

- **39 patterns** across 12 categories, covering every major DSA topic
- **250+ LeetCode problems** sorted Easy → Medium → Hard within each pattern
- **Direct LeetCode links** — click any problem to open it in a new tab
- **Collapsible categories** — expand only what you're studying
- **Sidebar navigation** — jump to any pattern instantly
- **Search** — filter patterns by name in real time
- **Difficulty filter** — view All / Easy / Medium / Hard problems across all patterns
- **Grid & List view** toggle
- **Fully self-contained** — one `.html` file, no server, no install, no dependencies

---

## 🚀 Usage

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/dsa-pattern-vault.git

# Open in browser — that's it
open dsa-patterns.html
```

No npm install. No build step. Just open the file.

---

## 📚 Pattern Categories

### 📦 Arrays & Strings
| # | Pattern |
|---|---------|
| 1 | 🪟 Sliding Window |
| 2 | 👆 Two Pointers |
| 3 | ∑ Prefix Sum |
| 4 | 📈 Kadane's Algorithm |
| 5 | 🔀 Sorting Tricks |

### 🔍 Binary Search
| # | Pattern |
|---|---------|
| 6 | 🎯 Classic Binary Search |
| 7 | 📐 Binary Search on Answer |

### 🔗 Linked Lists
| # | Pattern |
|---|---------|
| 8 | 🐢 Fast & Slow Pointers |
| 9 | ↩️ In-Place Reversal |

### 📚 Stacks & Queues
| # | Pattern |
|---|---------|
| 10 | 📊 Monotonic Stack |
| 11 | 🌊 Monotonic Deque |

### 🌳 Trees
| # | Pattern |
|---|---------|
| 12 | 🌿 Tree DFS |
| 13 | 🏔️ Tree BFS / Level Order |
| 14 | 🔍 Binary Search Tree |

### 🕸️ Graphs
| # | Pattern |
|---|---------|
| 15 | 🗺️ Graph DFS / BFS |
| 16 | 📋 Topological Sort |
| 17 | 🔗 Union Find (DSU) |
| 18 | 🛣️ Shortest Path (Dijkstra) |

### 🧩 Dynamic Programming
| # | Pattern |
|---|---------|
| 19 | 📏 1D DP |
| 20 | 🔲 2D / Grid DP |
| 21 | 🎒 Knapsack |
| 22 | 📐 Interval DP |
| 23 | 🔢 Digit DP |
| 24 | 🧿 Bitmask DP |
| 25 | 📈 Stock / State Machine DP |

### 🎲 Backtracking
| # | Pattern |
|---|---------|
| 26 | 🧰 Subsets / Combinations |
| 27 | 🔄 Permutations |
| 28 | ♟️ Constraint Satisfaction |

### ⚡ Heap & Priority Queue
| # | Pattern |
|---|---------|
| 29 | 🏆 Top K Elements |
| 30 | ⚖️ Two Heaps (Median) |
| 31 | 🔀 K-way Merge |

### 🔤 Strings & Hashing
| # | Pattern |
|---|---------|
| 32 | 🗃️ Hash Map Patterns |
| 33 | 🔡 Trie |
| 34 | 🔎 String Matching (KMP) |

### 🔢 Math & Bit Manipulation
| # | Pattern |
|---|---------|
| 35 | ⚙️ Bit Manipulation |
| 36 | 🧮 Math Tricks |

### 🏗️ Advanced Data Structures
| # | Pattern |
|---|---------|
| 37 | 📅 Merge Intervals / Sweep Line |
| 38 | 🌲 Segment Tree |
| 39 | 🌿 Fenwick Tree (BIT) |

---

## 🖥️ Preview

```
┌─────────────────────┬──────────────────────────────────────────────┐
│  DSA Pattern Vault  │  Master Every                                │
│  41 patterns ·      │  DSA Pattern                                 │
│  200+ problems      │                                              │
│  by Kishan Kumar    │  [39 Patterns] [252 Problems] [Easy] [Med]  │
│  Zalavadia          │                                              │
│  ─────────────────  │  📦 Arrays & Strings              ▼         │
│  > Arrays           │  ┌─────────────────────────────────────┐    │
│  > Binary Search    │  │ 🪟 Sliding Window                   │    │
│  > Linked Lists     │  │ #3  Longest Substring...   Medium  LC↗│  │
│  > Stacks           │  │ #76 Minimum Window...      Hard    LC↗│  │
│  > Trees            │  └─────────────────────────────────────┘    │
│  > Graphs           │                                              │
│  > DP               │                                              │
└─────────────────────┴──────────────────────────────────────────────┘
```

---

## 🛠️ Tech Stack

- **Vanilla HTML/CSS/JS** — zero frameworks, zero dependencies
- **Google Fonts** — Syne + Space Mono for the dark-terminal aesthetic
- **Single file** — everything inlined, fully portable

---

## 🤝 Contributing

Found a missing pattern or wrong difficulty label? PRs welcome.

1. Fork the repo
2. Edit `dsa-patterns.html` — patterns live in the `CATS` array in the `<script>` section
3. Follow the existing schema:
```js
{
  id: 40,
  name: "Pattern Name",
  icon: "🔥",
  accent: "#63d2ff",
  desc: "Short description of the technique.",
  problems: [
    { num: 1, name: "Two Sum", diff: "easy", slug: "two-sum" },
  ]
}
```
4. Open a PR

---

## 👤 Author

**Kishan Kumar Zalavadia**  
Full-Stack Software Engineer · M.S. Computer Science, University of North Texas  
[GitHub](https://github.com/YOUR_USERNAME) · [LinkedIn](https://linkedin.com/in/YOUR_PROFILE)

---

## 📄 License

MIT — use it, fork it, study with it. Good luck with the interviews. 🚀
