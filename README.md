# Ransomware-Riddles
Homework 10

In this homework assignment, you will play the role of a cybersecurity analyst at Nakatomi Hospital.

Unfortunately, one of the hospital's doctors opened up an email containing ransomware.

This ransomware spread throughout the hospital and encrypted all of the Patient Records.

The ransomware has given you two options to decrypt and retrieve the patient records: Either pay 100 bitcoins or solve six riddles.

Since you refuse to pay off any ransom, you'll have to solve six cryptographic riddles. Act fast: the doctors need to access the patient records as lives are at stake!

Additionally, a Career Service Milestone is located at the end of this file. Complete it to learn how to become more Employer Ready.

Topics Covered in Your Assignments

Encryption Decryption Caesar Cipher Encoding and Decoding Binary Symmetric and Asymmetric Encryption Open SSL Key/IV Public/Private Keys Key Distribution Hashing Hashing Algorithms Hashcat Steganography Steghide

Files Required

The entire homework assignment can be completed on a publicly available website linked below. If for any reason, the website has issues or is unavailable, an offline copy has also been provided.

Website: https://sites.google.com/view/cryptobreakout/

Offline Copy: Crypto_Homework

Instructions:

In order to solve each riddle, you will need to apply cryptographic concepts covered in the past three lessons. concepts will need to be applied. Once the riddle has been solved, submit your answer on the bottom of each Riddle Page. If you are correct, you will receive a key. Save this key in your notes. Once you have collected all six keys, select the Ransomware Decrypted header on the website and enter all your keys. If all the six keys are correct, the ransomware will be removed and the data will be decrypted.

You will need to submit a screenshot as proof that the ransom Good luck and act fast as the Nakatomi Patients are counting on you!

Riddle 1:


I used Caesar Cipher Decoder with a shift value of 8 to the ciphertext (ozcjmz). After processed, the result was  (gruber). Once I deciphered the message, my key for Riddle 1 is (6skd8s).

![image](https://github.com/user-attachments/assets/b68ee74b-6762-4360-967b-23c0d8ef5a63)


Riddle 2:


For Riddle 2, I used binary decoding. The input I had was (01000111 01100101 01101110 01101110 01100101 01110010 01101111), which produced the output (Gennero). After obtaining my answer, I solved the riddle and received the key (cy8snd2).

![image](https://github.com/user-attachments/assets/b89880d1-cef0-4dcc-8156-143ba73a9f30)

![image](https://github.com/user-attachments/assets/4bffc191-7229-40a1-9303-71d9e9f99fce)


Riddle 3:

My third riddle was a bit tricky, I used my Ubuntu machine running Linux and executed the following command:

echo "4qMOIvwEGXzvkMvRE2bNbg==" | openssl enc -pbkdf2 -nosalt -aes-256-cbc -out out.txt -d -base64 -K 5284A3B154D99487D9D8D8508461A478C7BEB67081A64AD9A15147906E8E8564 -iv 1907C5E255F7FC9A6B47B0E789847AED
After deciphering 4qMOIvwEGXzvkMvRE2bNbg==, I found the answer to my riddle (Takagi). Once I answered the riddle, I received my key (ud6s98n).

![image](https://github.com/user-attachments/assets/c4fec98d-7bf4-49f6-ab00-65b29d41bc53)

![image](https://github.com/user-attachments/assets/8f1abd58-d2db-4ce4-9ad7-99ce1c393b27)


Riddle 4:

Jack and Jill went up a Hill to 
use their public Keys.

Jack had 2, and Jill did too
to exchange their messages
with ease.

What would Jack use to send 
an encrypted message to Jill?

Jill's public key, Jill's private key, 12 Asymmetric and 15 Symmetric, Alice's public key, My key is (7gsn3nd2)

![image](https://github.com/user-attachments/assets/20a3f503-5df8-413b-bcf7-a412c324dd01)

Riddle 5:

My riddle five was a bit challenging to solve. I utilized my Ubuntu machine and ran the following commands: echo 3b75cdd826a16f5bba0076690f644dc7 > riddle5.txt hashcat -m 0 -a 0 -o solved1.txt riddle5.txt /usr/share/wordlists/rockyou.txt --force. The hash I needed to solve was 3b75cdd826a16f5bba0076690f644dc7. After deciphering it, I found the answer to be "argyle." Once I solved riddle five, I obtained my key: (ajy39d2).

![image](https://github.com/user-attachments/assets/a18a5c90-1712-4087-8c4a-4cae13cc69c9)

![image](https://github.com/user-attachments/assets/f5404318-5cd2-4201-b5d0-84a8e92c5e0e)

Riddle 6:

My riddle six was a bit tricky, but I also used my Ubuntu machine running Linux. I used the command: steghide extract -sf mary-lamb.jpg with the password: ABC. After I executed the command, I retrieved the answer to riddle six (Mcclane). I then answered my final riddle and received the key (7skahd6).

![image](https://github.com/user-attachments/assets/004e7dfb-9124-44e4-8cac-9b3e483e4795)


Ransomware Decrypted:

After I solved all six cryptographic riddles, I returned to the Decrypted header on the website and entered all six keys into the ransomware decrypted.

![image](https://github.com/user-attachments/assets/b78a2283-7766-453c-b00c-a5fc0c74d159)








