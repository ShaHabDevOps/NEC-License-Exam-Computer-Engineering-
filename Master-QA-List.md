# NEC Computer Engineering License Exam Study Notes
## 200 Comprehensive Questions & Answers (Basic to Advanced)

---

## Table of Contents
1. [Basic Electrical and Electronics Engineering](#topic-1-basic-electrical-and-electronics-engineering)
2. [Digital Logic](#topic-2-digital-logic)
3. [Microprocessor (8085/8086)](#topic-3-microprocessor-80858086)
4. [Programming Language (C)](#topic-4-programming-language-c)
5. [Object-Oriented Programming (C++)](#topic-5-object-oriented-programming-c)
6. [Computer Organization and Embedded Systems](#topic-6-computer-organization-and-embedded-systems)
7. [Computer Network and Network Security](#topic-7-computer-network-and-network-security)
8. [Theory of Computation and Computer Graphics](#topic-8-theory-of-computation-and-computer-graphics)
9. [Data Structures, Algorithms, Database and OS](#topic-9-data-structures-algorithms-database-and-os)

---

## Topic 1: Basic Electrical and Electronics Engineering

### Basic Level
1. **Q: State Ohm's Law.** **A:** $V = IR$ (Voltage = Current × Resistance).
3. **Q: What is the difference between a conductor and an insulator?** **A:** Conductor allows free flow of electrons (low resistance). Insulator restricts electron flow (high resistance).
5. **Q: Define electrical power and its SI unit.** **A:** Power is the rate of energy consumption. SI unit: Watt (W) = Joules/second (J/s).
6. **Q: In a series circuit, how do voltages add up?** **A:** Total voltage = $V_1 + V_2 + V_3 + ...$ (voltages add directly).
7. **Q: In a parallel circuit, how do currents add up?** **A:** Total current = $I_1 + I_2 + I_3 + ...$ (currents add directly).
8. **Q: What is the relationship between terminal voltage ($V_t$) and EMF ($\epsilon$)?** **A:** $V_t = \epsilon - Ir$ (Terminal voltage = EMF - voltage drop across internal resistance).
9. **Q: Define a bilateral circuit.** **A:** A circuit whose properties are independent of the direction of current flow through it.
10. **Q: What is a non-linear circuit?** **A:** A circuit where the relationship between voltage and current is non-linear (e.g., diode circuits).

### Medium Level
9. **Q: State Kirchhoff's Voltage Law (KVL).** **A:** The algebraic sum of voltages around any closed loop in a circuit is zero: $\sum V = 0$.
10. **Q: State Kirchhoff's Current Law (KCL).** **A:** The algebraic sum of currents at any node is zero. Current entering = Current leaving.
11. **Q: Convert a delta ($\Delta$) connection with resistance $R$ to an equivalent star ($Y$) connection.** **A:** $R_Y = R_\Delta / 3$ (Each star resistance = Delta resistance / 3).
12. **Q: State the Superposition Theorem.** **A:** In a linear circuit with multiple sources, the response is the sum of responses due to each source acting alone.
13. **Q: What is Thevenin's Theorem?** **A:** Any linear two-terminal circuit can be replaced by an equivalent circuit consisting of a voltage source ($V_{th}$) and series resistance ($R_{th}$).
14. **Q: Explain the Maximum Power Transfer Theorem.** **A:** Maximum power is transferred to a load when the load resistance equals the Thevenin equivalent resistance ($R_L = R_{th}$).
15. **Q: Define resonance in an RLC circuit.** **A:** Resonance occurs when the inductive and capacitive reactances are equal ($X_L = X_C$), and impedance is minimum (purely resistive).
16. **Q: What is the power factor?** **A:** Power Factor (PF) = $\cos(\phi)$ = Real Power / Apparent Power. It indicates the phase angle between voltage and current.

### Advanced Level
17. **Q: Derive the resonant frequency formula for a series RLC circuit.** **A:** $f_0 = \frac{1}{2\pi\sqrt{LC}}$ where $L$ is inductance and $C$ is capacitance.
18. **Q: Explain active and reactive power in AC circuits.** **A:** Active Power ($P$) = $VI \cos(\phi)$ (actual power consumed). Reactive Power ($Q$) = $VI \sin(\phi)$ (power oscillating between source and load).
19. **Q: In a three-phase AC system, what is the phase difference between phases?** **A:** 120° (or $2\pi/3$ radians). Line voltage = $\sqrt{3} \times$ phase voltage.
20. **Q: Explain the working principle of a CMOS device.** **A:** CMOS combines NMOS and PMOS transistors. NMOS pulls output low, PMOS pulls high. Always one transistor is off, leading to extremely low power consumption.

---

## Topic 2: Digital Logic

### Basic Level
1. **Q: Convert the binary number 1011 to decimal.** **A:** $(1 \times 2^3) + (0 \times 2^2) + (1 \times 2^1) + (1 \times 2^0) = 8 + 0 + 2 + 1 = 11$.
2. **Q: What are the basic logic gates?** **A:** AND, OR, NOT, NAND, NOR, XOR, XNOR.
3. **Q: Draw the truth table for a 2-input AND gate.** **A:** | A | B | Y |
   |---|---|---|
   | 0 | 0 | 0 |
   | 0 | 1 | 0 |
   | 1 | 0 | 0 |
   | 1 | 1 | 1 |
4. **Q: What is Boolean Algebra?** **A:** Mathematical system for analyzing and simplifying logic circuits using variables (0,1) and operations (AND, OR, NOT).
5. **Q: State De Morgan's Laws.** **A:** $(A \cdot B)' = A' + B'$ and $(A + B)' = A' \cdot B'$.
6. **Q: What is a Karnaugh Map (K-map)?** **A:** A graphical method for simplifying Boolean expressions and logic circuits.
7. **Q: What is a multiplexer?** **A:** A digital device that selects one of many input signals and outputs it based on control select lines.
8. **Q: What is a decoder?** **A:** A device that converts binary input into one of $2^n$ output lines (only one output is active at a time).
9. **Q: Define a flip-flop.** **A:** A bistable multivibrator that has two stable states and is used to store one bit of information.
10. **Q: What is an SR (Set-Reset) flip-flop?** **A:** A basic flip-flop with Set and Reset inputs. SET forces $Q=1$, RESET forces $Q=0$.

### Medium Level
11. **Q: What is the difference between a latch and a flip-flop?** **A:** Latch is level-triggered. Flip-flop is edge-triggered (responds to clock edge).
12. **Q: Explain JK flip-flop.** **A:** J=Set, K=Reset. When J=K=0: No Change; J=K=1: Toggle; J=1, K=0: Set; J=0, K=1: Reset.
13. **Q: What is a ring counter?** **A:** A shift register circuit where the output of the last flip-flop is fed back to the input of the first.
14. **Q: How many bits can a 4-bit binary number represent?** **A:** $2^4 = 16$ different values (0000 to 1111).
15. **Q: What is a half-adder?** **A:** A combinational circuit that adds two single-bit binary numbers and produces Sum and Carry outputs.
16. **Q: What is a full-adder?** **A:** A combinational circuit that adds three bits (two significant bits + carry-in) and produces Sum and Carry-out.
17. **Q: What is a multiplexer vs. demultiplexer?** **A:** Multiplexer: many inputs → one output. Demultiplexer: one input → many outputs.
18. **Q: How many address lines are needed to address 1024 memory locations?** **A:** $2^n = 1024 \rightarrow n = 10$ address lines.
19. **Q: What is the difference between combinational and sequential circuits?** **A:** Combinational: output depends only on current input. Sequential: output depends on current input and past states.

### Advanced Level
20. **Q: Minimize the Boolean expression: $F = A'B'C + A'BC + AB'C + ABC$** **A:** Using K-map: $F = C$ (A and B are redundant).
21. **Q: Explain asynchronous and synchronous counters.** **A:** Asynchronous: each flip-flop clocked by previous flip-flop output. Synchronous: all flip-flops clocked simultaneously.
22. **Q: What is state diagram in sequential circuits?** **A:** A diagram showing all possible states and transitions based on inputs.
23. **Q: How many flip-flops are required to design a mod-8 counter?** **A:** 3 flip-flops (since $2^3 = 8$ states).
24. **Q: What is edge-triggering in flip-flops?** **A:** The flip-flop responds to input changes only at the rising or falling edge of the clock.
25. **Q: Explain setup time and hold time in flip-flops.** **A:** **Setup time**: minimum time input must be stable *before* clock edge. **Hold time**: minimum time input must remain stable *after* clock edge.

---

## Topic 3: Microprocessor (8085/8086)

### Basic Level
1. **Q: What are the main components of a microprocessor?** **A:** ALU, Control Unit, Registers, Memory/IO Interface.
2. **Q: What is the word size of 8085 microprocessor?** **A:** 8-bit.
3. **Q: How many interrupts does the 8085 have?** **A:** 5 hardware (TRAP, RST 7.5, 6.5, 5.5, INTR) and 8 software (RST 0-7).
4. **Q: What is the difference between TRAP and INTR in 8085?** **A:** TRAP: Non-maskable, highest priority. INTR: Maskable, lowest priority.
5. **Q: List the 16-bit register pairs in 8085.** **A:** BC, DE, HL, SP (Stack Pointer), PC (Program Counter).
6. **Q: What is the clock frequency of 8085?** **A:** 3 MHz typically.
7. **Q: What is an assembly language instruction?** **A:** A low-level mnemonic (e.g., MOV A, B) that the CPU can execute.
8. **Q: What is a register?** **A:** Small, fast storage within the CPU for temporary data.

### Medium Level
9. **Q: Explain the addressing modes in 8085.** **A:** Immediate (MVI), Register (MOV), Direct (LDA), Indirect (LDAX).
10. **Q: What is the stack and what is its purpose?** **A:** A LIFO memory structure used to store return addresses during function calls (CALL).
11. **Q: Explain the fetch-decode-execute cycle.** **A:** Fetching opcode from memory, decoding what it does, and performing the operation.
12. **Q: What is interrupt handling?** **A:** Process where CPU pauses execution, saves state, and executes an Interrupt Service Routine (ISR).
13. **Q: What is Direct Memory Access (DMA)?** **A:** Technique allowing peripherals to transfer data directly to memory without CPU intervention.
14. **Q: Explain the difference between 8085 and 8086.** **A:** 8085: 8-bit. 8086: 16-bit, features a 6-byte instruction queue (pipelining).
15. **Q: What is pipelining in microprocessors?** **A:** Overlapping the fetch and execution phases of instructions to increase throughput.

### Advanced Level
16. **Q: In 8085, which interrupt has the highest priority?** **A:** TRAP.
17. **Q: Explain the Memory Interface in 8085.** **A:** Uses 16-bit Address Bus to select location and 8-bit Data Bus for transfer.
18. **Q: What is the purpose of the Stack Pointer (SP)?** **A:** Holds the memory address of the top of the stack.
19. **Q: Explain Interrupt Priority in 8085.** **A:** TRAP > RST 7.5 > RST 6.5 > RST 5.5 > INTR.
20. **Q: What is the fetch cycle and execution cycle?** **A:** Fetch cycle retrieves the instruction (M-cycles), execution cycle performs the task (T-states).

---

## Topic 4: Programming Language (C)

### Basic Level
1. **Q: What is a data type in C?** **A:** Defines the type and size of data (int, float, char).
2. **Q: List basic data types in C.** **A:** int, float, double, char, void.
3. **Q: What is a pointer in C?** **A:** A variable that stores the memory address of another variable.
4. **Q: How do you declare a pointer?** **A:** `int *ptr;`
5. **Q: What is the difference between pass by value and pass by reference?** **A:** Value: copy passed. Reference: address passed (affects original).
6. **Q: What is a structure in C?** **A:** User-defined type grouping different data types under one name.
7. **Q: What is a union in C?** **A:** Like structure, but all members share the same memory location.
8. **Q: Define an array.** **A:** Collection of same-type elements in contiguous memory.
9. **Q: What is a string in C?** **A:** Character array terminated by `\0`.
10. **Q: What is the purpose of the main() function?** **A:** The entry point where execution begins.

### Medium Level
11. **Q: Explain pointer arithmetic.** **A:** Pointers increment by the size of their data type (e.g., `ptr++` on int moves 4 bytes).
12. **Q: What is a 2D array and how is it declared?** **A:** Matrix of rows/cols: `int arr[3][4];`.
13. **Q: What is a function prototype?** **A:** Declaration specifying name, return type, and parameters before usage.
14. **Q: Explain recursion with an example.** **A:** Function calling itself: `fact(n) = n * fact(n-1)`.
15. **Q: What is the difference between local and global variables?** **A:** Local: scoped to function. Global: scoped to entire program.
16. **Q: What is dynamic memory allocation?** **A:** Using `malloc()`, `calloc()` to allocate memory at runtime.
17. **Q: What is file I/O in C?** **A:** `fopen`, `fclose`, `fread`, `fwrite` for file operations.
18. **Q: Explain sequential and random file access.** **A:** Sequential reads one by one; Random uses `fseek()` to jump to a position.
19. **Q: What is the difference between gets() and fgets()?** **A:** `gets()` is unsafe (buffer overflow); `fgets()` specifies size.

### Advanced Level
20. **Q: Explain pointer to pointer (double pointer).** **A:** `int **ptr;` stores the address of another pointer.
21. **Q: What is a structure pointer?** **A:** Accessed via `ptr->member`.
22. **Q: Explain function pointers.** **A:** Stores the address of a function: `int (*fp)(int);`.
23. **Q: What is the difference between array and pointer?** **A:** Array name is a constant pointer to the first element.
24. **Q: Explain the difference between #define and const.** **A:** `#define`: Preprocessor (no type checking). `const`: Compiler (type-safe).
25. **Q: What are command-line arguments?** **A:** Passed to `main(int argc, char *argv[])`.

---

## Topic 5: Object-Oriented Programming (C++)

### Basic Level
1. **Q: What is a class in C++?** **A:** Blueprint for objects encapsulating data and functions.
2. **Q: What is an object?** **A:** Instance of a class.
3. **Q: What are access specifiers in C++?** **A:** `public`, `private`, `protected`.
4. **Q: What is encapsulation?** **A:** Bundling data and hiding implementation details.
5. **Q: What is a constructor?** **A:** Auto-called function to initialize objects.
6. **Q: What is a destructor?** **A:** Auto-called function for cleanup.
7. **Q: What is operator overloading?** **A:** Giving special meaning to operators for classes.
8. **Q: What is inheritance?** **A:** Deriving properties from a base class.

### Medium Level
9. **Q: Explain single inheritance.** **A:** One child from one parent.
10. **Q: Explain multiple inheritance.** **A:** One child from multiple parents.
11. **Q: What is a virtual function?** **A:** Enables runtime polymorphism via overriding.
12. **Q: Explain polymorphism.** **A:** One interface, multiple forms (Overloading vs. Overriding).
13. **Q: What is the 'this' pointer?** **A:** Pointer to the current object.
14. **Q: What is a static member?** **A:** Shared across all instances of the class.
15. **Q: Explain the difference between pass by reference and pass by pointer.** **A:** Reference is an alias; Pointer is a memory address.

### Advanced Level
16. **Q: What is pure virtual function and abstract class?** **A:** `virtual void func() = 0;`. Abstract class cannot be instantiated.
17. **Q: Explain friend function.** **A:** Non-member function that can access private data.
18. **Q: What is function template?** **A:** Generic function for different types: `template <typename T>`.
19. **Q: Explain const member function.** **A:** Cannot modify object members.
20. **Q: What is the difference between overloading and overriding?** **A:** **Overloading**: Same scope, different params. **Overriding**: Base vs Derived, same signature.

---

## Topic 6: Computer Organization and Embedded Systems

### Basic Level
1. **Q: What is the memory hierarchy?** **A:** Registers > Cache > RAM > HDD/SSD.
2. **Q: What is cache memory?** **A:** Fast buffer between CPU and RAM.
3. **Q: Explain the CPU cycle.** **A:** Fetch → Decode → Execute → Store.
4. **Q: What is pipelining?** **A:** Parallelizing instruction stages.
5. **Q: What is RISC?** **A:** Reduced Instruction Set Computer.
6. **Q: What is CISC?** **A:** Complex Instruction Set Computer.
7. **Q: What is an embedded system?** **A:** System designed for a specific function within a larger device.
8. **Q: What is RTOS?** **A:** Operating system for real-time constraints.

### Medium Level
9. **Q: What is ALU?** **A:** Performs math and logic.
10. **Q: What is instruction format?** **A:** [Opcode] [Operand].
11. **Q: Explain addressing modes.** **A:** Immediate, Direct, Indirect, Indexed.
12. **Q: What is control unit?** **A:** Orchestrates CPU operations.
13. **Q: Explain cache mapping.** **A:** Direct, Associative, Set-Associative.
14. **Q: Write-through vs Write-back.** **A:** Write-through updates RAM immediately; Write-back updates RAM later.
15. **Q: What is virtual memory?** **A:** Using disk space as extended RAM.

### Advanced Level
16. **Q: What is TLB?** **A:** Cache for page table lookups.
17. **Q: Explain page replacement.** **A:** LRU (Least Recently Used), FIFO, Optimal.
18. **Q: What is ILP?** **A:** Instruction-Level Parallelism.
19. **Q: Explain superscalar architecture.** **A:** Issuing multiple instructions per clock cycle.
20. **Q: Von Neumann vs Harvard.** **A:** Von Neumann: Combined code/data bus. Harvard: Separate buses.

---

## Topic 7: Computer Network and Network Security

### Basic Level
1. **Q: What is a computer network?** **A:** Interconnected devices sharing resources.
2. **Q: What is the OSI model?** **A:** 7 layers: Physical, Data Link, Network, Transport, Session, Presentation, Application.
3. **Q: Explain TCP/IP model.** **A:** 4 layers: Link, Internet, Transport, Application.
4. **Q: What is IP address?** **A:** Unique identifier (IPv4: 32-bit; IPv6: 128-bit).
5. **Q: What is a subnet?** **A:** Segmented part of a larger network.
6. **Q: What is a router?** **A:** Connects networks (Layer 3).
7. **Q: What is a switch?** **A:** Connects devices in a LAN (Layer 2).
8. **Q: What is a gateway?** **A:** Entrance/exit point between networks.
9. **Q: TCP vs UDP.** **A:** TCP: Reliable/Slow. UDP: Fast/Unreliable.
10. **Q: What is DNS?** **A:** Translates domain names to IP addresses.

### Medium Level
11. **Q: Explain 3-way handshake.** **A:** SYN → SYN-ACK → ACK.
12. **Q: What is ARP?** **A:** Maps IP to MAC.
13. **Q: What is ICMP?** **A:** Error reporting protocol (used by Ping).
14. **Q: Explain routing.** **A:** Choosing the best path via algorithms like Dijkstra.
15. **Q: What is BGP?** **A:** Protocol for routing between autonomous systems on the internet.
16. **Q: What is DHCP?** **A:** Auto-assigns IP addresses.
17. **Q: What is a firewall?** **A:** Traffic filter for security.
18. **Q: Encryption vs Decryption.** **A:** Plaintext to Ciphertext and vice versa.
19. **Q: What is VPN?** **A:** Secure tunnel over public network.

### Advanced Level
20. **Q: Symmetric vs Asymmetric encryption.** **A:** Symmetric: 1 key. Asymmetric: Public/Private key pair.
21. **Q: What is RSA?** **A:** Popular asymmetric algorithm based on prime factorization.
22. **Q: What is a digital signature?** **A:** Provides authentication/integrity.
23. **Q: Explain IPSec.** **A:** Protocol for securing IP traffic.
24. **Q: SSL/TLS.** **A:** Encryption for web (HTTPS).
25. **Q: Congestion control.** **A:** Managing data flow to prevent network collapse.

---

## Topic 8: Theory of Computation and Computer Graphics

### Theory of Computation
1. **Q: What is finite automaton?** **A:** State machine recognizing regular languages.
2. **Q: DFA vs NFA.** **A:** DFA: One move per input. NFA: Multiple moves possible.
3. **Q: Regular language.** **A:** Language accepted by a finite automaton.
4. **Q: Context-free grammar (CFG).** **A:** Grammar used for programming languages (Pushdown Automata).
5. **Q: Turing machine.** **A:** Universal model of computation.
6. **Q: Church-Turing thesis.** **A:** Anything computable is computable by a Turing machine.
7. **Q: Pumping lemma.** **A:** Proves a language is NOT regular.
8. **Q: P, NP, NP-Complete.** **A:** P: Easy to solve. NP: Easy to check. NP-Complete: Hardest NP problems.

### Computer Graphics
1. **Q: Basic transformations.** **A:** Translation, Rotation, Scaling.
2. **Q: Translation formula.** **A:** $x' = x + t_x, y' = y + t_y$.
3. **Q: Rotation formula.** **A:** $x' = x\cos\theta - y\sin\theta$.
4. **Q: 3D transformations.** **A:** Extension of 2D including Z-axis.
5. **Q: Projection types.** **A:** Orthographic vs Perspective.
6. **Q: Clipping.** **A:** Removing parts of an image outside a window (Cohen-Sutherland).
7. **Q: Perspective.** **A:** Objects further away appear smaller.

---

## Topic 9: Data Structures, Algorithms, Database and OS

### Data Structures & Algorithms
1. **Q: Stack vs Queue.** **A:** Stack: LIFO. Queue: FIFO.
2. **Q: Linked List.** **A:** Nodes connected by pointers.
3. **Q: Big O.** **A:** Worst-case time complexity.
4. **Q: BST.** **A:** Binary Search Tree: Left < Root < Right.
5. **Q: Sorting.** **A:** Quick/Merge: $O(n \log n)$. Bubble/Insertion: $O(n^2)$.
6. **Q: Hash Table.** **A:** Key-value mapping for $O(1)$ lookup.
7. **Q: Graph Representation.** **A:** Adjacency Matrix or List.
8. **Q: DFS vs BFS.** **A:** DFS uses Stack; BFS uses Queue.
9. **Q: Dijkstra.** **A:** Shortest path algorithm.
10. **Q: Dynamic Programming.** **A:** Solving subproblems and storing results (memoization).

### Database Systems
1. **Q: DBMS.** **A:** Software for database management.
2. **Q: ER Model.** **A:** Entities and their relationships.
3. **Q: Normalization.** **A:** Reducing data redundancy (1NF, 2NF, 3NF).
4. **Q: SQL.** **A:** Standard language for relational databases.
5. **Q: ACID.** **A:** Atomicity, Consistency, Isolation, Durability.
6. **Q: Concurrency control.** **A:** Managing simultaneous transactions (Locks).

### Operating Systems
1. **Q: Process.** **A:** Program in execution.
2. **Q: CPU Scheduling.** **A:** FCFS, SJF, Round Robin.
3. **Q: Paging.** **A:** Non-contiguous memory allocation.
4. **Q: Deadlock.** **A:** Mutual wait for resources.
5. **Q: Page Replacement.** **A:** LRU, FIFO, Optimal.
