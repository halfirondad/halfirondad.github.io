---
layout: post
date: 2019-03-07 21:52
title: 'This is a test'
category:
- test
tags:
- 
---
This is a test

It has 2 lines

    def foo
      puts 'foo'
    end

- List item 1
- List item 2

> quote example
> quote line 2

Below is a code extract

{% highlight python %}
# Python program to check if the input number is prime or not

num = 407

# take input from the user
# num = int(input("Enter a number: "))

# prime numbers are greater than 1
if num > 1:
   # check for factors
   for i in range(2,num):
       if (num % i) == 0:
           print(num,"is not a prime number")
           print(i,"times",num//i,"is",num)
           break
   else:
       print(num,"is a prime number")
       
# if input number is less than
# or equal to 1, it is not prime
else:
   print(num,"is not a prime number")
{% endhighlight %}

That's about everything