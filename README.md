[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/FgMJElkj)
# Theory vs. Practice

- List 3 reasons why asymptotic analysis may be misleading with respect to
  actual performance in practice.

  1) Asymptotic analysis normally only accounts for the average or worst case scenarios in algorithms, but in the real world these cases are often different and unpredictable.
     
  2) In the real world, the efficiency of these algorithms can be altered by uncontrollable factors such as the hardware or programming language the algorithm is being ran on.
     
  3) In some cases, algorithms run at different speeds depending on what data structure it is working with and this is sometimes unaccounted for.
  

- Suppose finding a particular element in a binary search tree with 1,000
  elements takes 5 seconds. Given what you know about the asymptotic complexity
  of search in a binary search tree, how long would you guess finding the same
  element in a search tree with 10,000 elements takes? Explain your reasoning.
  
  We consider the time complexity of a binary tree to be O(log(n)).
  If 5 seconds = O(log(1000)),
     x seconds = O(log(10000)).
     log(1000) / log(2) is roughly equal to 10.
     log(10000) / log(2) is roughly equal to 13.3.
     (5 seconds / 10) = (x seconds / 13.3)
     It would likely take about 6.5 seconds to find the element in the tree.
  

- You measure the time with 10,000 elements and it takes 100 seconds! List 3
  reasons why this could be the case, given that reasoning with the asymptotic
  complexity suggests a different time.

  1) There is a possibility that the tree is very poorly balanced, causing the search time to be way higher than it should be.
 
  2) The hardware the program is being run on could be slow.
 
  3) There could be other compatibility issues within the program or computer itself that could cause a slower runtime.
  

Add your answers to this markdown file.
