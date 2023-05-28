# Stack-CPU-Simulator :computer:

A **Stack CPU** is a fascinating piece of hardware that operates on a unique principle. It primarily comprises of three essential components:

- **Memory (MEM)** - This is where the instructions for operations are stored.

- **Data Stack (DS)** - A stack-based data structure used for storing intermediate results.

- **Return Stack (RS)** - Another stack-based structure utilized for storing return addresses.

The stack CPU operates based on the instructions stored in the **Memory**, starting from the instruction pointed to by the **Program Counter (PC)**. A single instruction is made up of two parts:

- **The opcode** - This indicates the type of instruction. The subsequent memory location will serve as the operand, which may or may not be present.

- **The operand** - Depending on the instruction, the operation may require zero to two operands.

Once an instruction execution is complete, the **PC** advances to point to the next instruction, and the process continues by executing that instruction. This cycle repeats continuously, making the CPU work.

> You can access the code for both the 8-bit and 16-bit versions on their respective branches

---

## :movie_camera: Preview

Check out these simulations in action:

<details>
<summary><b>16 bit</b> - <a href="https://stack-cpu-16-bit.netlify.app/">stack-cpu-16-bit.netlify.app</a></summary>

![image](https://github.com/ExitedState/Stack-CPU-Simulator/assets/67526393/5773ab11-4f88-4704-8dc6-63e778be4183)

</details>

<details>
<summary><b>8 bit</b> - <a href="https://stack-cpu-8-bit.netlify.app/">stack-cpu-8-bit.netlify.app</a></summary>

![image](https://github.com/ExitedState/Stack-CPU-Simulator/assets/67526393/9639f747-fd86-483f-b26f-74988023d029)

</details>

---


#### :book: Reference

The original version can be found in Course 2301274 [Computer Systems](https://cache111.com/me/2301274.html)

- **16 bit** - [cache111.com/me/2301274/Simulator_16.html](https://cache111.com/me/2301274/Simulator_16.html)

- **8 bit** - [cache111.com/me/2301274/Simulator_8.html](https://cache111.com/me/2301274/Simulator_8.html)
