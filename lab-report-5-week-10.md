# Lab Report 5 Week 10

Bryan Nguyen A16661105

[Link to my repo](https://github.com/b4nguyen/markdown-parse)
[Link to other repo](https://github.com/ucsd-cse15l-w22/markdown-parse)

## How I found the different results:
I put both outputs into txt files and paired the outputs with the file names. Then I just looked at both of them side by side and found the differences manually.

## Results:
[Test file 342:](https://github.com/ucsd-cse15l-w22/markdown-parse/blob/main/test-files/342.md)

My MDP Output:
<img width="115" alt="342MyOut" src="https://user-images.githubusercontent.com/97714611/157829164-4d5faab3-c004-43d3-b45e-b29ecc2b51fa.png">

Lab 9 MDP Output: <img width="104" alt="342ClassOut" src="https://user-images.githubusercontent.com/97714611/157829273-0342913c-c9b7-4771-9e19-ac2787147f06.png">

Expected Output: []

Explanation: 

The error in the MDP file given by lab 9 is that it only accounts for the brackets and has no way of knowing if the text within the brackets is an actual link or not.
It strictly focuses on the brackets and should probably have something to check if the link is an actual link.

Code that should be changed:

<img width="534" alt="Screenshot_1" src="https://user-images.githubusercontent.com/97714611/157831749-0a8cfa85-dd35-422c-8e81-7028d961058b.png">



[Test file 201:](https://github.com/ucsd-cse15l-w22/markdown-parse/blob/main/test-files/201.md) 

My MDP Output: <img width="109" alt="201MyOut" src="https://user-images.githubusercontent.com/97714611/157829396-02c7e0bf-51ce-45dc-b9c6-855de6373699.png">

Lab 9 MDP Output: <img width="104" alt="201ClassOut" src="https://user-images.githubusercontent.com/97714611/157829455-83942e8e-e7a2-4239-8b40-a4a60360722f.png">

Expected Output: []

Explanation: 
I think the problem here is that the code provided in the lab does not check if the link inside is an actual link, and it doesn't account for anything other than the parentheses and square brackets. Here there was something in between, but the code ignored that and skipped straight to what it thought was a link.

Code that should be changed:


<img width="534" alt="Screenshot_1" src="https://user-images.githubusercontent.com/97714611/157832318-de56e688-1178-4520-800e-570e2ff3d498.png">


