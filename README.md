# RailFenceCipher
Group Assignment of Course Cryptography to build Rail Fence Cipher algorithm with Python.
## Features
- [x] Encryption
- [x] Decryption
- [x] Define the depth
- [x] Define the repetition
- [x] Space sensitive
- [X] Case insensitive
- [x] Autorun tests 1 and 2 in the assignment
## Installation
1. Run the Python file directly  
The program is written in Python, make sure you have python3 installed on your computer. If not, you can follow the instructions here:https://realpython.com/installing-python/
2. Run from docker file  
Make sure you have docker installed on your computer. If not, you can follow the instructions here:https://docs.docker.com/engine/install/
## Usage
1. **Python file**  
- Open your command line tool  
  
  For Encryption
  ```
  sudo Python3 /.../railFenceDecryption-python3.py
  ``` 
  For Decryption
  ```
  sudo Python3 /.../railFenceEncryption-python3.py
  ```
  <img width="686" alt="image" src="https://github.com/arcadylee/RailFenceCipher/assets/80624027/6d39dc55-7347-495c-955e-250dcefb9166">
  
- Choose the function  
   <img width="280" alt="image" src="https://github.com/arcadylee/RailFenceCipher/assets/80624027/22856114-37ce-41dc-894d-a1a736d1db1d">

  1.Enter the Input yourself  
  You can enter any text you want to encrypt and choose the number of depth and repetition you want. The program will give you the Cipher text.  
  For example, enter "HELLO WORLD" as input and choose both depth and repetition with 2.  
  For Encryption, The Cipher text is "hore llwdlo"  
  <img width="325" alt="image" src="https://github.com/arcadylee/RailFenceCipher/assets/80624027/6141f4fb-3472-4444-8c2a-2683a2a514d7">  
  For Decryption, The Plain text is "hello world"  
  <img width="322" alt="image" src="https://github.com/arcadylee/RailFenceCipher/assets/80624027/ba6ad96a-49c0-48a9-a326-611898799105">
  
  2.Run the test directly  
  For Test1 Encryption, the program gives you the result of ciphertext.
  <img width="566" alt="image" src="https://github.com/arcadylee/RailFenceCipher/assets/80624027/1596552e-843e-4cd9-8266-673fb4112007">  
  For Test2 Decryption, the program gives you the result of plaintext.
  <img width="570" alt="image" src="https://github.com/arcadylee/RailFenceCipher/assets/80624027/038fd162-6d25-4b2d-9787-c5b086abdab4">  

  3.Exit
  The program exit.  
  <img width="224" alt="image" src="https://github.com/arcadylee/RailFenceCipher/assets/80624027/fe735c7e-b9ac-41a7-b632-6f9f158b368d">   
2. **Docker file**  
- Build Docker image with docker file  
  ```
  sudo docker build -t dockerimagename -f dockerfilename .
- Run Docker image
  ```
  sudo docker run dockerimagename  
- Use the fuction
  the same as with Python file in above.
  ## Build With
  Python3  
  Docker  
