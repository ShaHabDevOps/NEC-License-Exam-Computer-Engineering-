# Topic 2: Digital Logic & Microprocessor

> **80 Questions** | Direct Answers | Cheat Sheet Format

---

<details>
<summary><b>Q: Convert binary 1101 to decimal.</b></summary>
<blockquote><b>Answer:</b> (1×8) + (1×4) + (0×2) + (1×1) = 13</blockquote>
</details>

<details>
<summary><b>Q: Convert decimal 25 to binary.</b></summary>
<blockquote><b>Answer:</b> 11001</blockquote>
</details>

<details>
<summary><b>Q: Basic logic gates list?</b></summary>
<blockquote><b>Answer:</b> AND, OR, NOT, NAND, NOR, XOR, XNOR</blockquote>
</details>

<details>
<summary><b>Q: AND gate truth table (2-input)?</b></summary>
<blockquote><b>Answer:</b> 0&0=0, 0&1=0, 1&0=0, 1&1=1 (Output 1 only if BOTH inputs 1)</blockquote>
</details>

<details>
<summary><b>Q: OR gate truth table (2-input)?</b></summary>
<blockquote><b>Answer:</b> 0|0=0, 0|1=1, 1|0=1, 1|1=1 (Output 1 if AT LEAST ONE input 1)</blockquote>
</details>

<details>
<summary><b>Q: XOR gate truth table (2-input)?</b></summary>
<blockquote><b>Answer:</b> 0⊕0=0, 0⊕1=1, 1⊕0=1, 1⊕1=0 (Output 1 if inputs DIFFERENT)</blockquote>
</details>

<details>
<summary><b>Q: De Morgan's Law 1?</b></summary>
<blockquote><b>Answer:</b> (A·B)' = A' + B'</blockquote>
</details>

<details>
<summary><b>Q: De Morgan's Law 2?</b></summary>
<blockquote><b>Answer:</b> (A+B)' = A'·B'</blockquote>
</details>

<details>
<summary><b>Q: What is multiplexer?</b></summary>
<blockquote><b>Answer:</b> Selects 1 of 2^n inputs. Inputs: 2^n data, n select lines. Output: 1 line</blockquote>
</details>

<details>
<summary><b>Q: What is demultiplexer?</b></summary>
<blockquote><b>Answer:</b> Routes 1 input to 1 of 2^n outputs. Input: 1 data, n select lines. Outputs: 2^n</blockquote>
</details>

<details>
<summary><b>Q: What is decoder?</b></summary>
<blockquote><b>Answer:</b> Converts n-bit binary to 1 of 2^n outputs. One output active at a time</blockquote>
</details>

<details>
<summary><b>Q: What is encoder?</b></summary>
<blockquote><b>Answer:</b> Converts 1 of 2^n inputs to n-bit binary code</blockquote>
</details>

<details>
<summary><b>Q: What is flip-flop?</b></summary>
<blockquote><b>Answer:</b> Bistable circuit. 2 stable states. Stores 1 bit. Outputs: Q, Q' (complementary)</blockquote>
</details>

<details>
<summary><b>Q: SR flip-flop truth table?</b></summary>
<blockquote><b>Answer:</b> S=0,R=0→Hold. S=1,R=0→SET(Q=1). S=0,R=1→RESET(Q=0). S=1,R=1→Invalid</blockquote>
</details>

<details>
<summary><b>Q: JK flip-flop truth table?</b></summary>
<blockquote><b>Answer:</b> J=0,K=0→Hold. J=0,K=1→RESET. J=1,K=0→SET. J=1,K=1→TOGGLE</blockquote>
</details>

<details>
<summary><b>Q: D flip-flop behavior?</b></summary>
<blockquote><b>Answer:</b> Q(next) = D (stores input at clock edge)</blockquote>
</details>

<details>
<summary><b>Q: T flip-flop behavior?</b></summary>
<blockquote><b>Answer:</b> T=0→No change. T=1→Toggle (Q becomes Q')</blockquote>
</details>

<details>
<summary><b>Q: Difference: Latch vs Flip-flop?</b></summary>
<blockquote><b>Answer:</b> Latch: Level-triggered, transparent. Flip-flop: Edge-triggered, synchronous</blockquote>
</details>

<details>
<summary><b>Q: Half-adder logic?</b></summary>
<blockquote><b>Answer:</b> Sum = A ⊕ B. Carry = A · B</blockquote>
</details>

<details>
<summary><b>Q: Full-adder logic?</b></summary>
<blockquote><b>Answer:</b> Sum = A ⊕ B ⊕ C_in. Carry_out = AB + (A⊕B)C_in</blockquote>
</details>

<details>
<summary><b>Q: Address lines for 1KB memory?</b></summary>
<blockquote><b>Answer:</b> log₂(1024) = 10 address lines</blockquote>
</details>

<details>
<summary><b>Q: Address lines formula?</b></summary>
<blockquote><b>Answer:</b> n = log₂(Memory size in bytes)</blockquote>
</details>

<details>
<summary><b>Q: Ring counter states for 4-bit?</b></summary>
<blockquote><b>Answer:</b> 0001, 0010, 0100, 1000, 0001... (4 states, MOD-4)</blockquote>
</details>

<details>
<summary><b>Q: Johnson counter states for 4-bit?</b></summary>
<blockquote><b>Answer:</b> 8 states (2n). Feedback from Q' instead of Q</blockquote>
</details>

<details>
<summary><b>Q: Synchronous counter definition?</b></summary>
<blockquote><b>Answer:</b> All FFs clocked simultaneously. No ripple delay. Faster than asynchronous</blockquote>
</details>

<details>
<summary><b>Q: Asynchronous counter definition?</b></summary>
<blockquote><b>Answer:</b> Each FF clocked by previous FF output. Ripple delay. Slower</blockquote>
</details>

<details>
<summary><b>Q: MOD-n counter flip-flops needed?</b></summary>
<blockquote><b>Answer:</b> n = 2^k where k = number of FFs. Example: MOD-8 needs 3 FFs</blockquote>
</details>

<details>
<summary><b>Q: Shift register types?</b></summary>
<blockquote><b>Answer:</b> SISO, SIPO, PISO, PIPO</blockquote>
</details>

<details>
<summary><b>Q: Karnaugh Map (K-map) purpose?</b></summary>
<blockquote><b>Answer:</b> Graphical method to simplify Boolean expressions. Minimize logic gates</blockquote>
</details>

<details>
<summary><b>Q: K-map valid grouping sizes?</b></summary>
<blockquote><b>Answer:</b> 1, 2, 4, 8, 16... (powers of 2)</blockquote>
</details>

<details>
<summary><b>Q: Sum-of-Products (SOP) method?</b></summary>
<blockquote><b>Answer:</b> Write product term for each 1 in truth table. OR all terms together</blockquote>
</details>

<details>
<summary><b>Q: Product-of-Sums (POS) method?</b></summary>
<blockquote><b>Answer:</b> Write sum term for each 0 in truth table. AND all terms together</blockquote>
</details>

<details>
<summary><b>Q: 4:1 Multiplexer logic equation?</b></summary>
<blockquote><b>Answer:</b> Y = I₀S₁'S₀' + I₁S₁'S₀ + I₂S₁S₀' + I₃S₁S₀</blockquote>
</details>

<details>
<summary><b>Q: 2:4 Decoder truth table?</b></summary>
<blockquote><b>Answer:</b> AB=00→Y₀=1. AB=01→Y₁=1. AB=10→Y₂=1. AB=11→Y₃=1</blockquote>
</details>

<details>
<summary><b>Q: 1-bit comparator logic?</b></summary>
<blockquote><b>Answer:</b> A>B = A·B'. A=B = A⊙B (XNOR). A<B = A'·B</blockquote>
</details>

<details>
<summary><b>Q: Parity bit purpose?</b></summary>
<blockquote><b>Answer:</b> Error detection. Even parity: total 1s = even. Odd parity: total 1s = odd</blockquote>
</details>

<details>
<summary><b>Q: Setup time definition?</b></summary>
<blockquote><b>Answer:</b> Minimum time input must be stable BEFORE clock edge</blockquote>
</details>

<details>
<summary><b>Q: Hold time definition?</b></summary>
<blockquote><b>Answer:</b> Minimum time input must remain stable AFTER clock edge</blockquote>
</details>

<details>
<summary><b>Q: Metastability in flip-flop?</b></summary>
<blockquote><b>Answer:</b> Output undefined when setup/hold violated. Settles unpredictably to 0 or 1</blockquote>
</details>

<details>
<summary><b>Q: 8085 word size?</b></summary>
<blockquote><b>Answer:</b> 8-bit</blockquote>
</details>

<details>
<summary><b>Q: 8085 total interrupts?</b></summary>
<blockquote><b>Answer:</b> 13 (5 hardware + 8 software)</blockquote>
</details>

<details>
<summary><b>Q: TRAP vs INTR interrupt?</b></summary>
<blockquote><b>Answer:</b> TRAP: Non-maskable, highest priority. INTR: Maskable, lowest priority</blockquote>
</details>

<details>
<summary><b>Q: 8085 interrupt priority order?</b></summary>
<blockquote><b>Answer:</b> TRAP > RST 7.5 > RST 6.5 > RST 5.5 > INTR</blockquote>
</details>

<details>
<summary><b>Q: 8085 16-bit register pairs?</b></summary>
<blockquote><b>Answer:</b> BC, DE, HL, SP (Stack Pointer), PC (Program Counter)</blockquote>
</details>

<details>
<summary><b>Q: 8085 clock frequency?</b></summary>
<blockquote><b>Answer:</b> 3 MHz (originally), up to 5 MHz</blockquote>
</details>

<details>
<summary><b>Q: Fetch-decode-execute cycle steps?</b></summary>
<blockquote><b>Answer:</b> 1. Fetch (retrieve instruction) 2. Decode (interpret) 3. Execute (perform) 4. Store (result)</blockquote>
</details>

<details>
<summary><b>Q: What is Direct Memory Access (DMA)?</b></summary>
<blockquote><b>Answer:</b> Device transfers data directly to/from memory without CPU intervention</blockquote>
</details>

<details>
<summary><b>Q: 8085 vs 8086?</b></summary>
<blockquote><b>Answer:</b> 8085: 8-bit, 1MHz. 8086: 16-bit, 5-10MHz, more powerful instruction set</blockquote>
</details>

<details>
<summary><b>Q: Pipelining concept?</b></summary>
<blockquote><b>Answer:</b> Multiple instructions processed in parallel stages simultaneously</blockquote>
</details>

<details>
<summary><b>Q: Without pipeline: 5 instructions with 5 stages = ? cycles</b></summary>
<blockquote><b>Answer:</b> 5 × 5 = 25 cycles</blockquote>
</details>

<details>
<summary><b>Q: With pipeline: 5 instructions with 5 stages = ? cycles (after fill)</b></summary>
<blockquote><b>Answer:</b> 5 + (5-1) = 9 cycles</blockquote>
</details>

<details>
<summary><b>Q: Microprocessor ALU purpose?</b></summary>
<blockquote><b>Answer:</b> Performs arithmetic (+, -, *, /) and logical (AND, OR, NOT) operations</blockquote>
</details>

<details>
<summary><b>Q: Control Unit function?</b></summary>
<blockquote><b>Answer:</b> Directs CPU operations. Fetches, decodes, controls instruction execution</blockquote>
</details>

<details>
<summary><b>Q: Addressing modes in 8085?</b></summary>
<blockquote><b>Answer:</b> Immediate, Register, Direct, Indirect, Register Indirect</blockquote>
</details>

<details>
<summary><b>Q: Stack purpose?</b></summary>
<blockquote><b>Answer:</b> LIFO memory. Stores return addresses, temporary data during function calls</blockquote>
</details>

<details>
<summary><b>Q: Interrupt handling steps?</b></summary>
<blockquote><b>Answer:</b> 1. Save state 2. Jump to ISR (Interrupt Service Routine) 3. Execute ISR 4. Return to original location</blockquote>
</details>

<details>
<summary><b>Q: Gray code for 3-bit?</b></summary>
<blockquote><b>Answer:</b> 000, 001, 011, 010, 110, 111, 101, 100 (consecutive values differ by 1 bit)</blockquote>
</details>

<details>
<summary><b>Q: Binary to Gray conversion?</b></summary>
<blockquote><b>Answer:</b> G₀=B₀. G₁=B₁⊕B₀. G₂=B₂⊕B₁. Gₙ=Bₙ⊕Bₙ₋₁</blockquote>
</details>

<details>
<summary><b>Q: Gray code application?</b></summary>
<blockquote><b>Answer:</b> Rotary encoders, minimizes errors in transitions, reduces glitches</blockquote>
</details>

<details>
<summary><b>Q: SRAM vs DRAM?</b></summary>
<blockquote><b>Answer:</b> SRAM: 6T, no refresh, fast (~1ns), expensive. DRAM: 1T+C, refresh needed, slow (~50ns), cheap</blockquote>
</details>

<details>
<summary><b>Q: PROM vs EPROM vs EEPROM?</b></summary>
<blockquote><b>Answer:</b> PROM: Write once. EPROM: UV erase. EEPROM: Electrical erase (byte-wise, in-circuit)</blockquote>
</details>

<details>
<summary><b>Q: Cache mapping techniques?</b></summary>
<blockquote><b>Answer:</b> Direct, Associative, Set-associative</blockquote>
</details>

<details>
<summary><b>Q: Write-through cache?</b></summary>
<blockquote><b>Answer:</b> Write to cache AND memory simultaneously</blockquote>
</details>

<details>
<summary><b>Q: Write-back cache?</b></summary>
<blockquote><b>Answer:</b> Write to cache, update memory later</blockquote>
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
<summary><b>Q: LRU page replacement?</b></summary>
<blockquote><b>Answer:</b> Replace Least Recently Used page when page fault occurs</blockquote>
</details>

<details>
<summary><b>Q: FIFO page replacement?</b></summary>
<blockquote><b>Answer:</b> Replace oldest (First In) page</blockquote>
</details>

---

**Total: 80 Questions** | Study Focus: Flip-flops, decoders, K-map, 8085 interrupts, memory types, addressing modes
