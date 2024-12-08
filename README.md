# Fundamentals of Software Development

## Data Types
- Primitive Types
  - [Integer](https://en.wikipedia.org/wiki/Integer): Whole numbers, e.g., 1, 42.
  - [Float](https://en.wikipedia.org/wiki/Floating-point_arithmetic): Decimal numbers, e.g., 3.14.
  - [Boolean](https://developer.mozilla.org/en-US/docs/Glossary/Boolean): True/False values.
  - [Character](https://en.wikipedia.org/wiki/Character_(computing)): A single letter, e.g., 'a'.
  - [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String): A sequence of characters, e.g., "Hello".
- Composite Types
  - [Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array): A fixed-size collection of elements of the same type.
  - [Object/Struct](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object): A collection of fields with key-value pairs.
  - [Tuple](https://en.wikipedia.org/wiki/Tuple): An immutable, ordered collection of elements.
- Abstract Data Types (ADTs)
  - [List](https://en.wikipedia.org/wiki/List_(abstract_data_type)): An ordered collection allowing duplicates.
  - [Stack](https://en.wikipedia.org/wiki/Stack_(abstract_data_type)): A last-in, first-out (LIFO) collection.
  - [Queue](https://en.wikipedia.org/wiki/Queue_(abstract_data_type)): A first-in, first-out (FIFO) collection.
  - [Set](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set): A collection of unique elements.
  - [Map/Dictionary](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map): Key-value pairs for fast lookups.

## Data Structures
- Linear
  - [Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array): A collection of elements indexed by position.
  - [Linked List](https://en.wikipedia.org/wiki/Linked_list): A chain of nodes where each points to the next.
  - [Stack](https://en.wikipedia.org/wiki/Stack_(abstract_data_type)): Supports operations like push, pop, and peek.
  - [Queue](https://en.wikipedia.org/wiki/Queue_(abstract_data_type)): Useful for tasks processed in order, e.g., print jobs.
- Non-Linear
  - [Tree](https://en.wikipedia.org/wiki/Tree_(data_structure)): A hierarchy of nodes with a root and children.
    - [Binary Tree](https://en.wikipedia.org/wiki/Binary_tree): Each node has up to two children.
    - [Binary Search Tree](https://en.wikipedia.org/wiki/Binary_search_tree): A binary tree with ordered nodes.
    - [AVL Tree](https://en.wikipedia.org/wiki/AVL_tree): A self-balancing binary search tree.
    - [B-Trees](https://en.wikipedia.org/wiki/B-tree): Optimized for disk storage systems.
  - [Graph](https://en.wikipedia.org/wiki/Graph_(abstract_data_type)): Nodes (vertices) connected by edges.
    - [Directed/Undirected Graphs](https://en.wikipedia.org/wiki/Graph_(discrete_mathematics)#Types_of_graphs): Edges have or lack direction.
    - [Weighted/Unweighted Graphs](https://en.wikipedia.org/wiki/Graph_(discrete_mathematics)#Weighted_graphs): Edges may have a weight value.
- Hashing
  - [Hash Tables](https://en.wikipedia.org/wiki/Hash_table): Store data using hash functions for quick lookups.
  - [Hash Maps](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map): Similar to hash tables but often in memory.

## Algorithms
- Algorithms Types
  - Sorting
    - [Bubble Sort](https://en.wikipedia.org/wiki/Bubble_sort): Repeatedly swaps adjacent out-of-order elements.
    - [Quick Sort](https://en.wikipedia.org/wiki/Quicksort): Divides and conquers around a pivot element.
    - [Merge Sort](https://en.wikipedia.org/wiki/Merge_sort): Divides, sorts, and merges arrays.
    - [Insertion Sort](https://en.wikipedia.org/wiki/Insertion_sort): Builds a sorted list by inserting one element at a time.
  - Searching
    - [Linear Search](https://en.wikipedia.org/wiki/Linear_search): Sequentially checks each element.
    - [Binary Search](https://en.wikipedia.org/wiki/Binary_search_algorithm): Efficient search for sorted data.
  - Graph Algorithms
    - [Depth-First Search (DFS)](https://en.wikipedia.org/wiki/Depth-first_search): Explores as deep as possible before backtracking.
    - [Breadth-First Search (BFS)](https://en.wikipedia.org/wiki/Breadth-first_search): Explores neighbors level by level.
    - [Dijkstra’s Algorithm](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm): Finds shortest paths in weighted graphs.
  - [Dynamic Programming](https://en.wikipedia.org/wiki/Dynamic_programming)
    - [Fibonacci Sequence](https://en.wikipedia.org/wiki/Fibonacci_number): Solves problems using overlapping subproblems.
    - [Knapsack Problem](https://en.wikipedia.org/wiki/Knapsack_problem): Optimizes resource allocation.
  - [Greedy Algorithms](https://en.wikipedia.org/wiki/Greedy_algorithm): Makes local optimum choices for global solutions.
  - [Divide and Conquer](https://en.wikipedia.org/wiki/Divide-and-conquer_algorithm): Splits problems into smaller ones, solves, and combines results.
- Algorithmic Complexity
  - [Time Complexity](https://en.wikipedia.org/wiki/Time_complexity)
      - [O(1) - Constant Time](https://rob-bell.net/2009/06/a-beginners-guide-to-big-o-notation/): Execution time doesn't depend on input size.
      - [O(log n) - Logarithmic Time](https://rob-bell.net/2009/06/a-beginners-guide-to-big-o-notation/): Time grows logarithmically with input size.
      - [O(n) - Linear Time](https://rob-bell.net/2009/06/a-beginners-guide-to-big-o-notation/): Time grows proportionally to input size.
      - [O(n log n) - Linearithmic Time](https://rob-bell.net/2009/06/a-beginners-guide-to-big-o-notation/): Common in efficient sorting algorithms like Merge Sort.
      - [O(n²) - Quadratic Time](https://rob-bell.net/2009/06/a-beginners-guide-to-big-o-notation/): Often results from nested loops over input size.
      - [O(2ⁿ) - Exponential Time](https://rob-bell.net/2009/06/a-beginners-guide-to-big-o-notation/): Growth doubles with each addition to input size, e.g., solving the Traveling Salesman Problem.
      - [O(n!) - Factorial Time](https://rob-bell.net/2009/06/a-beginners-guide-to-big-o-notation/): Infeasible for large inputs, e.g., brute force permutations.
  - [Space Complexity](https://en.wikipedia.org/wiki/Space_complexity)
      - [Auxiliary Space](https://www.geeksforgeeks.org/g-fact-86/): Temporary or extra space used by the algorithm.
      - [Input Space](https://en.wikipedia.org/wiki/Space_complexity): Memory required to store input data.
  - Notations:
    - [Big-O Notation](https://en.wikipedia.org/wiki/Big_O_notation): Describes the upper bound of an algorithm's complexity.
    - [Big-Theta Notation](https://en.wikipedia.org/wiki/Big_%CE%98_notation): Describes the average or "tight bound" of complexity.
    - [Big-Omega Notation](https://en.wikipedia.org/wiki/Big_Omega_notation): Describes the best-case complexity.

## Software Development Principles
- [SOLID Principles](https://en.wikipedia.org/wiki/SOLID): Best practices for maintainable and scalable OOP.
  - [Single Responsibility Principle](https://en.wikipedia.org/wiki/Single-responsibility_principle): A class should have one purpose.
  - [Open/Closed Principle](https://en.wikipedia.org/wiki/Open–closed_principle): Software should be open for extension but closed for modification.
  - [Liskov Substitution Principle](https://en.wikipedia.org/wiki/Liskov_substitution_principle): Subtypes should replace their base types without issues.
  - [Interface Segregation Principle](https://en.wikipedia.org/wiki/Interface_segregation_principle): Avoid forcing classes to implement unused interfaces.
  - [Dependency Inversion Principle](https://en.wikipedia.org/wiki/Dependency_inversion_principle): Depend on abstractions, not concrete implementations.
- [DRY (Don't Repeat Yourself)](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself): Reduce code duplication by centralizing functionality.
- [KISS (Keep It Simple, Stupid)](https://en.wikipedia.org/wiki/KISS_principle): Aim for simplicity to avoid complexity.
- [YAGNI (You Aren’t Gonna Need It)](https://martinfowler.com/bliki/Yagni.html): Don’t build features until they are necessary.
- [OOP Concepts](https://en.wikipedia.org/wiki/Object-oriented_programming): Encapsulation, Abstraction, Inheritance, Polymorphism.

## Design Patterns
- [Creational Patterns](https://en.wikipedia.org/wiki/Creational_pattern)
  - [Singleton](https://refactoring.guru/design-patterns/singleton): Ensures a class has only one instance.
  - [Factory](https://refactoring.guru/design-patterns/factory-method): Creates objects without specifying exact classes.
  - [Builder](https://refactoring.guru/design-patterns/builder): Separates object construction from its representation.
  - [Prototype](https://refactoring.guru/design-patterns/prototype): Copies objects to create new ones.
- [Structural Patterns](https://en.wikipedia.org/wiki/Structural_pattern)
  - [Adapter](https://refactoring.guru/design-patterns/adapter): Bridges incompatible interfaces.
  - [Composite](https://refactoring.guru/design-patterns/composite): Treats individual objects and compositions uniformly.
  - [Decorator](https://refactoring.guru/design-patterns/decorator): Dynamically adds behavior to objects.
  - [Proxy](https://refactoring.guru/design-patterns/proxy): Controls access to objects.
- [Behavioral Patterns](https://en.wikipedia.org/wiki/Behavioral_pattern)
  - [Observer](https://refactoring.guru/design-patterns/observer): A subscription mechanism to notify multiple objects.
  - [Strategy](https://refactoring.guru/design-patterns/strategy): Defines a family of algorithms for runtime selection.
  - [Command](https://refactoring.guru/design-patterns/command): Encapsulates commands as objects.
  - [State](https://refactoring.guru/design-patterns/state): Alters behavior based on the object's state.

## Refactoring
- [Code Smells](https://refactoring.guru/refactoring/smells): Indicators of problematic code needing improvement.
  - [Duplicated Code](https://refactoring.guru/smells/duplicated-code): Identical code blocks scattered throughout.
  - [Long Method](https://refactoring.guru/smells/long-method): Functions that do too much and are hard to read.
  - [Large Class](https://refactoring.guru/smells/large-class): Classes with too many responsibilities.
- [Refactoring Techniques](https://refactoring.guru/refactoring)
  - [Extract Method](https://refactoring.guru/extract-method): Move repeated code into a new method.
  - [Inline Method](https://refactoring.guru/inline-method): Replace a simple method with its contents.
  - [Rename Variable](https://refactoring.guru/rename-variable): Make names self-explanatory.
  - [Simplify Conditional Expressions](https://refactoring.guru/replace-nested-conditional-with-guard-clauses): Reduce nested or complex conditions.
- [Tools](https://refactoring.guru/tools)
  - [IDE Support](https://www.jetbrains.com/help/idea/refactoring-code.html): Automates refactoring tasks.
  - [Linters](https://eslint.org/): Identify code smells and enforce style guidelines.

---
