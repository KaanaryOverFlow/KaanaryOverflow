[![](https://github.com/MucahitSaratar/MucahitSaratar/blob/master/dinosaur.gif)](#)

# Hi. I'm Mücahit Saratar

```py
bits 64
section .about
  skills:
    dq "security researcher"
    dq "0-day vulnerability hunter"
    dq "exploit developer"
    dq "programmer"
  links:
    dq "https://www.linkedin.com/in/m%C3%BCcahit-saratar-1701bb198/"
    dq "https://www.exploit-db.com/?author=11013"
    dq "https://github.com/MucahitSaratar/researches"
    dq "https://mucahitsaratar.github.io/"
    dq "https://twitter.com/0x00deadbeef"
  about_self:
    db "student"
    db "living in Bursa"
    db "currently learning: pwn,reverse engineering, web development, music production and english"
  contact db 0x03
    discord dq "s/uçan_denizaltı/s-12/g#5154"
    twitter dq links[4]
    email dq "trregen222@gmail.com"
section .text
  global wonder

wonder:
  push about
  push work
  jmp hello_friend ; hello_friend(about)
```
