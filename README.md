# Video Encryption & Decryption

In this Project , I use AES algorithm to encrypt and decrypt the video file. <br>
I have created application on python language and front-end layout is based on python gui toolkit tkinter. <br>
The AES (Advanced Encryption Standard) algorithm is a symmetrical block cipher algorithm that takes plain text in blocks of 128 bits and converts them to ciphertext using keys of 128, 192, and 256 bits. <br>

# Install Pycrypto Module

The installation command for this module is:<br>
<b>pip install pycrypto<b>
<br><br>
  
# Steps For ENCRYPTION

<ol><li>Python accepts the file input and encrypts it using the Pycrypto module.</li>
  <li>The filename is taken as input parameter along with the password.</li>
<li>Encryption is achieved with the help of key which is generated with SHA-256 algorithmic standards. The encrypted file is saved in the same directory with a prefix of encrypted added to it.</li>
<li>SHA-256 cryptographic hash function generates keys which helps in maintaining security of files that are used for symmetric encryption of files.</li>
</ol>
<br><br>
<ul><li>The files are basically protected with passwords.</li>
<li>Decryption follows the reverse procedure where the password and encrypted file is taken input parameters.</li>
</ul>
 <br><br>

# System View

![image](https://user-images.githubusercontent.com/58871655/117016839-b6a0b700-ad10-11eb-92d7-debab972a288.png)
![image](https://user-images.githubusercontent.com/58871655/117016881-c3bda600-ad10-11eb-84ec-f13228abaf54.png)
![image](https://user-images.githubusercontent.com/58871655/117016905-ccae7780-ad10-11eb-9096-1d2002fb6df0.png)
