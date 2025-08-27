
          Two Sum

          - Summary: This algorithm utilizes a hashmap (dictionary in Python) to efficiently find two numbers within a list that sum up to a target value. It iterates through the input list 'nums', calculating the complement needed to reach the target for each number.  If the complement is found in the hashmap, it means a pair that sums to the target has been identified, and their indices are returned. Otherwise, the current number and its index are added to the hashmap for future lookup.

          - Time Complexity: O(n) because the algorithm iterates through the input list 'nums' once.  The hashmap lookups (in and adding) have an average time complexity of O(1).
          - Space Complexity: O(n) because in the worst-case scenario, the hashmap 'num_to_index' will store all the numbers from the input list 'nums', resulting in space proportional to the input size.
          