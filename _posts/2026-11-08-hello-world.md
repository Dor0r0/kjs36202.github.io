---
title: 블로그를 시작합니다
date: 2026-11-08 18:00:00 +0900
categories: [Blog, Notice]
tags: [blog, jekyll, chirpy]
---

GitHub Pages + Jekyll Chirpy 테마로 블로그를 열었습니다.

## 앞으로 올릴 것

- CTF write-up (Crypto / Pwn / Rev / Web / Misc)
- 보안·개발 공부 기록

## 코드 하이라이팅 테스트

```python
from pwn import *

p = remote("localhost", 1337)
p.sendline(b"A" * 0x28 + p64(0xdeadbeef))
p.interactive()
```

> 수식도 됩니다: front matter에 `math: true`를 넣으면 $$ a^{e} \equiv c \pmod n $$
{: .prompt-tip }
