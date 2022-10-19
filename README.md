# Stock-Analysis

## Overview of Project: 
  In this project, we refactored code. The purpose of this project is to optimize our code to run more efficiently. 
## Results: 
When running both codes, the results of the stock performance for 2018 are the same, however, one code runs faster. 

![2018 performance](https://user-images.githubusercontent.com/114771735/196824153-fdb223b3-5f24-4e00-8ac5-40eb5192b95f.png)

In the below image, we see the runtime of our original code at .164 seconds.

![VBA_Challenge_1_2018](https://user-images.githubusercontent.com/114771735/196824211-2374dd3f-5f87-4d8a-bf6c-8403db3a201f.png)

In the below image, we see the new runtime of our refactured code at .140 seconds. 

![VBA_Challenge_Refractured_2018](https://user-images.githubusercontent.com/114771735/196824239-5d463c68-140c-492c-8a6d-e59d2543def8.png)

## Summary: 
## What are the advantages or disadvantages of refactoring code?

Having refactured coding can be advantagous if your dataset changes or you're working with a larger volume. You'll want to have flexible and fast codes since the seconds count. 
Disadvantages may be that you're refering back to an index, instead of the array. The source may not be as obvious as if you had an array with each ticker listed. 

## How do these pros and cons apply to refactoring the original VBA script?

Replacing the tickers with tickerIndex and having nested loops may cause errors in your script that can be tricky to resolve. When having both codes, I found that I had to stop the original code before running the refactored code. 
