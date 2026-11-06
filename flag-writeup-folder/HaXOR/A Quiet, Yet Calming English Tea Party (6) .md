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
<code>CTS{1, 3, 4, 8}</code>
</details>

## INTENDED SOLUTION

<details>
<summary>
The solution is:
</summary>
The two tea trays are meant to be sets. Set one has items {5, 8, 3} and set two has items {6, 4, 1}<br>
When the old lady/grandma gives you a macaron to eat, you're supposed to turn the 6 macarons in set 2 into 5.<br>
This is when you are ready to XOR. XORing sets meaning any time you see something in set 1 and the same thing in set 2, you cancel them both out because the XOR logic gate says an input of 1 on both inputs gives you an output of 0. <br>
Combine any values that survived the XOR to complete XORing sets and make sure to put them in ascending order per the instructions. <br>
</details>

## PERSONAL THOUGHTS

<details>
<summary>
My personal thoughts on this flag:
</summary>
  <br>
As I'm making this writeup, I'm starting to realize I used both old lady and grandma interchangeably. Oh well. <br>
<br>
I searched up what else you can XOR and when I saw sets pop up, I thought about how cool would it be to make a challenge around that. Since I'm also a MasterChef Canada and Dessert Masters fan, I was thinking about the tea trays presented in S2 of MasterChef Canada and Anna Polyviou's High Tea Tray she made in S1. I also made sure that the tea trays in the challenge sounded appetizing and also I gave them very nice descriptions because I just love my descriptions.<br>
  <br>
Also, I made the keypad 5 attempts because I was thinking about intruders guessing passwords. <br>
  <br>
Difficulty (out of 100): 3 <br>
Reason: XORing sets is not that hard.
</details>

