# Sale Season

This problem is about calculating the final amount Chef has to pay after applying a fixed discount based on how much he spent (X). The discount follows slab rules: no discount for X ≤ 100, ₹25 off if X is between 101 and 1000, ₹100 off for values between 1001 and 5000, and ₹500 off for any amount above 5000. The program reads the number of test cases T, then for each test case, reads X, checks which slab it falls into using if-else conditions, calculates the discount, and subtracts it from X.

The logic uses descending order of slab checks (> 5000, then > 1000, and so on) to ensure the correct discount is applied without overlapping. After determining the correct discount, it prints the final payable amount (X - discount) for each test case on a new line.
