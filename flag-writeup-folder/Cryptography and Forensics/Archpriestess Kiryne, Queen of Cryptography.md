# Archpriestess Kiryne, Queen of Cryptography

## OVERVIEW

I was facetiming a friend recently and saw this message on the wall of his room. I quickly took a blurry screenshot and managed to salvage all of the characters.

9EEADi^^A2DE63:?]4@>^zJ_!}q3g

Flag is in the form of CTS{answer}

> Points Awarded: 60<br>
> <details><summary>Hint 1 (Cost: 10) </summary>Rotate me right 'round baby right 'round Rotate me the same number of times as there have been presidencies in the US.</details><br>
> <details><summary>Hint 2 (Cost: 20) </summary>The diagonals wrap around, always left to right.</details>

## THE FLAG

Spoilers below!

<details>
<summary>The flag is:</summary>
<code>CTS{cryptographyinsanity}</code>
</details>

## INTENDED SOLUTION

<details>
<summary>
The solution is:
</summary>
Do a ROT47 cipher on the given message. 
You get: pastebin Ky0PNBb8
Take the first letter of the first word, second letter of the second word etc. When you are trying to find the 10th letter, you take the 1st letter of the 10th word.
pelcgbtenculvafnavgl is the answer after step 2.
You are then supposed to realize brain (ROT) and friday the (13)th to make ROT13.
ROT13 on pelcgbtenculvafnavgl is cryptographyinsanity
</details>

## PERSONAL THOUGHTS

<details>
<summary>
My personal thoughts on this flag:
</summary>
<br>
This was my second flag ever made. I told the other people that if nobody made a harder flag, I might change this to be Vytelus, King of Cryptography. But then I realized that, I think this name has a better ring to it so the name is still Archpriestess Kiryne, Queen of Cryptography

I had a lot of fun in thinking about how to encrypt something. i remember hearing Ted-Ed's sorting hat riddle and how the answer required you to line up the names of the people and the "house" they belonged to and then read out the diagonal to form "minotaur". I also remember how in roblox, some games made you go to a pastebin to get a code or your next step so I took inspiration from that. This challenge was only supposed to have 2 ciphers with the diagonals spelling the answer but then I decided to make a final twist to make it even better.

I will admit some of the hint values were too low but also they didn't reveal a whole lot besides the first one telling you ROT from rotate and presidencies in the US (47).

Oh I also forgot to mention, the name was taken from the first boss in a game called Dungeon Quest Reborn, specifically the Gilded Skies dungeon (the hardest dungeon at the time).

Difficulty (out of 100): 40 <br>
Reason: Triple cipher, but not too hard. If I had used a crazier cipher the difficulty would be a lot higher.

