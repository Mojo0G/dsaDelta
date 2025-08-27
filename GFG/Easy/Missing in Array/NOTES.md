
          Missing in Array

          - Summary: The code utilizes an array to store input numbers.  It leverages the XOR bitwise operator to find the missing number. First, it XORs all numbers from 1 to n (n being the expected size of the array including the missing number). Then, it XORs the result with all numbers present in the input array. The final XOR result represents the missing number because XORing a number with itself cancels it out.

          - Time Complexity: O(n) because both loops iterate through the array once, where n is the length of the array.
          - Space Complexity: O(1) because it only uses a constant amount of extra space to store variables like n and xor, regardless of the input array size.
          