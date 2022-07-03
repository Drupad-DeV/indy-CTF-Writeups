<div><img align = "right" src = "https://img.shields.io/badge/Points-393%20-informational" height = 22>
<img align = "left" src = "https://img.shields.io/badge/Catagory-HARDWARE-informational" height = 22>
</div
<br>
<div align="center"> <h1> Baby_IR</h1> <img src = "https://img.shields.io/badge/Solved ✔️%20-brightgreen" height = 30>
</div>

## Description: 
- An IR Communication was sniffed between two people. The data was a pile of binary digits. Analyze the data sniffed and use them in the circuit and get a "meaning full" flag.

### Solution: 

- The link on the attachment takes us to a [thinkercad simulation](https://www.tinkercad.com/things/5fuy9Yz0UaX) worksapce.
- On the simulation it had an Arduiono Connected with an IR reciever and an 16*2 Display attached to it.
- But while checking on the Arduiono Code I came to know that when specific buttons where pressed on the Remote the flag would be visible on the LCD display.
  
  ![image](https://user-images.githubusercontent.com/100958162/177044136-20793d64-94f8-4ae8-b749-bdf77b91bcb7.png)

- Hence After Checking the Thinkercad remote signal hex codes, I figured out the buttons to be pressed inorder to get the flag.
- While the buttons where pressed in sequencial order the flag was visible on the display
   
  ![image](https://user-images.githubusercontent.com/100958162/177044146-7f099685-17a5-4215-9307-30e970a85949.png)

```
ictf{whrsfla_m4_YfL_f1aGmyg0T}
```
