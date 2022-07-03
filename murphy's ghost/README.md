<div><img align = "right" src = "https://img.shields.io/badge/Points-188%20-informational" height = 22>
<img align = "left" src = "https://img.shields.io/badge/Catagory-WIRELESS-informational" height = 22>
</div
<br>
<div align="center"> <h1> murphy's ghost</h1> <img src = "https://img.shields.io/badge/Solved ✔️%20-brightgreen" height = 30>
</div>

## Description: 
  - Decipher the ciphertext

## Hints:
  - http://practicalcryptography.com/ciphers/polyalphabetic-substitution-category/

### Solution: 

- On the Attachments Section we get 2 .wav audio files namely cipher.wav and key.wav
- While Hearing both I understood that cipher.txt is a morse code encoded in an audio file.
- But the key.wav was a strange audio which was verymuch similar to what we hear on the audio given for [4chan's Favorite](https://github.com/Drupad-DeV/indy-CTF-Writeups/tree/main/4chan's%20Favorite) challenge.
- I decoded the Morse code using an online audio [morse code decoder](https://morsecode.world/international/decoder/audio-decoder-adaptive.html). Resulted in this cypher text ```Q O V W X N G C M N Q E C U I I A T``` .
![image](https://user-images.githubusercontent.com/100958162/177040433-fdcba5fe-3066-4a31-8753-5955f6e3ee05.png)

- I opened the key.wav file on audacity and switched it to spectographic view inorder to get the key ```COOPER```  
![image](https://user-images.githubusercontent.com/100958162/177040453-4ac43ddc-5688-4377-ae46-10f427640986.png)

- The Hints given provided an various no of ciphers and its decoders and encoders.
- When I put the cipher text and keys on diffrent ciphers there flag was obtained from [Beaufort Cipher](http://practicalcryptography.com/ciphers/polyalphabetic-substitution-category/beaufort/)


```
ictf{matthewmcconaughey}
```
