# PassX

* A simple program in C which tells password complexity, time to brute force it and strength of the password entered by the user.<br>

* Compile : <br>
  Windows : gcc PassX.c -o passx<br>
 
 *  ![For Windows](PassXWin.png)  

* Compile : <br>
  Linux : gcc PassX.c -o passx -lm <br>
  
*   ![For Linux](PassXLin.png)<br>

* Wordlist :<br>
I have used list of 100 common passwords from SecLists. You can use any wordlist for bruteforcing.<br>
Note : Larger the wordlist file more time it will take to bruteforce a password.
