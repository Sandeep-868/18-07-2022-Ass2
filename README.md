# 18-07-2022-Ass2
class Solution:
    def isPerfectSquare(self,num: int) -> bool:
       i=1
       while(i*i<num):
            if((num%i==0)and(num/i==i)):
                return False
                i=i+1
            else:
                return True
