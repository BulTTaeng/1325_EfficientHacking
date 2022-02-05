# 1325_EfficientHacking

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![image](https://github.com/Choi-JaeHyeok-21500749/1325_EfficientHacking/blob/main/1325_pro.PNG)

## What Algorithm should I use?

Graph Algorithm, dfs

## What was the key point and the hard part?

The hard part was I keep trying to apply dp...

Maybe we can use dp but I think that is very hard because of cycle.

For example , if input is like

3 3 

1 2

2 3

3 1

then it have cycle.

then, if we apply dp in here, the answer will be only 1 if we start from 1 to n or , it goes to infinite loop depends on your code.

So, keep checking the cycle and if we have the cycle, stop everything and apply max value among them to every node in cycle.

My code is just keep reset the visit array and if we find an new node, add one to the answer.

After searching is done, reset the visit array and answer and repeat it until n.

## Where can I get more help, if I need it?

You can contact me through email, which is wogur7496@gmail.com.
Thank you for visiting this github!
