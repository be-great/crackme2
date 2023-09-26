# Crackme2: Unmask the Password Adventure

![Crackme2 Logo](crackme2_logo.png)

The chanllage : https://github.com/alx-tools/0x06.c 🏴‍☠️
commands used : cd , ls , cat ,less , apt , vim , strings

# steps :-
1) clone the repository
    ![Alt Text](https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2017-25-38.png)
2) cd to the folder <br>
   $ cd 0x06.c
3) $ ls # to see what you have
   ![ALT Text](https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2017-25-55.png)
4) execute it
    ![ALT Text](https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2017-26-18.png)
   As we see we need to install some package
5) install necessery package
   + Add the resource in the apt resources
      ![ALT Text](https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2018-25-46.png)
      Todo : Add this at the end of the file
     ![ALT Text](https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2017-46-10.png)
   + Update package list
     ![ALT Text](https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2018-36-16.png)
   + Install the nessecury package
      ![ALT Text](https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2018-36-24.png)
6) view what is the normal output
   ![ALT Text](https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2017-56-06.png)
7) see What inside the execute file
   ![ALT Text](https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2017-57-18.png)
   note : we notice some readable texts formats
   ![ALT Text](https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2017-57-1.png)
8) we notice some readable text formats to see it more clear we can you the command "strings"
   ![ALT Text](https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2018-49-48.png)
   note : we notice some hash on it
   ![ALT Text](https://github.com/be-great/crackme2/blob/main/crackme2_images/the_hash)
9) If it's a hash we can brute force it with common password . we can google some website that do that
    ![ALT Text](https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2018-00-00.png)
10) Crack it
    ![ALT Text](https://github.com/be-great/crackme2/blob/main/crackme2_images/crackit)
    

Happy hacking, fearless codebreakers! 🏴‍☠️

*Disclaimer: This repository will not self-destruct. But the secrets you uncover within just might.*
