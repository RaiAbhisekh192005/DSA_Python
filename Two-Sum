# 🧮 Two Sum Problem – Python DSA Solution

## Overview
This project solves the classic **Two Sum** problem using Python and basic data structures. The goal is to find two numbers in a list that add up to a given target.

## Approach
I used a **hash map (dictionary)** to store each number's index as I iterated through the list. For each number, I calculated its complement (`target - num`) and 
checked if that complement already exists in the map. If it does, I return the indices of the current number and its complement. This approach ensures **O(n)** time 
complexity, making it efficient for large inputs.

## Example

```
class Solution:
    def twoSum(self, nums: List[int], target: int) -> List[int]:
        num_dict = {}

        for i, num in enumerate(nums):
            complement = target - num

            if complement in num_dict :
                return [num_dict[complement], i]

            num_dict[num] = i

        return []

```
