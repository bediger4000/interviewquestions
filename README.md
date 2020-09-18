# Programming Interview Questions and Puzzles

Like a lot of people, I subscribe to [Daily Coding Problem](https://www.dailycodingproblem.com/).
I also read reddit and other sites and sometimes do the interview problem or puzzle just
to see if I can.

This repo collects links to other repos of mine that contain solutions to interview questions and puzzles.

* [Binary tree](https://github.com/bediger4000/binary_tree) problems.
This repo contains a number of problems,
and a tree package (it's in Go) to make
solving the problems less repetitious.
  * Invert a binary tree
  * Breadth-first traverse
  * Return the maximum depth and/or the deepest node
  * Reconstruct original tree from pre-order and in-order traversals
  * Find all paths from root to leaves
  * Print tree nodes' values in boustrophedon order
  * Print "cousin" nodes of a given node
  * Prune a tree so all subtrees that have a 0-valued node are removed
  * Minimum-height binary search tree from a sorted array
  * Find lowest-common ancestor of a given node. Assume pointer to parent node
  * Count nodes in a "complete" binary tree in less than linear time
  * Determine whether a binary tree is height-balanced
  * Return the "inorder successor" (next biggest node) of a given node in a binary tree
  * Find the "bottom view" of a binary tree
  * Given a binary tree, find a minimum path sum from root to a leaf
  * Find nodes of a tree with values inside a given range
  * Implement locking in a binary tree. Weird locking, but locking.
  * Count "unival subtrees" in a binary tree
* [k-ary tree symmetry](https://github.com/bediger4000/tree_symmetry) determine whether a tree with arbitrary number of children is symmetric.
* [Linked list](https://github.com/bediger4000/linked_lists) problems.
This repo contains several interview questions,
and a Go linked list package to make solving problems less repetitious.
  * Build a stack from a linked list
  * Implement a queue using two stacks. This is an old standby.
  * Merge two sorted linked lists
  * Find the middle item in a linked list
  * Reverse a linked list in place. Another old, familiar face.
  * Is a list palindromic?
  * The classic "XOR next and previous pointers", harder to do in type safe Go.
  * Remove kth Last element of a list
* [RPN calculator](https://github.com/bediger4000/reverse-polish-problem) Reverse polish notation calculator.
* [Collatz conjecture](https://github.com/bediger4000/collatz-conjecture-puzzle) question.
* [Array rotation algorithms](https://github.com/bediger4000/array-rotation-algorithms), these come up a lot.
* [List manipulation problem](https://github.com/bediger4000/addition_puzzle), do 2 numbers in a list add to a given sum.
* [Reverse a string](https://github.com/bediger4000/golang-unicode-string-reversal), a silly problem, but it has depths if it's a Unicode string.
* [Print a string zig-zag](https://github.com/bediger4000/zigzag-programming-problem)
* [Estimate Pi](https://github.com/bediger4000/estimate_pi) using a Monte Carlo method. People have done this in the real world.
* [Find if a string could be a palindrome anagram](https://github.com/bediger4000/possible-palindromes)
* [Recreate binary search tree from a post-order traversal](https://github.com/bediger4000/postorder-tree-traversal) I think this algorithm is unique.
* [AVL binary search trees](https://github.com/bediger4000/avl_tree). This would be an advanced interview question indeed.
* [String representation of binary tree](https://github.com/bediger4000/binary-tree-odd-string-rep). You may not get what you are looking for.
* [Great Tree List Recursion Problem, Go](https://github.com/bediger4000/tree-list-recursion-go)
* [Great Tree List Recursion Problem, C](https://github.com/bediger4000/tree-list-recursion-c)
* [Pour water from jug to jug](https://github.com/bediger4000/egyptian-waterjar-puzzle) just to get a non-jugful amount.
* [Kaprekar's Constant](https://github.com/bediger4000/kaprekar)
* [Flipping N fair coins](https://github.com/bediger4000/fair-coin-flipping), eliminating all that come up tails, then repeating.
* [Soundex algorithm](https://github.com/bediger4000/soundex), Soundex in Go.
* [Roman numerals to decimal](https://github.com/bediger4000/romannumerals)
* [Sort list](https://github.com/bediger4000/reverselistsort) using only an array-reverse operation.
* [Boggle-like game](https://github.com/bediger4000/boggle-question) find a word according to Boggle-game rules
* [Balanced parens/brackets/braces](https://github.com/bediger4000/balanced-parens)
* [Run-length encoding](https://github.com/bediger4000/runlength-encoding)
* [Job scheduler](https://github.com/bediger4000/jobscheduler)
* [Markov chain](https://github.com/bediger4000/markov-chain)
* Make a [stack from a heap](https://github.com/bediger4000/stack)
* [Reverse bits](https://github.com/bediger4000/bitsreversed) of an integer
* [Decipher single-byte-XORed ciphertext](https://github.com/bediger4000/singlexor) 

I've tried to either solve them in a unique or lesser-known fashion,
or explore them more fully with alternate solutions.
I've also tried to include an analysis of the question,
maybe from a programming point of view,
but also from the point of view of what an interviewer could legitimately expect from a developer in an interview, and why.

My takeaway after looking at all of these is that Daily Coding Problem doesn't rate a problem very accurately.
Job candidates simply can't feel bad if an interviewer asks what they
consider an "easy" problem, and the candidate can't solve it.
A lot of these problems require insight that might not arrive in the stress of an interview.
The flip side of this is that the interviewer should have some solution in mind,
a solution appropriate for the job in question,
and the seniority of the candidate.
The interviewer might not get what they're interested in from any given candidate.
