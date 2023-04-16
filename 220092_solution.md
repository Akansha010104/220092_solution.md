# Details

Rename this file in the format `yourRollNumber_solution.md` (example, `220000_solution.md`) and submit the solution in the Google form link provided 
*** https://forms.gle/RZtKpFcKfrWrYYxF9 ***


## Your zeroth approach below

REASONING :

On running the zeroth.c,I  got the error that int array cannot initialized with string .So, I included string library to be able to use string keyword. Since argc is argument count so changed its datatype into int and argv is argument vector i.e from pointer to pointr of char so I used ** and changed ved's from int to char .


RESULT:
"The answer of this challenge is output of "man" when run on terminal, copy the exact output"

What manual page do you want?
For example, try 'man man'.
```

---
## Your first approach below (first.txt):

REASONING :


 - With the help of the directions for first.txt I came to know that the characters are supposed to be rotated ,so i just used an online decoder/encoder namely
 https://www.dcode.fr/rot-cipher which helps me to get a meaningful or readable sentence .

```
RESULT:
"noicee you did crack a rotation encryption on your own. The following is a clue for the next puzzle: CLASS of that INPUT"
```



## Your second approach below (strings.txt)

REASONING- 

I found the file name "string.txt" at location A by using "find" command .
At Location A: "./Lamp_Stack_task/question_mark/Lamp_Stack/1/5/0/3/strings.txt "
then in string.txt there is text that looks like this using "cat" i got the content in the file string.txt
              cat strings.txt
              kw4QLNylm2inErX
              DabAWF1UenBD2W
              kPVEQPc6ZN8x2jn
              g4JoMqFZyat9vd5
              ORNwuwGtKDLydge
              TqMuGims7vlJtno
              8dc2evcCSSc4kUy (password)

-  using  bash I opened the strings.txt file individually and retrieved all files in ""Lamp_Stack_task/question_mark/Lamp_Stack"" this 
   folder using "grep"  command 

grep -r "8dc2evcCSSc4kUy"
Lamp_Stack_task/question_mark/Lamp_Stack/1/5/0/3/strings.txt:8dc2evcCSSc4kUy (password)
Lamp_Stack_task/question_mark/Lamp_Stack/eleven.txt:8dc2evcCSSc4kUy
Lamp_Stack_task/question_mark/Lamp_Stack/final.txt:8dc2evcCSSc4kUy
Binary file Lamp_Stack_Task.zip matches

GOt two passwords namely : {eleven.txt,final.txt}



## Your third approach below (fourth.zip)


REASONING :

-  The password from the previous task is found to be "eleven.txt" . After extracting fourth.zip using unzip :
          ***unzip fourth.zip
        Archive:  fourth.zip
        [fourth.zip] get_in/2/4_inner/5.txt password:

- then we get folder namely ""get_in"" again using grep command i got this:
       grep -r "DevOps"
       4/2_inner/0.txt:DevOps{y0ur3_4w350m3_4nd_0ne_5t3p_c1053r}



* RESULT:
  
  DevOps{y0ur3_4w350m3_4nd_0ne_5t3p_c1053r}





---


- Name :Akansha
- Roll :220092
- GitHub username: Akansha010104
- Discord username: Akansha Singh#9007



## Do not tamper below this line

---

Q29yZSB0ZWFtIGtvIGZha2UgZG8=
