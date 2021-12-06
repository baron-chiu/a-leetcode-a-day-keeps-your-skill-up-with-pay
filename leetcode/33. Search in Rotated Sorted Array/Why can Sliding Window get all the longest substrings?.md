# Why can Sliding Window get all the longest substrings?

- From: [[3. Longest Substring Without Repeating Characters]]
- Assignee: #BC 
- Tags: #Discussion 

## Define Sliding Window

The Sliding Window begins at the first letter. It finds the first longest substring withoug repeating characters beginning from the first letter. It's the first window.

Say the character, **$**, next to the end of the first window. The window must contain the charatcter, **$**. Let the next window begin at the character next the the first **$**. Collection all the windows in such precedures is the sliding window we have.

## Proof

### Assumption
THE sliding windown gets all the longest substring if and only if every substring is contained by the THE sliding window. 

### Reasoning

If THE sliding windown indeed gets all the longest substring, we can obtaint the longest substring from THE sliding window.