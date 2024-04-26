# Cats At The Beach

Hello!

This is Team Banannana's writeup (we are all sec 3's with this being our first ctf/writeup so please dont grill us too hard or zenneth will cry)

---

The challenge 

> I lost my grey cat when we were overseas.
> 
> This is the last picture I found of it, but I have no idea where it is. Can you help me identify this beach?
> 
> The flag format is grey{name_of_beach_in_lower_case}.
> 
> There is no word "beach" in the flag.
> 

and this image was attached

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/beach.jpg?raw=true)

---
How to go about solving it

Well since the question hints to the Flag being a name of a beach and the social engineer in the #misc channel in discord managed to get the admins to reviel that the beach was in vietname, We had strong hints about where it was.
![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240426-nmuq.png?raw=true)

(the hint has been retracted by the admins as seen by timestamps(also we solved this before the hint))

With these hints, it is still quite hard to find where the beach is, Hence, we reverse image searched it using Google

it initially got stuck at the handsome man in the image 
![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240426-nnxs.jpeg?raw=true)

so we manually distracted it to put its focus back into the beach and to narrow it down even further, we selected only the mountains in the background

![](https://github.com/saumilthecode/A-writeup-of-sorts-greycattheflag/blob/main/Images/SCR-20240426-noad.jpeg?raw=true)

With this, we had a tremendus clue that the beach was called My Khe Beach!!!

However, when we put it into the challenge website, it deemed that we were wrong. So we decided to dig deeper into my khe beach