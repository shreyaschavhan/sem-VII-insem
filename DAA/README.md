## 𝐃𝐞𝐬𝐢𝐠𝐧 𝐚𝐧𝐝 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬 𝐨𝐟 𝐀𝐥𝐠𝐨𝐫𝐢𝐭𝐡𝐦𝐬

> - Unit I  : Algorithms and Problem Solving
> - Unit II : Analysis of Algorithms and complexity theory

---

## 𝐔𝐧𝐢𝐭 𝐈  : 𝐀𝐥𝐠𝐨𝐫𝐢𝐭𝐡𝐦𝐬 𝐚𝐧𝐝 𝐏𝐫𝐨𝐛𝐥𝐞𝐦 𝐒𝐨𝐥𝐯𝐢𝐧𝐠

<div align=center>
  <br>

  ![image](https://user-images.githubusercontent.com/68887544/193409166-6f5abe6d-2534-4224-baa6-e22689e00bcf.png)

  <br>
</div>

- What is an algorithm?
> - In order for us to complete a specific task, we need to define a finite set of unambiguous steps that needs to be followed in certain order.
> - These finite set of unambiguous steps are called as algorithm.

- Characteristics of an algorithm:
> - Input : A good algorithm should have zero or more inputs
> - Output : A good algorithm will always produce one or more outputs.
> - Finiteness : A good algorithm will always terminate after finite number of steps for each test case
> - Definiteness : A good algorithm will be definite, precise and easy to interpret.
> - Effectiveness : A good algorithm will be effective, simple and feasible.

`^ Expand on the above topics depending upon the number of marks assigned to the question`

- Algorithm as technology:
> - We should consider algorithms as technology, same as we do consider hardware.
> - Why?
> - Because - Algorithms make solving problems more efficient. Same problem can be solved by different algorithms.
> - Suppose, we have two computers - Computer A and Computer B.
> - Computer A is 100 times faster than Computer B.
> - Now, we wanna sort an array with 10^6 numbers.
> - Computer A uses bubble sort, whereas computer B uses heap sort
> - Time complexity of bubble sort is n^2 where as time complexity of heap sort is (nlogn).
> - Suppose - Processing speed of computer A is 10^9 instructions per second whereas computer B is 10^7 instructions per second
> - Let's compute time to sort that array:

```
Computer A :

      n^2                (10^6)^2       
-----------------   = ---------------  = 1000 seconds
 Processing Speed          10^9/sec

Computer B :

    n log n                    10^6 log 10^6
------------------  =  ------------------------  = 100 seconds
 Processing Speed               10^7/sec

```

> - It's obvious that algorithm used in computer B is 10 times faster than algorithm used in computer A even if computer A is faster than computer B.
> - This is one of the major reason why we should consider algorithm as a technology.


- Evolution of Algorithms
> - I think it's not that important.

- Design of Algorithms
> - The design approach of an algorithm mainly depends on the model chosen.
> - There might exist more than one algorithm to solve a given problem and which one to choose out of them depends on which one is more effective and efficient.
> - We can write algorithms using pseudo code.
> - Basic Steps to design an algorithm:
>   - Identify the problem to be solved.
>   - Understand and analyze it.
>   - Select appropriate algorithmic strategy.
>   - Identify the input.
>   - Identify the expected output.
>   - Decide suitable data structures to store the input and present/store the output.
>   - Describe a finite set of well-ordered unambiguous instructions to produce the expected output.

- Need of correctness of algorithms
> - We wouldn't be able to say the algorithm is reliable unless and until it gives expected output for each and every possible given input.
> - If the algorithm passes only few test inputs and fail for the others, most of our answer will be incorrect and we wouldn't be able to rely on that algorithm for long term.
> - So, we need algorithms to be correct so that we can make sure we get 100% correct output for all possible given inputs and to verify if the algorithm actually solves the problem for which it is designed.

- Confirming correctness of Algorithm - Sample Examples
> - It's almost impossible to test an algorithm with each and every possible input since it's very difficult to trace down that much amount of inputs.
> - So, to be able to confirm the correctness of algorithm - we need to use mathematical proofs and equations.
> - Basic steps to confirm the correctness of algorithms:
>   - Define the post conditions that needs to be satisfied.
>   - Assume all pre-conditions that can possibly help us in reaching the expected post conditions.
>   - Apply a chain of logical and mathematical reasoning from preconditions to satisfy the post conditions.

- Testing of a loop invariant property:
> - What is loop invariant condition?
>   - A condition which is true immediately before, during and immediately after each iteration of the loop is called as loop invariant condition.
> - A loop invariant property is a property of an iterative algorithm.
> - It is used to define the goal or desired output of an iterative algorithm.
> - We test loop invariant property to make sure the iterative algorithm is working properly.
> - To prove the correctness of an iterative algorithm, we need to demonstrate that a postcondition is met or satisfied upon the termination of the given loop.
> - To do that, we need to test the following:
>   - The loop invariant should hold true at first iteration.
>   - The loop invariant should stay true during the iteration.
>   - The loop should terminate after a finite number of iteration.
>   - The loop invariant should stay true at the termination.
>   - Whenever the termination condition and loop invariant of loop both holds, then the postocndition must also hold.
> - For example,
```
int iterative_fact(int n){
  int fact = 1;
  for(int i = 1; i <= n ; i++){
    fact = fact * i;
  }
  return fact;
}
```
> - Here:
>   - Post Condition: fact = n! = product of n numbers
>   - Suppose n = 4, therefore postcondition = fact = 4! = 24
>   - Loop invariant is: fact = fact * i;
>   - First iteration: i = 1, fact = 1 = 1! ==> which is true.
>   - During all iteration:
>     - i = 2, fact = 1 * 2 = 2! ==> which is true.
>     - i = 3, fact = 2 * 3 = 6 = 3! ==> which is true.
>     - i = 4, fact = 6 * 4 = 24 = 4! ==> which is true.
>   - Loop terminates at n = 4
>   - Here, first condition and loop termination condition both holds, hence the post condition also holds.
>   - It implies that the algorithm is correctly computing n! in the finite number of steps and hence the algorithm for factorial is correct.

- Proof by principle of mathematical induction (PMI)
> - PMI is generally used to prove the correctness of recursive algorithms.
> - According to PMI, we can check the correctness of an algorithm using following steps:
>   - Verify if the statement is true for the base case like n = a .i.e F(a) is true
>   - Assume that the statement is true for n = k where k >= a i.e. F(k) is true (Inductive Hypothesis)
>   - If the truth of P(k) implies the truth of P(k+1), then the statement P(n) is true for all n >= a.
> - For example
```
int recursive_fact(int n){
  if (n == 0 || n == 1){
    return 1
  }
  else{
    return n * recursive_fact(n-1);
  }

}
```
> - Here,
>   - We know, recursive_fact(n) = n * (n - 1) * .... 1 = n!
>   - base case is n = 0 or n = 1, for it the function returns 1 which is true.
>   - suppose, recursive_fact(k) = k * (k - 1) * .... 1 = k! is true for n = k
>   - We now have to prove that recursive_fact(k+1) is also true
```
recursive_fact(k+1) = (k+1) * recursive_fact(k)
Here,
RHS = (k + 1) * k * (k - 1) .... 1 = (k+1)!
LHS = (k + 1) * k * (k - 1) .... 1 = (k+1)!
LHS = RHS
Hence proved!
```   
>   - Hence, recursive_fact(k+1) is true, whenever recursive_fact(k) is true.
>   - And we know for base case, n = 0 or n = 1 is true.
>   - Hence recursive_fact(n) is true and returns n * recursive_fact(n-1) for all n.

- Iterative Algorithm Design Issues:
> - Wastage of computing resources if iterative algorithm is designed to contain redundant computations of constant part in a loop.
>   - Example:
```
sum = 0
for i in range(n):
  sum = sum + i * (a * b + b * b + a * a)
```
>   - Here the expression (a * b + b * b + a * a) has a redundant constant which is calculated during each iteration.
> - Referencing an array element from a loop. To reach any array element, the program performs address arithmetic and it consumes time.
> - Defining more than required conditions to terminate the loop which causes late termination of loop.

- Problem Solving Principles:
> - Classification of problem:
>   - Searching problems          : Searching of any element or key in a given data.
>   - Sorting problems            : Rearrangement of given data in asc or dsc order.
>   - String processing problems  : Computation on string eg. concatenation, encoding, etc.
>   - Graph problems              : Problems including graphs, eg. graph-traversal, etc.
>   - Combinatorial problems      : Finding or computing combinatorial objects eg. permutation, combination, etc.
>   - Geometric problems          : Problems dealing with points, lines, ploygons, etc.
>   - Numerical problems          : Problems including mathematical computational problems.
>   - Optimization problem        : computational problem that determines the optimal value of a specific cost function.
>   - Decision problem            : Problem that produces "yes" or "no" kind of output for each input.
>   - Decidable problem           : Decision problem which get correct "yes" or "no"
>   - Undecidable problem         : Decision problem which does not get correct "yes" or "no"
>   - Tractable problem           : Problems solved in polynomial time.
>   - Intractable problem         : Problems that cannot be solved in polynomial time.
>
> ---
>
> - Problem solving strategies:
>   - Brute force method   : Enumerates all possible solutions to a given problem without applying any heuristics.
>   - Exhaustive Search    : Generates all candidate solutions to a given combinatorial problem and identifies the feasible solution.
>   - Divide and conquer   : Follows - divide, conquer and combine
>     - Divide: dividing large problem into smaller ones
>     - Conquer: Solving the sub-problems independently and recursively by invoking the same algorithm.
>     - Combine: Combine the solutions to all sub-problems and derive a final solution.
>   - Greedy method        : Build solution in stages and selecting the best choice at each stage concerning the local consideration.
>   - Dynamic programming  : Solves optimization problems with overlapping sub-problems.
>   - Backtracking        : Explores all the solutions to a given problem and abandons them if they are not fulfilling the specified constraints.
>   - Branch and bound    : Performs a systematic enumeration of candidate solutions by means of state space search.
>
> ---
>
> - Classification of time complexities:
>   - Constant time    - O(1)
>   - Linear time      - O(n)
>   - Logarithmic time - O(log n)
>   - Quadratic time   - O(n^2)
>   - Cubic time       - O(n^3)
>   - Exponential time
>   - Quasilinear time
>   - Factorial time
>   - Poly-logarithmic time
>   - Sub-linear time
>   - Polynomial time
>   - etc.



## 𝐔𝐧𝐢𝐭 𝐈𝐈: 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬 𝐨𝐟 𝐀𝐥𝐠𝐨𝐫𝐢𝐭𝐡𝐦𝐬 𝐚𝐧𝐝 𝐂𝐨𝐦𝐩𝐥𝐞𝐱𝐢𝐭𝐲 𝐓𝐡𝐞𝐨𝐫𝐲

<div align=center>
  <br>

![image](https://user-images.githubusercontent.com/68887544/193447355-dd10fe24-f3a8-4033-beff-91fd7358ab2b.png)

  <br>
</div>
