#IMPORTANT
    Undertstanding
        visual representtation
        conceptual/mental understanding
        verbal expression
    Analyze
        time complexity
    Implementation
        data-structure required
        pseudo-code
        with programming constructs

#data structures && algorithms
## Insights
    different DS implementations
    combining things
## TURING MACHINE
<!----------------------------------------------------DATA STRUCTURES BEGIN------------------------------------------------------------------------------------------------>
DATA STRUCTURES
================
## Data type
    primitive based
    reference based9(linked)
## linear (sequential,single run,prev/next)
        array (index based, memory efficient, static)
            static (fixed size)
            dynamic/array list (varible size)
        list
            linked list(not index based/pointer/reference)
                single
                double
            stack(LIFO)
            queue(FIFO)
                min/max heap/ordered
                    sink/swim
                    comparable interface?
                waiting line
                enqueue/dequeue
                offer/poll
                breadth
                heap
                    tree based
## non-linear
        tree (hierarchy, parent/child)
        graph (nodes/vertices,edges)
# tree 
        no cycles
        undirected graph
        less edges then nodes
        skewed tree - each node one child
## other
       hash table
       matrix (table)
       user defined data structures

ABSTRACT DATA TYPE
-----------------
* interface
* combine data structure and operations
* variable is input size?
* interface is set of operations of ADT
* all primitives are ADT
* different implementation of ADT
* encapsulation
### Operations from data structure point:
    * search
    * sort/rearrange
    * insert 
    * update
    * delete
    * merging
    * traversing
# DATA STRUCTURES CLASSIFICATION
    primitive (integer...)/composite (array...)
    linear/non-linear
    homogeneous(elements of same type) / non-homogeneous(not same type)
    static/dynamic
# Graphs
    vertex/node
        single point
        set of vertices
    edge
        line/connection
# ADT common operations
    access/find (one/multiple items)
    insert (at start/end/position)
    delete (from start/end/position)
    update (in mutable structure)
<!----------------------------------------------------DATA STRUCTURES END------------------------------------------------------------------------------------------------>

ALGORITHM DEFINITION:
====================
Program = data structures + algorithms
Basic algorithms concept:
-------------------------
* algorithms as math concept
* algorithms as order of instructions (step by step)
* data structures (linear && non-linear)
* implementation with programming constructs 
* problem and resource dependent
* step by step procedure
* language independent
###Algorithm characteristics:
    * unambiguous
    * have input
    * have output
    * finiteness
    * fasibility
    * language independent
    * correctness

Program constructs CAN BE USED to write algorithms (if,for,sequences,expressions ...)
Problem has many solutions
Time complexity - time and  input relation
###Algorithm analysis(efficienty)
    * priori (theorethical)
    * posteriory (empirical)
###Algorithm comlexity
    * time
        lower time
        we CAN'T Buy time
        RAM
    * space (memory)
        increase space
        we CAN buy memory
        temporary variables
        meta information about the program
        how input impact extra memoty needed?
        ignoring input/output and extra variables
        control variables independent on amount of data
        processor
# Constant may be ingnored (dominant term also)
###Time
    *   run in constant time (independent, of input size)
    *   linear time (execution proportional to input size,instance is increased by constant)
    *   logarithmic (inverse of exponent) time 
            each step is divided by constant
            reduce problem by half usually
            constant is not important (smaller constant, more steps)
            on each iteration elements are thrown (divided by constant)
            breaking problems info smaller units (divide and conquer)
    *   linearithmic (cross between linear and logarithmic n * logN)
    *   quadratic time (execution proportional to squeare of input size,nested loops)
    *   cubic (two nested loops)
    *   exponential

###Asymptotic analysis (running time)
    * best case (minimum time)
    * average cas ( average time)
    * worst case (maximum time)
###Asymptotic notation
    * big omega Ω notation (best case)
    * big theta θ notation (both cases)
    * big O notation (worst case)
# Asymptotic bounding

#CLASSIFICATION
##by purpose
    -sorting
    -searching
##BY IMPLEMENTATION
    -recursive/iterative
    -logical/procedural
    -serial/parallel
    -deterministic/non-deterministic
##BY DESIGN PARADIGM
    -divide and conquer (binary search, quick sort, merge sort, closest pair)
    -dynamic programming
    -greedy method
    -linear programming
    -reduction
    -using graphs
    -probabilistic/heuristic
    -backtracking
    -brute force (no shortcat)
#BY STRATEGY (ONE POSSIBLE CLASSIFICATION)
    *iteretive
    *divide and conquer
    *greedy (immediately)
    *back-tracking
##BY COMPLEXITY


STEP COUNT OPERATIONS
---------------------
-arithmetical operations
-logical operations
-return statement
-variable assignment

CONSTANT VS VARIABLE
--------------------
*   constant are operations?


Examples for practice:
----------------------
*   fibonacci
*   euclid (GCD)
*   odd/even
*   factorial (recursion)

Recursion
---------
*   smaller subproblem
*   base case (condition for exit)
*   call stack

Types of recursion
------------------
*   linear (winding/unwinding)
*   binary recursion (double call at each run)
*   tail recursion (no pending operation after return)
*   mutual recursion
*   nested recursion (call itself as parameter)

Side notes
----------
    *A MATHEMATICAL FUNCTION IS THE INTERFACE, OR SPECIFICATION OF THE INPUTS AND OUTPUTS OF AN ALGORITHM.
    *Constants can be removed
    *Lower order terms can be removed
    *Multiplication constants can be removed

## Common
    Euclid
        Greatest common denominator
        GCD
    Fibonacci
    Recursive
        Power(2*2*2)
        Factorial(5! 5*4*3*2*1)
    Sorting
        Bubble sort
        Merge sort (divide and conquer)
        Quick sort (divide and conquer)
    Searching
        Unordered
        Ordered (binary search)
# Control structures
    sequence (statement)
    branching/decision/selection 
        if/else/elseIf
    loop/iteration
        for
        forEach
        while
        do while
        switch/break/continue
# Tools
    input
    control 
    data structure
    algorithm
# Sublinear
    not required to look all elements
    approximation
    preprocessing
    O(1)
    O(log n)
    O(n log n) nearly linear
# Superlienar
# Ammortized time
# Time && space relation
# Class of behavior e.g. constants are not important


# Common classes of behavior
# Tail end behavior
# Upper bound 
    worst case
    includes upper (slower) classes e.g. n2,n log n, for n?
    Tight upper bound (same class)
    Loose upper bound (different class)
# Constants are internal to class
    for bounding
# Tight bound
    same class of behavior

# Input is crucial
# What can input do to change internal logic?
    O(1) nothing
# O(1)
    BASED ON WHAT COMPUTER DOES, NOT INPUT
# O(log n)
    levels are important
# O (m + n)
    multilinear (max)
# Function domain
    all input values
# Function range
    all output values
# Graph
    sparse
    dense
# Cardinality
    |x|
# Recursion
    recursive case/more calls/expansion
    base case

# Math for algorithms
    number theory
    algebra (with matrices)
    combinatorics/probability
    sets
    logic/proof
    graph theory
# Problem terms

# Important
    data structure
        array (indexed)
            static(fixed size)
        list
            dynamic array(list)
            linked
            double
        stack
        queue
        heap
        tree
        hash table
        graph
        matrix (table)
    operation/problem to solve
        search
            linear search
            binary search
        sort/rearrange
            bubble sort
            merge sort
                divide and conquer
                usually recursively
            heap sort
            quick sort
            selection sort
            radix sort
        insert 
        update
        delete
        merging
        traversing
    class of behavior
        O(1)
        O(log(n))
        O(n)
        O(n * log(n))
        O(n2)
    control structures
# Important
    swap
    self modifying
    ram memory of computation
        imperative nature
        step by step
        global state
        branching to path
        where to start?
        multiple paths
# File
    on disk
# Data structure
    in memory
