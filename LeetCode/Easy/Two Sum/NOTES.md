
          Two Sum

          - Summary: This algorithm utilizes a hashmap (dictionary in Python) to efficiently find two numbers within a list that sum up to a target value. It iterates through the input list; for each number, it checks if the complement (target - number) exists in the hashmap. If found, it returns the indices of the two numbers; otherwise, it adds the current number and its index to the hashmap. If no solution is found after iterating through the entire list, it returns an empty list.

          - Time Complexity: O(n) because the algorithm iterates through the input list once. Hashmap lookups have an average time complexity of O(1).
          - Space Complexity: O(n) because in the worst-case scenario, the hashmap may store all n numbers from the input list.
          