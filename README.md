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
    dq [linkedin](https://www.linkedin.com/in/m%C3%BCcahit-saratar-1701bb198/)
    dq [exploitdb](https://www.exploit-db.com/?author=11013)
    dq [researches](https://github.com/MucahitSaratar/researches)
    dq [my web page](https://mucahitsaratar.github.io/)
    dq [twitter](https://twitter.com/0x00deadbeef)
    dq [medium](https://medium.com/@Mr.deadbeef.py)
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
  push hello_friend
  ret ; hello_friend(about)
```

