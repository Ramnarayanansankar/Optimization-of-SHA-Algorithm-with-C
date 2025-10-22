## README: Program Optimization Details

This file contains details about the program, its optimization approach, execution steps, and the resulting difference in running time.

-----

### Program File Details

  * **`shaO.c`**: This is the **Original File** provided by the professor.
  * **`shaM.c`**: This is the **Modified File** containing the **Optimized C program Code**.

-----

### How to Run the Programs

#### Running the Optimized Program (`shaM.c`)

There are two steps to run the `shaM.c` file:

**Step 1: Compilation**

Give the command:

```bash
gcc shaM.c -o programM
```

  * `shaM.c` is the C program file.
  * `programM` is the Compiled File.

**Step 2: Execution**

Give the command:

```bash
./programM
```

  * `programM` is the file that will show the output.

#### Running the Original Program (`shaO.c`)

There are two steps to run the `shaO.c` file:

**Step 1: Compilation**

Give the command:

```bash
gcc shaO.c -o programO
```

  * `shaO.c` is the C program file.
  * `programO` is the Compiled File.

**Step 2: Execution**

Give the command:

```bash
./programO
```

  * `programO` is the file that will show the output.

-----

### Optimization Approach

The optimization focused on changing only the **FOR Loops** within the program.

  * Loops have an $\text{O}(n)$ Time Complexity , where '$n$' represents the number of times the loop is going to run.
  * Function blocks *without* looping statements have an $\text{O}(1)$ complexity , where '1' represents the constant time taken for running the function block.

#### What was done to optimize the program?

1.  We **removed For Loops** from the functions in the program.
2.  We then **manually ran the looping statements** for the required number of times for the function block.
3.  Ultimately, this process **reduced the Running time** of the program.