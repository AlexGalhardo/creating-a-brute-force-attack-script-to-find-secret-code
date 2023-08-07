
<div align="center">
<h2 align="center">Brute force attack script to find secret code using NodeJS Paralelism</h2>
</div>

<https://github.com/AlexGalhardo/Software-Engineering/assets/19540357/ed9bb26c-402d-45d4-9def-da3576967718>

## INTRODUCTION

- It is quite common for systems to use 6-digit secret codes to authenticate users.
- Delivery usually via email or SMS
- For example: 435 657

## Algorithm

- In this algorithm, using parallelism, the algorithm uses the 8 available CPUs in parallel here on my machine.
- I made a logic so that each worker processes an amount of equal numbers.
- Example: if I have 32 possible numbers to check, each worker will check 4 different numbers, in parallel, at the same time.
- When one of the workers finds the secret code, it sends a message to the master cluster of the 8 workers to finish the work of all of them.

## CONCLUSION

- I made this algorithm for didactic purposes, and for pure curiosity/technical interest.
