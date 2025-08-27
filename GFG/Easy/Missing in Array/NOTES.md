
          Missing in Array

          - Summary: The code utilizes an array to store input numbers. It employs the bitwise XOR operation to find the missing number. First, it XORs all numbers from 1 to n (n being the expected array size including the missing number). Then, it XORs all elements present in the input array with the previously calculated XOR value. The final XOR result represents the missing number because XORing a number with itself results in 0, thus canceling out the present numbers and leaving only the missing one.

          - Time Complexity: O(n) because both loops iterate through the array (or numbers from 1 to n) once, where n is the length of the input array.
          - Space Complexity: O(1) because the algorithm uses a constant amount of extra space to store variables like 'n' and 'xor', regardless of the input array size.
          