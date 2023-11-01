# Problem-Solving Template
## **1768.) Merge Strings Alternately**
### **Problem Description:**
```
You are given two strings word1 and word2. Merge the strings by adding letters in alternating order, starting with word1. If a string is longer than the other, append the additional letters onto the end of the merged string.

Return the merged string.
```
### **URL**
[1768.) Merge Strings Alternately](https://leetcode.com/problems/merge-strings-alternately/?envType=study-plan-v2&envId=leetcode-75)
***

## **Understanding the Problem:**
1. - [x] **Can I restate the problem in my own words:**
    > Take two stings and enter each letter of the stings starting from the first letter of word1 and alternate between the two words with their corresponding letters
2. - [x] **What inputs go into the problem:**
    > Word1
    > Word2
3. - [x] **What is the expected output:**
      + - [x] *Data type:*
            > One String with a combination of letters from each word
      + - [x] *Example:*  
            > (hello) (world) hweolrllod
4. - [x] **Can the output be determined from the input:**
            > Yes
5. - [ ] **How should I label the data:**
      + - [x] *Function Names:*
            > mergeAlternately
      + - [x] *Inputs:*
            > word1
            > word2
      + - [x] *Variables:*
            > result
            > i
            > j
      + - [x] *Outputs:*
            > returned string
6. - [ ] **Concrete Examples:**
      	- [x] **Simple Examples:**
        + - [x] *Input 1:*
            > bottle
            > ham
      	+ - [x] *Output 1:*
            > bhoatmtle
      	+ - [x] *Input 2:*
            > twitch
            > streaming
      	+ - [x] *Output 2:*
            > tswtirtecahming
        + - [x] *Input 3:*
            > first
            > content
      	+ - [x] *Output 3:*
            > fciornstent
      	- [ ] **Complex Examples:**
      	+ - [ ] *Input:*
            > 
      	+ - [ ] *Output:*
            >
7. - [x] **Edge Cases: (NaN, Null, Error, Not Found, etc…)**
    > hyphenated words
      - Could sanitize the inputs
    > more than one word per input
      - Either add the whitespace or sanitize the inputs
8. - [x] **Break It Down Step-by-step:**
    - create a while loop that will run until both words are empty by incrementing the word.length until it is equal to the length of the word.
9.  - [x] **Can You Solve This Problem:**
      - [x] *Yes, Do it*
      - [ ] *No, What simpler problems can you solve?*
        >
10. - [ ] **REFACTOR AND CLEAN UP!!!**
