# Topic 7: Data Structures, Database & OS (70 Q)

<details>
<summary><b>Q: Stack?</b></summary>
<blockquote><b>Answer:</b> LIFO (Last-In-First-Out). Operations: push, pop, peek</blockquote>
</details>

<details>
<summary><b>Q: Queue?</b></summary>
<blockquote><b>Answer:</b> FIFO (First-In-First-Out). Operations: enqueue, dequeue</blockquote>
</details>

<details>
<summary><b>Q: Linked List?</b></summary>
<blockquote><b>Answer:</b> Linear structure with nodes. Types: Singly, Doubly, Circular</blockquote>
</details>

<details>
<summary><b>Q: Binary Tree?</b></summary>
<blockquote><b>Answer:</b> Each node has ≤2 children. Root at top, leaves at bottom</blockquote>
</details>

<details>
<summary><b>Q: BST (Binary Search Tree)?</b></summary>
<blockquote><b>Answer:</b> Left child < parent < right child. Enables efficient search</blockquote>
</details>

<details>
<summary><b>Q: Big O notation?</b></summary>
<blockquote><b>Answer:</b> Worst-case time complexity. O(1), O(n), O(n log n), O(n²), O(2^n)</blockquote>
</details>

<details>
<summary><b>Q: Inorder traversal?</b></summary>
<blockquote><b>Answer:</b> Left → Root → Right</blockquote>
</details>

<details>
<summary><b>Q: Preorder traversal?</b></summary>
<blockquote><b>Answer:</b> Root → Left → Right</blockquote>
</details>

<details>
<summary><b>Q: Postorder traversal?</b></summary>
<blockquote><b>Answer:</b> Left → Right → Root</blockquote>
</details>

<details>
<summary><b>Q: Bubble Sort complexity?</b></summary>
<blockquote><b>Answer:</b> O(n²) best and worst</blockquote>
</details>

<details>
<summary><b>Q: Quick Sort complexity?</b></summary>
<blockquote><b>Answer:</b> O(n log n) average, O(n²) worst</blockquote>
</details>

<details>
<summary><b>Q: Merge Sort complexity?</b></summary>
<blockquote><b>Answer:</b> O(n log n) always</blockquote>
</details>

<details>
<summary><b>Q: Hash Table?</b></summary>
<blockquote><b>Answer:</b> Maps keys to values using hash function. O(1) average lookup</blockquote>
</details>

<details>
<summary><b>Q: Collision resolution?</b></summary>
<blockquote><b>Answer:</b> Chaining (linked lists), Open addressing (linear/quadratic probing)</blockquote>
</details>

<details>
<summary><b>Q: DFS (Depth-First Search)?</b></summary>
<blockquote><b>Answer:</b> Uses stack. Explores deeply. Path depends on order</blockquote>
</details>

<details>
<summary><b>Q: BFS (Breadth-First Search)?</b></summary>
<blockquote><b>Answer:</b> Uses queue. Explores level by level. Finds shortest path</blockquote>
</details>

<details>
<summary><b>Q: Dijkstra's Algorithm?</b></summary>
<blockquote><b>Answer:</b> Shortest path in weighted graph. Greedy approach</blockquote>
</details>

<details>
<summary><b>Q: Dynamic Programming?</b></summary>
<blockquote><b>Answer:</b> Break problem into overlapping subproblems. Store results (memoization)</blockquote>
</details>

<details>
<summary><b>Q: DBMS purpose?</b></summary>
<blockquote><b>Answer:</b> Manages data storage, retrieval, organization, security</blockquote>
</details>

<details>
<summary><b>Q: E-R model?</b></summary>
<blockquote><b>Answer:</b> Entities (objects), Attributes (properties), Relationships</blockquote>
</details>

<details>
<summary><b>Q: Normalization?</b></summary>
<blockquote><b>Answer:</b> Reduces data redundancy and anomalies</blockquote>
</details>

<details>
<summary><b>Q: 1NF (First Normal Form)?</b></summary>
<blockquote><b>Answer:</b> Atomic values only. No repeating groups</blockquote>
</details>

<details>
<summary><b>Q: 2NF (Second Normal Form)?</b></summary>
<blockquote><b>Answer:</b> 1NF + no partial dependencies</blockquote>
</details>

<details>
<summary><b>Q: 3NF (Third Normal Form)?</b></summary>
<blockquote><b>Answer:</b> 2NF + no transitive dependencies</blockquote>
</details>

<details>
<summary><b>Q: SQL DDL commands?</b></summary>
<blockquote><b>Answer:</b> CREATE, DROP, ALTER (define structure)</blockquote>
</details>

<details>
<summary><b>Q: SQL DML commands?</b></summary>
<blockquote><b>Answer:</b> INSERT, UPDATE, DELETE, SELECT (manipulate data)</blockquote>
</details>

<details>
<summary><b>Q: ACID properties?</b></summary>
<blockquote><b>Answer:</b> Atomicity (all/nothing), Consistency (valid), Isolation (independent), Durability (persistent)</blockquote>
</details>

<details>
<summary><b>Q: Transaction?</b></summary>
<blockquote><b>Answer:</b> Unit of work. Commit (save) or Rollback (undo)</blockquote>
</details>

<details>
<summary><b>Q: Lock-based concurrency?</b></summary>
<blockquote><b>Answer:</b> Read lock (shared), Write lock (exclusive) prevent conflicts</blockquote>
</details>

<details>
<summary><b>Q: OS purpose?</b></summary>
<blockquote><b>Answer:</b> Manages hardware. Provides services to applications</blockquote>
</details>

<details>
<summary><b>Q: Process vs Program?</b></summary>
<blockquote><b>Answer:</b> Program: Static code. Process: Running instance of program</blockquote>
</details>

<details>
<summary><b>Q: Process states?</b></summary>
<blockquote><b>Answer:</b> New, Ready, Running, Waiting, Terminated</blockquote>
</details>

<details>
<summary><b>Q: CPU Scheduling: FCFS?</b></summary>
<blockquote><b>Answer:</b> First Come First Served. Simple but can starve short jobs</blockquote>
</details>

<details>
<summary><b>Q: CPU Scheduling: Round Robin?</b></summary>
<blockquote><b>Answer:</b> Time-slice (quantum). Fair, prevents starvation</blockquote>
</details>

<details>
<summary><b>Q: CPU Scheduling: SJF?</b></summary>
<blockquote><b>Answer:</b> Shortest Job First. Minimizes average waiting, but starves long jobs</blockquote>
</details>

<details>
<summary><b>Q: Semaphore?</b></summary>
<blockquote><b>Answer:</b> Integer variable. P (wait/down): decrease. V (signal/up): increase</blockquote>
</details>

<details>
<summary><b>Q: Mutex?</b></summary>
<blockquote><b>Answer:</b> Binary semaphore (0 or 1). Protects critical section</blockquote>
</details>

<details>
<summary><b>Q: Deadlock?</b></summary>
<blockquote><b>Answer:</b> Processes wait indefinitely for resources. Circular wait</blockquote>
</details>

<details>
<summary><b>Q: Deadlock necessary conditions (4)?</b></summary>
<blockquote><b>Answer:</b> Mutual exclusion, Hold and wait, No preemption, Circular wait</blockquote>
</details>

<details>
<summary><b>Q: Deadlock prevention?</b></summary>
<blockquote><b>Answer:</b> Break one condition (usually circular wait via resource ordering)</blockquote>
</details>

<details>
<summary><b>Q: Deadlock avoidance?</b></summary>
<blockquote><b>Answer:</b> Banker's Algorithm. Grant resources only if system remains safe</blockquote>
</details>

<details>
<summary><b>Q: Page fault?</b></summary>
<blockquote><b>Answer:</b> Referenced page not in memory. OS loads from disk</blockquote>
</details>

<details>
<summary><b>Q: Effective access time?</b></summary>
<blockquote><b>Answer:</b> EAT = (1-p)×M + p×(M + F) (p=fault rate, M=memory time, F=fault service time)</blockquote>
</details>

<details>
<summary><b>Q: File system?</b></summary>
<blockquote><b>Answer:</b> Organizes data storage. Directories, files, access permissions</blockquote>
</details>

<details>
<summary><b>Q: Segmentation?</b></summary>
<blockquote><b>Answer:</b> Divides memory into variable-size segments. Matches logical structure</blockquote>
</details>

---

**Total: 70 Questions** | Focus: Sorting, BST, SQL, transactions, scheduling, deadlock, memory management
