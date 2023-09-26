# Crackme2: Unmask the Password Adventure 🕵️‍♂️🔓

The challenge: [Crackme2 Repository](https://github.com/alx-tools/0x06.c) 🏴‍☠️

Commands used: `cd`, `ls`, `cat`, `less`, `apt`, `vim`, `strings`

## Steps:

**1. Clone the repository**

      $ git clone https://github.com/alx-tools/0x06.c.git

<img src="https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2017-25-38.png" alt="Clone Repository" width="800" height="200">

**2. Change to the folder**

      $ cd 0x06.c


**3. List the contents of the folder**

<img src="https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2017-25-55.png" alt="List Contents" width="800" height="200">

**4. Execute the program**

<img src="https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2017-26-18.png" alt="Execute Program" width="800" height="200">

As we can see, we need to install some packages.

**5. Install necessary packages** 📦

- Add the resource to the apt sources
      $ vim /etc/apt/sources.list


  <img src="https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2018-25-46.png" alt="Add Resource" width="800" height="200">

  **Todo:** Add this at the end of the file. 📝
  
      `deb http://security.ubuntu.com/ubuntu xenial-security main`
  <img src="https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2017-46-10.png" alt="Todo" width="800" height="200">

- Update the package list 🔄

      $ sudo  apt update
  <img src="https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2018-36-16.png" alt="Update Package List" width="800" height="200">

- Install the necessary package ⚙️

      $ sudo apt install libssl1.0.0
  <img src="https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2018-36-24.png" alt="Install Package" width="800" height="200">

**6. View the normal output** 👀

<img src="https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2017-56-06.png" alt="View Output" width="800" height="200">

**7. Inspect the contents of the executable file**

      $ cat crackme2 | less
<img src="https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2017-57-18.png" alt="Inspect Executable" width="800" height="200">

**Note:** We notice some readable text formats.

<img src="https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2017-57-1.png" alt="Note" width="800" height="200">

**8. We notice some readable text formats. To see it more clearly, we can use the `strings` command.**

      $ strings
<img src="https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2018-49-48.png" alt="Strings Command" width="800" height="200">

**Note:** We notice some hash values.

<img src="https://github.com/be-great/crackme2/blob/main/crackme2_images/the_hash" alt="Hash Values" width="800" height="200">

**9. If it's a hash, we can attempt to brute-force it with common passwords. You can find websites that offer this service.**
<img src="https://github.com/be-great/crackme2/blob/main/crackme2_images/Screenshot%20from%202023-09-26%2017-59-03.png" alt="Hash Values" width="1300" height="600">

**10. Crack it**
<img src="https://github.com/be-great/crackme2/blob/main/crackme2_images/crackit" alt="Hash Values" width="1300" height="600">
