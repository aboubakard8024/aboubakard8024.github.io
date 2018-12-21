---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of Greece by Abou Diarrassouba

## Describe your program

-   I created the Greece flag and I tried my best to make it scalable.
- I honestly expect a Apprentice and up on this project because I actually tried on this project. I spent days going through multiple errors until I was finally even able to make my first stripe. Then I had to create the second one which was harder than the first for me. Since this project isn't based on completion,I believe I have a shot at getting a decent grade.



## Current output

![MyFlag](/images/FLAGBCB.png)



## Describe your process.

I recieved alot of help from my peers, especially David M. and Emir. When I didn't have my first stripe, David showed me how I could create it and tried to help me with the second stripe. Emir helped me create my second stripe. I've now been trying to create more stripes and the other shapes that are in the Greek flag.




## Explain your code.

-   Explain each argument in the code section. _then delete this instruction_
-   Tell us how it functions independently and within the whole program _then delete this instruction_

* * *

(put-image (rectangle 300 25 "solid" white)
                                280 205

* * *

-   - This code is a put-image code. It placed a white rectangle on the square which created a stripe.
-   This code fits into the whole project because it creates one of the many stripes on the Greek flag.
 

## Program code

```
(put-image (rectangle 600 25 "solid" white)
                                280 48
(put-image (rectangle 300 25 "solid" white)
                                280 205
(put-image (rectangle 600 25 "solid" white)
                                280 103
(put-image (rectangle 300 25 "solid" white)
                                280 155
(put-image (rotate 90(rectangle 180 25 "solid" white))
                                65 205  
(put-image (rectangle 180 25 "solid" white)
                                40 180
(put-image (square 180 "solid" "royalblue")
                                40 220
                                 (put-image (circle 0.11 "solid" white)
                                            77 80 
                                            (rectangle 385 245"solid" "royalblue")))))))))

(define white "whitesmoke" )

```
