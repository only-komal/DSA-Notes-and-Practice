# Sliding Window

## When to use
- Contiguous subarray / substring
- Max / Min / Longest / Count
- Constraints require O(n)

## Core idea
Maintain a window using two pointers and adjust size based on condition.

## Steps
1. Initialize left = 0
2. Expand right pointer
3. Update data structure
4. Shrink window if invalid
5. Update answer

## Code Skeleton
while (r < n):
    add(arr[r])
    while (invalid):
        remove(arr[l])
        l++
    update_answer()
    r++

## Common mistakes
- Forgetting to shrink window
- Using fixed window when variable needed

## Variants
- Longest substring without repeating characters
- Max sum subarray of size K
