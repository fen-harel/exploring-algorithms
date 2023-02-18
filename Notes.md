# Big'O Time-Space complexity

Approximate growth with respect to input.

Constants are mostly ignored as mostly the worst case scenario is taken into
account.

Meaning : 20N -> O(N), N+29 -> O(N)

`N = 1, O(10N) = 10, O(N^2) = 1 N = 5, O(10N) = 50, O(N^2) = 25 N = 100, O(10N) = 1000, O(N^2) = 10,000 // 10x bigger`

N^2 complexity, although much slower for larger programs, are actually faster
than 10N in shorter cases.

## O(n logn)

Half the ammount needed to search (logn), but must search once throughout
length of input n to do so

## O (log n)

Binary search trees

## O (sqrt(n))

---

# Data Structures

## Arrays

### Arrays: Insertion, Deletion

`a + width * offset`

where;
a = memory address of array
width = size of type (i.e. 8bit or 16bit int)
offset = index

Operation is O(1) => Constant Time

Constant Time = No.of operations is constant regardless of input size
