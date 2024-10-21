# Shitcode for Robot Dreams 2024
## Main info:
- To run this code you need to have instaled `C#`, `C++` and `Python` compilers. I had instaled `python` before, also `C#` is on my Microsoft Visual Studio. But for `C++` I instaled `MinGW`, specifically `g++`. (https://youtu.be/2bZfdWCMBMI) - tutorial to instal this if you need.
- When you instaled MinGW there could (or not) be some troubles with `dll` files:
  - libgmp-10.dll
  - libiconv-2.dll
  - libisl-15.dll
  - libmpc-3.dll

I added them to repository and you need to copy them into `C:\...\MinGW\bin\` . Also into `C:\...\MinGW\mingw32\bin\` .
And for sure into `C:\...\MinGW\`
- As you can notice, there is a little bit of `c++` code, and to run it fully in one line is imposible (for my knowledges) due to `#include ...` line.
So near this line is `\n`, but when you execute main program you not see any other files except Program.cs
- I created it by Visual studio code. And such files as .sln and .csproj should be ignored by moderators of competition.

## Task
This code tells you if your number is palindrom or not.

## Properties
- It is one line shitcode. Whit length 990 characters.
- Firstly, it is `C#` code.

It creates our variables, some strings, and compiles some other code.

Also it creates some files and your task is to write a proper file path, ***SO A SUM OF ALL CHARACTERS WILL BE `<=1000`***. Here is a code which you need to rewrite(starts from `ch: 113` and `ch: 418`):
```C#
e=@"C:\MinGW\bin\g++.exe";x="palindrom";n=Console.ReadLine();o=@"C:\Shitcode\t.txt";q=@"C:\Shitcode\t.cpp";w=@"C:\Shitcode\t.exe";h=@"C:\Shitcode\t.cpp";z="#include<bits/stdc++.h>\nusing namespace std;
```
```C++
"....string pi=\"C:\\Shitcode\\s.py\";ofstream u(pi);...."
```
- But secondly, a loop part is `C++` code.
Which was written in some string. It runs a loop for cheking if number is a palindrom. And creates other operation.
- And at the end, a print result part is `python` code.
- It deletes files after their running so a program starts with 1 only line and ends with it.
Have fun!
