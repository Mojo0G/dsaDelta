
          Two Sum

          - Summary: The algorithm uses a hash map (dictionary in Python) to store numbers and their indices. It iterates through the input array `nums`. For each number, it calculates the complement needed to reach the `target`. If the complement is found in the hash map, it means a pair adding up to the target has been found, and their indices are returned. Otherwise, the current number and its index are added to the hash map, and the iteration continues. If no solution is found after iterating through all numbers, an empty list is returned.

          - Time Complexity: O(n) because the algorithm iterates through the input array once.  Hash map lookups have an average time complexity of O(1).
          - Space Complexity: O(n) because in the worst-case scenario, the hash map will store all numbers from the input array, resulting in space proportional to the input size.
          