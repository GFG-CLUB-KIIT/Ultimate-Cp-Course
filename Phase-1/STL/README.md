# STL (Standard Template Library)

The C++ STL (Standard Template Library) is a powerful set of C++ [template classes](https://www.tutorialspoint.com/cplusplus/cpp_templates.htm) to provide general-purpose classes and functions with templates that implement many popular and commonly used algorithms and data structures like vectors, lists, queues, and stacks.

## Major Components of STL library are following :-

### Containers

1. *Vector* : vector is a class that creates a dynamic array allowing insertions and deletions at the back
2. *Set* : set is an associate container for storing unique sets
3. *Multiset* : Multiset is an associate container for storing non- unique sets
4. *Map* : Map is an associate container for storing unique key-value pairs, i.e. each key is associated with only one value(one to one mapping)
5. *MultiMap* : multimap is an associate container for storing key- value pair, and each key can be associated with more than one value
6. *Stack* : It follows last in first out(LIFO)
7. *Queue* : It follows first in first out(FIFO)
8. *Priority queue* : First element out is always the highest priority element
9. *List* : list is the sequence containers that allow the insertions and deletions from anywhere
10. *Deque* : deque is the double ended queue that allows the insertion and deletion from both the ends


### Algorithms

1. *sort(first_iterator, last_iterator)* - To sort the given vector/array
2. **max_element(first_iterator, last_iterator)* - To find the maximum element of a vector/array
3. **min_element(first_iterator, last_iterator)* - To find the minimum element of a vector/array
4. count(first_iterator, last_iterator)* - To count the occurrences of x in vector/array
5. *find(first_iterator, last_iterator, x)* – Returns an iterator to the first occurence of x in vector and points to last address of vector ((name_of_vector).end()) if element is not present in vector
6. *lower_bound(first_iterator, last_iterator, x)* – returns an iterator pointing to the first element in the range [first,last) which has a value not less than ‘x’.
7. *upper_bound(first_iterator, last_iterator, x)* – returns an iterator pointing to the first element in the range [first,last) which has a value greater than ‘x’.
8. *next_permutation(first_iterator, last_iterator)* – This modified the vector to its next permutation
9. *distance(first_iterator,desired_position)* – It returns the distance of desired position from the first iterator.This function is very useful while finding the index
10. *reverse(first_iterator, last_iterator)* - To reverse a vector/array

### Iterators

1. [Iterators](https://www.geeksforgeeks.org/iterators-c-stl/) : As the name suggests, iterators are used for working upon a sequence of values. They are the major feature that allow generality in STL

--------------------------------------------

## Practise Problems




