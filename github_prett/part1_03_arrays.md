# 1. the difference between static and dynamic arrays
static arrays need specifying their size before allocation while dynamic arrays can grow or shrink automatically

# 2. What are run-time complexities of static array?
lookup by index: O(1), lookup by value: O(n), insertion: O(n), deletion: O(n)

# 3. Analize the run-time complexity for finding the index of an item in an array?
Best case: O(1), worst case: O(n), so -> the run-time complexity: O(n) (consider the worst case scenario)

# 4. Vector vs ArrayList in Java
 vectors grow 100% while Arraylists grow 50%. Vector mothods are synchronized

# 5. What are the 2 limitations of arrays?
1.the size of the array have to be known at creation time 2.they are slow when we need to add or remove a lot of items from them 
