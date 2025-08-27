
          Missing in Array

          - Summary: The code utilizes an array to store input numbers. It employs the bitwise XOR operation to find the missing number. First, it XORs all numbers from 1 to n (n being the expected array size including the missing number). Then, it XORs all numbers present in the input array with the initial XOR result. The final XOR value represents the missing number because XORing a number with itself results in 0, canceling out existing numbers, leaving only the missing number.

          - Time Complexity: O(n) because the code iterates through the input array once and then iterates from 1 to n, where n is the size of the array. Both operations have linear time complexity.
          - Space Complexity: O(1) because the algorithm uses a constant amount of extra space to store variables like 'n' and 'xor', regardless of the input array's size.
          