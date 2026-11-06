# A Quiet, Yet Calming English Tea Party

## OVERVIEW

You see an old lady, sipping tea.<br>
There's a blue table set up, with a teacup ready for you.<br>
​<br>
"Come sit down", she softly says. "Have a sweet."<br>
You see two tea trays, both with 3 layers.<br>
Tray one has:<br>
* five smoked salmon sandwiches, with the crusts cut off.<br>
* eight chocolate scones, packed to the brim with chocolate.<br>
* three slices of lemon cakes, with a nice sweet meringue to top it off.<br>
​<br>
Tray two has:<br>
* a box of six macarons, baked to perfection, each a different flavor.<br>
* four crumpets, with strawberry jam on the side.<br>
* and one pack of skittles, just in case you don't fancy tea trays.<br>
​<br>
"Have a vanilla macaron" she joyously says.<br>
​<br>
You eat the mint & vanilla macaron and feel refreshed, but also very sleepy from the countless days you've outran the police getting to this home.<br>
​<br>
"The bedroom's over there" she whispers. "Good night. I'll make sure the cops don't come looking for you."<br>
​<br>
"Thank you", you say. "But the door's locked".<br>
You look at the keypad and it says 5 attempts. Now you've realized why she offered you the macaron.<br>
​<br>
Flag is in the format: CTS{num1, num2, num3, etc.}<br>
Ex. CTS{1, 2, 3}<br>

> Points awarded: 20 <br>
> Prerequisite: Completion of "A Colorful House" (Part 5 of 7) <br>
> Participants only get 5 attempts at solving, otherwise they cannot see part 7 of 7.

## THE FLAG

Spoilers below!

<details>
<summary>The flag is:</summary>
<code>CTS{653846432424672560908}</code>
</details>

## INTENDED SOLUTION

<details>
<summary>
The solution is:
</summary>
XOR "aloha" and "freedom" to get 28835809281640204.<br>
Take each of the colors (#6C9E8B), (#693E0F), and (#375FC4) and turn them into R G B values.<br>
(108, 158, 139) & (105, 62, 15) & (55, 95, 196) <br>
Now, multiply all 9 numbers together to get 237197581430040000 <br>
XOR the aloha/freedom number and this RGB number to get the flag number.
</details>

## PERSONAL THOUGHTS

<details>
<summary>
My personal thoughts on this flag:
</summary>
  <br>
  Text goes here.
<br>
Difficulty (out of 100): 60 <br>
Reason: The aloha and freedom XOR was a bit obscure, but the meat and potatoes of the difficulty comes from people who did not use hints to try to solve this. I think it's possible for some people to think of getting the RGB values but the hardest part is what to do with them. Not many people would think to just multiply all 9 of them. i can think of situations where people would only multiply or even add the Rs Gs and Bs before multiplying them all together and then just not getting it right. There are so many ways to get a wrong answer. I even told the answer to another person making challenges alongside me, Alyssa. After I told her the answer, she says and quote "I'd be shocked if anyone gets that".
</details>

