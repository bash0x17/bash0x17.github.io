---
layout: post
title:  "How to flash a LPC-LINK2"
date:   2021-07-02 13:29:15 +0200
categories: NXP LPC-LINK2


---

In this post you will see how to flash a binary to the "LPC-LINK2". 

Step 1: Install the lpscrypt 

Step 2: To boot from the SPIFI fit the JP1 on the board, see on Fig. 1

![image-center](Bild1.jpeg){: .align-center}{:max-width="320px"}

Step 3: Got to the lpscrypt on a Linux system you will find it in 


```bash
user@linux:~$cd /usr/local/lpscrypt
```
  
Step 4: Flash an example program to the LPC. Here

```bash
user@linux:~$./bin/lpcscrypt program ./images/MCB1800_Blinky_SPIFI.bin spifi
```
