# Palindrome-Number

<!--
Note - Any content mention below in `<!-- ->` blocks are just comments
to help you fill-up the issue. It won't be visible in the actual issue after
you click on submit.
-->










#### Code you used for Submit/Run operation


```
// Palindrome Number
class Solution {
    public boolean isPalindrome(int x) {
        
        int temp = x;
        
        int rev = 0;
        
        while(temp>0&&temp!=0)
        {
            int ld = temp%10;
            
            rev = rev*10+ld;
            
            temp = temp/10;
        }
        
        return (rev==x);
        
    }
}
```

#### Language used for code
java 


#### Expected behavior
<!-- A clear and concise description of what you expected to happen in
contrast with what actually happened. -->
this question seems to be an easy but i like the concept used in this question as palindrome is playing a unique or best role in this
problem



#### Screenshots

![palindrome](https://user-images.githubusercontent.com/53940939/135462837-fbbd57f6-5178-4286-9fe4-4bf6fd2e76da.png)




Thankyou :)
