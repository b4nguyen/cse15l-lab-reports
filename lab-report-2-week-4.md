# Lab Report 2 Week 4

Bryan Nguyen A16661105

---

## 1. Code Change One: 

Test File link: https://github.com/b4nguyen/markdown-parse/blob/main/test-file2.md (test-file2.md)

Error given when run:

![file2error (2)](https://user-images.githubusercontent.com/97714611/151540233-91d4fbdf-de44-4706-b4ce-b9d90f6b6099.png)

Solution committed:

![file2fix](https://user-images.githubusercontent.com/97714611/151540017-f029f4f5-e833-409f-a083-6edbf730c1ae.png)

Explanation: 
The relationship between the bug, the symptom, and the failure inducing input here is that the input is a file that the code is not prepared to read. 
Due to the fact that the code has a bug where there is a while loop that continually sets the index values to -1 if it doesn't find anything, and will run forever and create a memory error. The memory error shown is the symptom of the bug, where the loop has run so much that the storage ran out of space.

---

## 2. Code Change Two: 

Test File link: https://github.com/b4nguyen/markdown-parse/blob/main/test-file3.md (test-file3.md)

Error given when run:

![file3error](https://user-images.githubusercontent.com/97714611/151541046-0dc8ed6d-8a85-44c1-8cf1-a356405dbadb.png)

Solution committed:

![file3solution](https://user-images.githubusercontent.com/97714611/151541093-d0b6e99d-4c17-422b-874d-d8d7afd5b713.png)

Explanation:
Here the failure inducing input is a file with only closed square brackets and nothing else. This reveals a bug in the code, as the code searches for things that aren't there and then tries to set the index to -1. The symptom of this is the ```IndexOutOfBoundsException``` that is thrown, indicating something is wrong.

---

## 3. Code Change Three: 

Test File link: https://github.com/b4nguyen/markdown-parse/blob/main/test-file8.md (test-file3.md)

Error given when run:

![file8error](https://user-images.githubusercontent.com/97714611/151541965-b87b0a37-6513-4223-ba35-3f653541dd4a.png)

Solution committed: 

![file8solution](https://user-images.githubusercontent.com/97714611/151542015-ca59fc6e-b37c-4a40-8e1c-1293800126a9.png)

Explanation: Similarly to the error found with file 2, this failure inducing input file with only a single bracket in it reveals the same bug. The loop keeps running infinitely and the index keeps getting reset to -1, which causes it to overwhelm my memory and create an error. The symptom is the java heap space error shown, indicating that I'm out of space.

---
