1. Because all values smaller than node is on left and larger is on right and in order visits left (smaller) node (middle) then right (larger) respectively.
2. Root = 10: 1, 20, 30, 40, 50, 60; In order traversal would be very short on left side just go to 1, then visit node 10, then recursively go through right subtree many times.
3. Recursive vs Iterative traversal: Recursive is simpler to implement because it keeps calling itself. Iterative you must make a stack yourself and push and pop manually.
    Depth vs Breadth first search: Depth goes all the way down exploring one branch to leaf then works back up through each, vs breadth goes level by level to all inner nodes then leaves.
4. In like a maze to rule out which paths lead to a dead end and aren't worth going down vs trying each one fully.
