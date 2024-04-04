## What's this
https://blog.didierstevens.com/2009/11/22/quickpost-selectmyparent-or-playing-with-the-windows-process-tree/    
This is a project for parent process spoofing.

## How to use
step 1:Select a parent process and remember the pid

![check](image/check.png)

Step 2:Execute the following command. Implement parent process spoofing
```
SelectMyParent.exe notepad 928
```

![result](image/result.png)

Step 3:Using process explorer to view the process tree, you can see the successful spoofing

![success](image/success.png)

## Reference
https://pentestlab.blog/2020/02/24/parent-pid-spoofing

https://ired.team/offensive-security/defense-evasion/parent-process-id-ppid-spoofing
