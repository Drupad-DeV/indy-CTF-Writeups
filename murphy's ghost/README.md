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
- I decoded the Morse code using an online audio [morse code decoder](https://morsecode.world/international/decoder/audio-decoder-adaptive.html). Resulted in this cypher text ```Q O V W X N G C M N Q E C U I I A T```.
- I opened the key.wav file on audacity and switched it to spectographic view inorder to get the key ```COOPER``` . 
  <img src = "https://traboda-arena-36.s3.amazonaws.com/files/attachments/uartdata_d97139a4-73fd-459f-8f53-d839d0bb0aa2.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA6GUFVMV6HO3NYL6Z%2F20220630%2Fap-south-1%2Fs3%2Faws4_request&X-Amz-Date=20220630T151227Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=1ff845dd2cf7e20062c0ea5a0a1a9c8513c1eef287cf5e7d099bdd70eb310039">
- The Hints given provided an various no of ciphers and its decoders and encoders.
- When I put the cipher text and keys on diffrent ciphers there flag was obtained from [Beaufort Cipher](http://practicalcryptography.com/ciphers/polyalphabetic-substitution-category/beaufort/)

```
ictf{matthewmcconaughey}
```
