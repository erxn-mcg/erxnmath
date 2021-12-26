---
title: "Understanding Primes"
date: 2021-12-19
tags: ["prime numbers", "maths", "number theory"]
draft: false
---

## The Basics

Prime numbers are arguably the **most** important numbers in mathematics - and for good reason! Primes are the *basic building blocks* of our number system, much like how letters are the building blocks of words. In fact, primes are so important that many number theorists will dedicate entire careers to exploring interesting theories about their quantity and distribution.

What is a prime number? This may be a very simple question, but it is very important that the answer is considered before we look any deeper into the ideas of primes. 
> A prime number is defined as being a number greater than 1 which has only two factors: 1 and itself. This means that it is unable to be broken up into smaller integers in the form `m x n`, so cannot be factored. 

There is often confusion over whether 1 is a prime number or not: 1 is not considered to be a prime number by most mathematicians because it would prove to be an annoying exception to many rules about primes. If 1 were a prime number, then the `fundamental theorem of arithmetic` would have to be changed since it currently states that every `composite` number can be written as a product of primes in *'exactly one way'*. If we considered 1 to be a prime, then we could write, for example, the number 15 as `3 x 5`, but we could also write it as `3 x 5 x 1`, or `3 x 5 x 1 x 1`. So you see that 'exactly one way' would have to be taken out, and this would have quite profound consequences for other areas of mathematics. As a result, many mathematicians consider the number 1 to be a special type of number which is neither prime, nor composite! 

## Predicting Primes

In a 1975 lecture, D. Zagier commented, 
> 'Despite their simple definition and role as the building blocks of the natural numbers, the prime numbers grow like weeds among the natural numbers, seeming to obey no other law than that of chance, and nobody can predict where the next one will sprout.' 
While this is the case, prime numbers also follow rules with strict conformity! However, it is the **finding** and the **proving** of these rules being incredibly difficult which make prime numbers as interesting and mysterious as they are. 

To start of nice and simply, almost everyone will be able to reel off a list of the first few prime numbers: `2, 3, 5, 7, 11, 13 ...` and so on. Even by looking at this list of 6 integers, we can clearly see the lack of uniformity in the distribution of the primes where they increase by **+1**, then **+2**, then **+2** again, then **+4**, and then back to **+2**. This is very messy and there is no *concrete proof* to describe when the next prime is going to crop up. Existing theorems are either very *contrived* and therefore practically unhelpful, or simply tackle a very *general* property of primes, such as that they are all - except 2 and 3 - either 1 more or 1 less than a multiple of 6.

One thing that we are certain of however, is that there are infinite primes. This may seem counterintuitive as you would think that as numbers get larger, there is a lower probability of ot being prime since there are more numbers smaller than it which could be factors of it, but actually primes go on forever. And, to make things even better, the proof of this is incredibly elegant:
> If we were to assume that there was a **finite** number of primes, with the largest being __*p<sub>n</sub>*__:
> - We could say that some integer N is the product of all these primes plus 1: N = p<sub>1</sub> x p<sub>2</sub> x ... x p<sub>n</sub> +1
> Since all composite numbers can be written as a product of two or more primes, we can conclude that:
> - N is not divisible by any primes in the list since there will always be a remainder of 1
> Therefore, N must be either a prime itself, or divisible by a prime that is greater than p<sub>n</sub>
> ***
> This contradicts our initial assumption, meaning that there must be an infinite number of primes!

## Primes in Nature

## Primes in Cryptography

## The Future of Primes
