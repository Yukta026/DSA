Two Pointer Pattern Learnings - 

1) Understand the problem well to determine whether pointer will move away or towards each other.
2) Proper setting of looping conditions otherwise leads to TLE or MLE.
3) Have special focus on looping conditions to skip duplicates or irrelevant values.
   For example - Placing while(nums[left] == nums[left-1]) {left++;} within the if condition handles skipping the duplicates and prevents MLE.
