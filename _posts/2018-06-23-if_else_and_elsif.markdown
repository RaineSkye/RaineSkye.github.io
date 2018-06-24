---
layout: post
title:      "If Else and Elsif"
date:       2018-06-24 02:23:43 +0000
permalink:  if_else_and_elsif
---


In Ruby, two of the most basic ways to tell your program to execute certain code, or control flow, are the If and else conditional statements. Conditional statements allow us to run different code if different conditions evaluate to true. 

People use control flow everyday.  For example, if it's a sunny day, you may take a walk outside.  Otherwise, you might stay indoors, or bring an umbrella when going out.

To write a conditional statement, we simply put a condition afer the "if", followed by a block of code.  The block of code that follows the If condition will execute if it evaluates to true.  If the "if" condition evaluates to false then the code does not execute.  

The "else" condition can be used to execute other code if the "if" condition evaluates to false.   Below is an example of this: 

if "this string" == "that string"
         puts "these two strings are not equal so they evaluate to false"
else
         puts "this block of code will get run if the above condition evaluates to false"
end

In this case, the two strings on either side of the comparative operator were not equivalent, and the "if" condition evaluates to false, and the computer goes down to the "else" condition and prints out the block of code before the "end" keyword.

If the "if" condition had evaluated to true, for example, "this string" == "this string", or 1+2 = 3, etc, the block of code after the if condition will run rather than pass to the "else" statement.  













