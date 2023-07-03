---
name: unexpected outputs & weal test cases
about: not getting appropriate outputs
title: ''
labels: ''
assignees: ''

---

<!--
Note - Any content mentioned below in `<!-- ->` blocks are just comments
to help you fill up the issue. It won't be visible in the actual issue after
you click on submit.
-->

#### Your LeetCode username
RawahaKhan (ID: rawaha707)

#### Category of the bug
- Solution
- Missing Test Cases 


#### Description of the bug
While typing, I usually run the code to see what's giving me in the output. However, instead of it, it either gives me an error or returns some other problems that I couldn't expect in normal IDEs. Like the incomplete code of Leetcode Problem 20. Valid Parentheses, if you observe the  mentioned Python code, I've used elif statement  and pass statement in it. I was expecting no error but gave 'invalid syntax'

#### Code you used for Submit/Run operation
<!-- 
Please make sure you wrap your code with ``` tags. 
Otherwise we may reject your request. 
-->

```
class Solution(object):
    def isValid(self, s):
        stack = []
        pairs = {'(':')','[':']','{':'}'}
        for i in s:
            if i == '(' or i == '[' or i == '{':
                stack.append(i)
            elif not stack or \
                pass
               
        return not stack

```

#### Language used for code
<!-- C++ -->


#### Expected behavior
<!-- A clear and concise description of what you expected to happen in
contrast with what actually happened. -->



#### Screenshots
<!-- If applicable, add screenshots to explain your issue. -->



#### Additional context
<!-- Add any other additional context about the bug. -->
