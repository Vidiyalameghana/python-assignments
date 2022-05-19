class Solution:
    def subarraysDivByK(self, nums: List[int], k: int) -> int:
        rs=ans=0
        dp={0:1}
        
        for A in nums:
            rs+=A
            key=rs%k
            
            if key in dp:
                ans+=dp[key]
                dp[key]+=1
            else:
                dp[key]=1
                
        return ans
