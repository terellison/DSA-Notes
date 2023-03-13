# Time Complexity

## Experimental Analysis

Measures the <u>actual</u> time an algorithm took to execute. Since this requires writing, compiling, and running different algorithms, this method is inefficient.

## Theoretical Analysis

In theoretical analysis, an algorithms execution time and space required to execute are defined as a function of the algorithm's input.

<br/>

<img src="https://paper-attachments.dropbox.com/s_2D428973624E7FC84C7D69D11421DE762BEA6B6F3361231FCDCAE0425D14526F_1664885448372_Untitled.drawio+17.png">

<br/>

### Time Complexity Examples

<br/>

| Name      | Complexity | Description          | Quality |
|-----------|------------|----------------------|---------|
| Quadratic | O(N^2)     | Time grows as a function of the square of input (e.g. N = 10, Time = 100s)| Horrible |
| Linear    | O(N)       | Time is proportional to the amount of input (e.g. N = 10, Time = 10s)| Fair |
| Logartihmic | O(log N) | Time gorws insignificantly as input grows (e.g. N = 10 T = 10s; N = 10,000 T = 1.1s); Search space is halved in each iteration | Good |
| Constant  | O(1)       | Time is constant irrespective of the amount of input (e.g. N = 10, Time = 1s; N = 1000, T ~1s)| Excellent |

# Real-World Examples

## Common operations with O(1) time complexity

- Accessing an array via index (i.e. `array[0]`)
- Insertion in a linked list
- Push / Pop on a stack
- Insertion or removal from a queue
- Accessing a hash map

<br/>

> Note: O(1) operations depend on <u>things that are always known to be true</u>. For example, if an array is sorted, we know that the max value will always be the end. No computation is need for these sort of operations. This is why their runtime is constant

<br/>

## Common operations with O(n) time complexity

- Traversing an array linearly
- String comparison
- Checking for a palindrome

<br/>

> Note: O(n) operations depend <u>solely</u> on the amount of input. Worst case scenario you will do one operation for each input