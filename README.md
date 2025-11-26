# 📘 **Titan DS**

An interactive, modern, and educational platform for visualizing **Data Structures & Algorithms** in real time.
Built using:

* ⚡ **React + TypeScript + Vite**
* 🎨 **Bootstrap 5** (UI styling)
* 🌀 **Framer Motion** (animations)
* 🔍 **Prism React Renderer** (code highlighting)
* 🧠 **Zustand** (state management)
* 📐 **D3-powered** layouts for Tree & Graph

This project is designed to help students, developers, and visual learners understand how data structures work — interactively and intuitively.

---

## 🚀 **Features**

### 🧱 Core Visualizers

* **Stack** → push, pop, clear with animations
* **Queue** → enqueue, dequeue
* **Linked List** → insert, delete, traverse
* **Binary Tree** → insert, inorder, preorder, postorder
* **Graph** → BFS, DFS, edge animations
* **Sorting** → bubble, selection, merge, quick sort with step-by-step visualization

### 🎨 UI & UX

* Clean, responsive UI using **Bootstrap 5**
* Split view layout:

  * Left → Visualizer
  * Right → Code Panel
* Sidebar for switching between structures
* Real-time traversal animations
* Adjustable animation speed
* Educational mode with highlighted code

### 🧠 Developer Friendly

* Fully modular folder structure
* Each DS has:

  * Its own visualizer
  * Control panel
  * Code snippet
  * Algorithms folder (for sorting, traversals, etc.)
* Easy to extend: add new DS in minutes
* Scalable & production-grade architecture

---

## 📁 **Project Structure**

```
src/
│
├── main.tsx
├── App.tsx
│
├── styles/
│   ├── globals.css
│   └── bootstrap-overrides.css
│
├── components/
│   ├── layout/
│   ├── ui/
│   ├── common/
│   ├── code/
│   ├── visualizers/
│   ├── animation/
│   └── placeholders/
│
├── data-structures/
├── store/
└── vite-env.d.ts
```

This structure ensures complete modularity and easy scaling.

---

## 🛠️ **Tech Stack**

| Category            | Tech                      |
| ------------------- | ------------------------- |
| Frontend Framework  | React + TypeScript + Vite |
| Styling             | Bootstrap 5, CSS          |
| Animations          | Framer Motion             |
| State Management    | Zustand                   |
| Code Highlighting   | Prism React Renderer      |
| Tree / Graph Layout | D3.js (force & hierarchy) |

---

## 📦 **Installation**

Clone the repository:

```bash
git clone https://github.com/DEMiHAT/titan-ds.git
cd titan-ds
```

Install dependencies:

```bash
npm install
```

Start the dev server:

```bash
npm run dev
```

Your app runs at:

```
http://localhost:5173
```

---

## 🧩 **Usage**

1. Pick a data structure from the left sidebar
2. Use the control panel (push, pop, insert, delete, traverse)
3. Watch animations update in real time
4. View code on the right panel to understand implementation
5. Modify or extend with your own algorithms

---

## 🧠 **Educational Purpose**

This project helps you understand:

* How data structures behave internally
* How algorithms work step-by-step
* How traversals move across nodes
* How sorting swaps happen visually
* How to use animations to explain logic

Perfect for:

* Students
* Programmers learning DSA
* Teachers/instructors
* Anyone who loves visual learning

---

## 🔧 **Extend This Project**

You can easily add new DS visualizers:

1. Create a new folder inside `components/visualizers/`
2. Add `YourDSVisualizer.tsx` and `YourDSControls.tsx`
3. Add code snippet in `components/code/ds-code/`
4. Add DS logic in `data-structures/`
5. Add Zustand store in `store/`
6. Add a new sidebar button
7. Done ✔

---

## 🤝 **Contributing**

Pull requests are welcome!
If you want to improve animations, add new DS, or clean up UI — feel free to contribute.

---

## 📜 **License**

MIT License – enjoy, learn, and build on top of this freely.

---

## ⭐ **Support**

If you like this project:

* ⭐ Star the repo
* 🔁 Share it
* 🧠 Use it to learn DSA
* 🚀 Extend it with your own visualizers

---

