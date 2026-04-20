# Topic 4: Computer Organization & Embedded Systems (50 Q)

<details>
<summary><b>Q: Memory hierarchy from fastest to slowest?</b></summary>
<blockquote><b>Answer:</b> Registers → Cache → Main Memory → Secondary Storage</blockquote>
</details>

<details>
<summary><b>Q: Cache memory purpose?</b></summary>
<blockquote><b>Answer:</b> Fast storage between CPU and main memory. Stores frequently accessed data</blockquote>
</details>

<details>
<summary><b>Q: CPU fetch-decode-execute-store cycle?</b></summary>
<blockquote><b>Answer:</b> 1. Fetch instruction 2. Decode 3. Execute 4. Store result</blockquote>
</details>

<details>
<summary><b>Q: RISC architecture?</b></summary>
<blockquote><b>Answer:</b> Reduced Instruction Set Computer. Simple, fast instructions. One cycle per instruction</blockquote>
</details>

<details>
<summary><b>Q: CISC architecture?</b></summary>
<blockquote><b>Answer:</b> Complex Instruction Set Computer. Complex, multi-cycle instructions</blockquote>
</details>

<details>
<summary><b>Q: Embedded system definition?</b></summary>
<blockquote><b>Answer:</b> Specialized computer system for specific task. Integrated into larger system</blockquote>
</details>

<details>
<summary><b>Q: RTOS (Real-Time OS)?</b></summary>
<blockquote><b>Answer:</b> OS with predictable response time. Used in critical embedded systems</blockquote>
</details>

<details>
<summary><b>Q: ALU (Arithmetic Logic Unit)?</b></summary>
<blockquote><b>Answer:</b> Performs arithmetic (+, -, *, /) and logical (AND, OR) operations</blockquote>
</details>

<details>
<summary><b>Q: Control Unit?</b></summary>
<blockquote><b>Answer:</b> Directs CPU operations. Fetches, decodes, controls instruction execution</blockquote>
</details>

<details>
<summary><b>Q: Addressing modes?</b></summary>
<blockquote><b>Answer:</b> Immediate, Register, Direct, Indirect, Register Indirect, Indexed</blockquote>
</details>

<details>
<summary><b>Q: Cache mapping: Direct mapping?</b></summary>
<blockquote><b>Answer:</b> Block address mod cache blocks (simple but high conflict)</blockquote>
</details>

<details>
<summary><b>Q: Cache mapping: Associative mapping?</b></summary>
<blockquote><b>Answer:</b> Block can go anywhere in cache (no conflict but complex)</blockquote>
</details>

<details>
<summary><b>Q: Cache mapping: Set-associative?</b></summary>
<blockquote><b>Answer:</b> Block maps to specific set, anywhere within set (balanced approach)</blockquote>
</details>

<details>
<summary><b>Q: Write-through cache?</b></summary>
<blockquote><b>Answer:</b> Write to cache AND memory immediately. Safe but slow</blockquote>
</details>

<details>
<summary><b>Q: Write-back cache?</b></summary>
<blockquote><b>Answer:</b> Write to cache, update memory later. Fast but complex</blockquote>
</details>

<details>
<summary><b>Q: Virtual memory?</b></summary>
<blockquote><b>Answer:</b> Uses secondary storage as extension of main memory. Allows larger programs</blockquote>
</details>

<details>
<summary><b>Q: Paging concept?</b></summary>
<blockquote><b>Answer:</b> Divides memory into equal-sized pages. Maps virtual to physical addresses</blockquote>
</details>

<details>
<summary><b>Q: Page table?</b></summary>
<blockquote><b>Answer:</b> Maps virtual page number to physical frame number</blockquote>
</details>

<details>
<summary><b>Q: TLB (Translation Lookaside Buffer)?</b></summary>
<blockquote><b>Answer:</b> Cache for page table entries. Speeds up address translation</blockquote>
</details>

<details>
<summary><b>Q: Page replacement: LRU?</b></summary>
<blockquote><b>Answer:</b> Replace Least Recently Used page (tracks usage)</blockquote>
</details>

<details>
<summary><b>Q: Page replacement: FIFO?</b></summary>
<blockquote><b>Answer:</b> Replace oldest page (First In First Out)</blockquote>
</details>

<details>
<summary><b>Q: Page replacement: Optimal?</b></summary>
<blockquote><b>Answer:</b> Replace page used furthest in future (theoretical, not practical)</blockquote>
</details>

<details>
<summary><b>Q: Instruction-level parallelism?</b></summary>
<blockquote><b>Answer:</b> Multiple instructions execute simultaneously. Via pipelining, superscalar</blockquote>
</details>

<details>
<summary><b>Q: Superscalar architecture?</b></summary>
<blockquote><b>Answer:</b> Multiple execution units. Several instructions per clock cycle</blockquote>
</details>

<details>
<summary><b>Q: Von Neumann architecture?</b></summary>
<blockquote><b>Answer:</b> Single memory for instructions and data. Most common</blockquote>
</details>

<details>
<summary><b>Q: Harvard architecture?</b></summary>
<blockquote><b>Answer:</b> Separate instruction and data memory. Faster but more complex</blockquote>
</details>

<details>
<summary><b>Q: Registers purpose?</b></summary>
<blockquote><b>Answer:</b> Fastest storage in CPU. Hold operands, intermediate results</blockquote>
</details>

<details>
<summary><b>Q: Program Counter (PC)?</b></summary>
<blockquote><b>Answer:</b> Holds address of next instruction to execute</blockquote>
</details>

<details>
<summary><b>Q: Stack pointer (SP)?</b></summary>
<blockquote><b>Answer:</b> Points to top of stack. Auto-incremented/decremented</blockquote>
</details>

<details>
<summary><b>Q: Bus in computer architecture?</b></summary>
<blockquote><b>Answer:</b> Shared communication path. Types: Data bus, Address bus, Control bus</blockquote>
</details>

<details>
<summary><b>Q: Data bus width?</b></summary>
<blockquote><b>Answer:</b> Determines how many bits transferred per cycle. 8-bit, 16-bit, 32-bit, 64-bit</blockquote>
</details>

<details>
<summary><b>Q: Address bus width?</b></summary>
<blockquote><b>Answer:</b> Determines addressable memory. n-bit bus = 2^n addressable locations</blockquote>
</details>

<details>
<summary><b>Q: Interrupt request (INTR)?</b></summary>
<blockquote><b>Answer:</b> Signal requesting CPU attention. Maskable (can be ignored)</blockquote>
</details>

<details>
<summary><b>Q: Non-maskable interrupt (NMI)?</b></summary>
<blockquote><b>Answer:</b> Cannot be ignored. Highest priority</blockquote>
</details>

<details>
<summary><b>Q: Memory bandwidth?</b></summary>
<blockquote><b>Answer:</b> Amount of data transferred per unit time (bytes/second)</blockquote>
</details>

<details>
<summary><b>Q: Memory latency?</b></summary>
<blockquote><b>Answer:</b> Time to access memory location (nanoseconds)</blockquote>
</details>

<details>
<summary><b>Q: Multiprocessor system?</b></summary>
<blockquote><b>Answer:</b> Multiple CPUs in one system. Shared or distributed memory</blockquote>
</details>

<details>
<summary><b>Q: Parallel processing benefits?</b></summary>
<blockquote><b>Answer:</b> Increased throughput, faster execution, improved reliability</blockquote>
</details>

<details>
<summary><b>Q: Amdahl's Law?</b></summary>
<blockquote><b>Answer:</b> S = 1/((1-p) + p/n). Speedup limited by sequential portion</blockquote>
</details>

<details>
<summary><b>Q: 5-stage pipeline throughput?</b></summary>
<blockquote><b>Answer:</b> After initial fill: 1 instruction per clock (if no stalls)</blockquote>
</details>

<details>
<summary><b>Q: Data hazard?</b></summary>
<blockquote><b>Answer:</b> Instruction depends on previous instruction's result. Solution: forwarding, stalls</blockquote>
</details>

<details>
<summary><b>Q: Control hazard?</b></summary>
<blockquote><b>Answer:</b> Branch changes execution flow. Fetched wrong instruction. Solution: prediction, delay slot</blockquote>
</details>

---

**Total: 50 Questions** | Focus: Cache, memory hierarchy, paging, pipeline, multiprocessor
