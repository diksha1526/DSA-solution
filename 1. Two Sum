class Solution:
    def twoSum(self, nums: List[int], target: int) -> List[int]:
        for i in range(len(nums)):
            r=nums[i+1:]
            if (target - nums[i]) in r:
                return [i,i+1+r.index(target-nums[i])]
            
