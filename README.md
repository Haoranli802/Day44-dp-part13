# Day44-dp-part13

● 1143.最长公共子序列 

dp[i][j]代表字符串一0到i长度和字符串二0到j长度的最长公共子序列，

状态转移：如果i和j字符相等，那么dp[i][j] = dp[i - 1][j - 1] + 1

如果不相等，那么dp[i][j]就会继承dp[i - 1][j]和dp[i][j - 1]的最大值。

O(NM), O(NM)

● 1035.不相交的线   

跟1143一样的解法

● 53. 最大子序和  动态规划 
