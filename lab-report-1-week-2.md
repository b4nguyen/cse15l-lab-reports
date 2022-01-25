# Lab Report 1 Week 2

Bryan Nguyen A16661105

## 1. VScode: 
Go to the VScode website and download it. Follow the instructions on the installer. Download here at https://code.visualstudio.com/.

![Screenshot_1](https://user-images.githubusercontent.com/97714611/149601654-52d643bd-2b38-4428-ae0e-f3b384a2ca66.png)


## 2. Connecting to ssh:
Open VScode and press ctrl + ` to open the terminal. Type in "ssh cs15lwi22zz@ieng6.ucsd.edu" but replace zz with the letters in your account. Then type in your password.

![Screenshot_3](https://user-images.githubusercontent.com/97714611/149601963-7c29bde3-36d8-41e1-a57d-d6839d5b407e.png)

## 3. Trying out commands:
Now you can try some commands. Some basic ones are ls (lists files in directory), cd (changes directory), and mkdir (makes directory).

![Screenshot_4](https://user-images.githubusercontent.com/97714611/149602056-25e1db70-bfba-4683-8cba-237701a59551.png)

## 4. Moving a file: 
You can move a file to SSH by using the scp command. Just type scp (filename) cs15lwi22zz@ieng6.ucsd.edu:~/.

![Screenshot_5](https://user-images.githubusercontent.com/97714611/149602366-795142c0-973b-4481-83fe-7718735ea134.png)

## 5. SSH keygen: 
Then use ssh keygen on your pc. Then log into the ssh and make a directory by typing mkdir .ssh. Logout, go back to your pc, and copy the key to your ssh directory.

![Screenshot_6](https://user-images.githubusercontent.com/97714611/149602719-4b82287e-d723-46c5-94d8-eb93fc5d89a5.png)

## 6. Easier ways to run:
You can add a command in quotations at the end of the ssh command to run it, or add semicolons to run multiple.

![Screenshot_7](https://user-images.githubusercontent.com/97714611/149602796-2f0f894b-3578-421a-95f6-8e01516eac7c.png)
