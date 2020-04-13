---
layout: post
title:  "2020.04.11"
date:   2020-04-11 11:50:29 -0700
categories: challenge
permalink: /2020/04/11

---

**Overview**

I decided that writing a daily journal like this would be a great writing practice. Also, this could count as 0.5 commit per day, right? This year, I noticed that my foundations (especially around Amazon Web Services and general coding/design best practices) have become fragile. While going through interviews a few months ago, I learned that ideal `interview ready` is when your coding skills are *already apt* but you just need some brush up on interview skills, instead of having to go through Cracking Code and numerous Leetcode problems within a few days. Thus, I decided that whether I am out looking for new opportunity or not, I should always carve out some time to be keen in my problem solving skills.


**TODOs**
- [x] 30 Day Leetcode Challenge
- [x] Read `Clean Architecture` - Open/Closed Principle
- [x] 자바 웹 프로그래밍 Next Step Chapter 2

---

**Leetcode: Diameter of Binary Tree**

The question asks to find the longest diameter of the tree. 
Initially, I missed the case of checking against the 2nd and 3rd variables :( 
This boils down to asking this question to each node: 
```
Math.max(
    (longest depth from left) + (longest depth from right),
    longest diameter of the subtree with left as the root,
    longest diameter of the subtree with right as the root
)
```



\[1\] https://leetcode.com/explore/featured/card/30-day-leetcoding-challenge
