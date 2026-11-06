# The FBI (Conclusion)

## OVERVIEW

The FBI search the ground floor of the house, but can't seem to get into the basement.
They realize the door is made of indestructible steel so they assume nobody's behind it.

"All clear", you faintly hear. "Cross this place off the list".

You realize that the keypad must have retracted into the door somehow. 
*That's another mystery I'll solve when I way up* you mumble to yourself.

The granny slowly goes upstairs to make sure her items are still there.
When she comes back down, she sits in the chair next to your bedside table.
"Y'know those FBI people? I blackmailed one of them and made them turn a blind eye on you and I", she calmly says with a subtle smile. "One last thing before you head off to sleep".

She hands you a piece of paper.
It reads:

CTS{safety_is_here_congratulations}

You've completed the HaXOR gauntlet. Congratulations!<br>
<br>
> Points awarded: 15 <br>
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

