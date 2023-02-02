# Bitonic Soter
Mini Project for Advance Digital Design Course
## How it Works 
Bitonic Sort is a classic parallel algorithm for sorting. 
* The number of comparisons done by Bitonic sort is more than popular sorting algorithms like Merge Sort [ does O(log N) comparisons], but Bitonic sort is better for parallel implementation because we always compare elements in a predefined sequence and the sequence of comparison doesn’t depend on data. Therefore it is suitable for implementation in hardware and parallel processor array.
* Bitonic Sort can only be done if the number of elements to sort is 2^n. The procedure of bitonic sequence fails if the number of elements is not in the aforementioned quantity precisely.
#### Components of a Bitonic Soter
* The basic building of a bitonic soter is Compare and Exchange Block
### Schematic
![](https://i.imgur.com/IyS0d5v.png)
### Working 
* The code is done in three stages
* The stage-1 is design and Implementation of Compare and Exchange Block
* The stage-2 is design and Implementation of 4-bit bitonic soter
* The stage-3 is design and Implementation of 8-bit bitonic soter by combining stage 1 and stage 2
 

