# Lab Report 4 Week 8

Bryan Nguyen A16661105

[Link to my repo](https://github.com/b4nguyen/markdown-parse)
[Link to other group's repo](https://github.com/aajc/markdown-parse)
[Link to the other group's repo where I edited the tests](https://github.com/b4nguyen/markdown-parse2)



## My Group MarkdownParseTest.java Test Cases

<img width="400" alt="MyMDPTests" src="https://user-images.githubusercontent.com/97714611/155679989-fd246329-8d36-47b1-9b12-70518f076b16.png">
<img width="533" alt="MyMDPFails" src="https://user-images.githubusercontent.com/97714611/155680138-ec8b5545-bbc2-4e55-bc0c-3ced7d845ec5.png">

Answer for Snippet 1: 
I think the changes we would have to make would not be considered small for this one. It would be a couple lines to account for weird bracket placement, on top of the fact
that the current way the tester works does not account for the new files.

Answer for Snippet 2:
I think the changes would be considered a small fix for this one. It would only take a few lines to account for the additional brackets and parentheses. Having to change the way the 
tester works could possibly push it over a 10 line change, but I doubt it.

Answer for Snippet 3:
I think the changes for this one would be small. The current version of MDparse does not have anything accounting for multiple line links, but I think adding
something small that checks for a line break would suffice.

## Other Group MarkdownParseTest.java Test Cases

<img width="607" alt="OtherMDPTests" src="https://user-images.githubusercontent.com/97714611/155680162-5dede1c3-4786-4ed7-a434-431c5f7d8531.png">
<img width="616" alt="OtherMDPFails" src="https://user-images.githubusercontent.com/97714611/155680175-48b5e3aa-a8ce-46fc-8690-4bf6aa4caa14.png">

Answer for Snippet 1:
I think the change would be considered small. I don't think adding a couple lines to check for weird bracket placement inside would take more than 10, probably
just a simple loop somewhere.

Answer for Snippet 2:
I think that the change for this would also be pretty small. I think it would probably take a nested loop somewhere and that's it.

Answer for Snippet 3:
I think the changes for this one would also be small. It would only take a couple lines to check for the line breaks, and after that it should be okay.

