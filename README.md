[![](https://github.com/KaanaryOverFlow/KaanaryOverFlow/blob/master/dinosaur.gif)](#)

# Hi. I'm Kaan Saratar

```py
bits 64
section .about
  skills:
    dq "security researcher"
    dq "0-day vulnerability hunter"
    dq "exploit developer"
    dq "programmer"
  links:
    dq "https://github.com/KaanaryOverFlow/researches"
    dq "https://twitter.com/0x00deadbeef"
    dq "https://medium.com/@Mr.deadbeef.py"

section .text
  global wonder

wonder:
  push about
  push work
  push hello_
  ret ; hello_(about)
```

