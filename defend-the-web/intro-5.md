# Intro 5

## Assignment

In this challenge, we've been given a classic login prompt. To pass this level, we need to find the correct password. Let's get into it!



## Analyze

Right away, we're faced with a login prompt, but we don't know the password yet. Let's check the page source code again.

To quickly close the login prompt, press <mark style="color:orange;">ESC</mark>. Now, let's view the source code by pressing <mark style="color:purple;">CTRL+U</mark>.

At first glance, we don’t see anything related to the password. So, let's search through the entire code by pressing <mark style="color:green;">CTRL+F</mark> and typing `password`.

We find that on **lines 421-425**, JavaScript is exposing the correct password!



## Findings

In this challenge, we examined the source code once again. We encountered a different authentication form than we're used to, but that didn’t stop us!

We learned how to:\
✅ Quickly close a login prompt.\
✅ Open the page source code.\
✅ Search for key terms efficiently.
