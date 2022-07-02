<div><img align = "right" src = "https://img.shields.io/badge/Points-75%20-informational" height = 22>
<img align = "left" src = "https://img.shields.io/badge/Catagory-REVERSING-informational" height = 22>
</div
<br>
<div align="center"> <h1> Baby_rev</h1> <img src = "https://img.shields.io/badge/Solved ✔️%20-brightgreen" height = 30>
</div>

## Description: 
- Here is a firmware dump. Can you find the flag?

### Solution: 

- On the Attachments Section we get a frimware dump file ```fw-4M_6a5c486d-635d-4767-8977-3bcdaafaad73.bin```
- While doings strings command I could see many suspecious patterns in which any one of theem could be the flag.
- So i used grep along with the strings using 'or operator' ```|``` 
- Which Returned the flag.
  ![image](https://user-images.githubusercontent.com/100958162/177008665-ab6ecd1d-bb89-4a72-a44d-561099e5da18.png)

```
ictf{b30cb82af09abeba892a4242ccfb854977e}
```
