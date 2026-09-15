# Problem: Two Sum (Easy)

**Link:** https://leetcode.com/problems/two-sum/

## Approach

I used a brute-force approach by checking every possible pair of elements in the array. For each pair, I check whether their sum is equal to the target. Once the required pair is found, its indices are returned.

## Complexity

- Time: O(n²)
- Space: O(1)

## Notes

The solution must not use the same element twice. I also tested a duplicate-value case such as [3, 3] with target 6.
