# TERM SEARCH
Brings the power of search to your terminal, so that you don't have to leave while coding.  
 
## INSTALLATION  
1. Clone this repo  
2. Cd into the folder  
3. Complile using clang ```clang -o search.exe main.c```
4. Add the folder location to the system path variable 

## USAGE
Now to use this app simply use ```search ``` and type anything you want to search  

## DEMO

https://user-images.githubusercontent.com/95243692/227010848-2e60b12b-37d9-4f90-9fad-b163d6d1e7a3.mp4



## WARNINGS
1. Do not use gcc to complie. It uses strcat_s which is only available in clang. If you want to use gcc try changing it to strcat and removing buffer size. Doing this may increase the chance of buffer overflow.

