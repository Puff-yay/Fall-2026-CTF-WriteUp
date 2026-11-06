# A Colorful House

## OVERVIEW

Your home free at last. You approach a colorful home. There's a key under the doormat.<br>
"aloha" is written on one side, "freedom" is on the other.<br>
<br>
You think nothing of it and open the door. With freedom comes... a wealth of knowledge.<br>
You see colors perfectly and can even name the hexcodes just by looking at them.<br>
The ceiling is sage green (#6C9E8B)<br>
The wood floors are a nice dark brown (#693E0F)<br>
And the furniture is an interesting royal blue (#375FC4).<br>
You also notice it's definitely not just wood seperating you and the floor.<br>
<br>
But then, you approach the basement door with a keypad.<br>
What's the code to the door?<br>
<br>
Expand beyond the normal world, the code is not 4 digits.<br>

> Points awarded: 75 <br>
> Prerequisite: Completion of "A Magical Prison" (Part 4 of 7)<br>
> <details><summary>Hint 1: The True Key (Cost: 15) </summary>"aloha" and "freedom"... and the category is all about XOR. Maybe give it a try?</details>
> <details><summary>Hint 2: Colorful (Cost: 35) </summary>You were given perfect color vision for a reason. Maybe find the RGBs?</details>
> <details><summary>Hint 3: The Keypad (Cost: 20) </summary>A common yet overlooked math operator, something you learned a while ago. Once you're down to two, it's go time.</details>

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
This was the hardest challenge in the HaXOR series by a mile. The hints were very much needed in order to do this challenge without losing your sanity. This was my attempt at making a challenge with the most craziest things I could think of, without holding back.<br>
<br>
Also, if you've read all of the other Personal Thoughts, this is the first challenge that came with a story! I started this story by thinking of a prisoner who would go on the run after escaping prison. I imagined the prisoner running through the thick fog and finding a nice cozy wood house in the distance. I also got inspiration from that one riddle that tells you a one-story house is colored all purple (it could be any color) and the question was "What color are the stairs?" (If you don't know, the answer to that riddle is there are no stairs). I was also thinking about how cool would it be if it had a metal basement door, sort of like a panic room. I also thought back to movies where they put the key in a pot or somewhere near the front door (such as under a doormat) for people who forget their keys or for people to give their keys to their forgetful grandparents. The word "aloha" was me thinking about how it would be cool for a prisoner to flee to nice hawaii to hide out while the word "freedom" was thinking about how a prisoner would want to say "freedom!" after escaping prison. <br>
<br>
When it came time to actually making the challenge, i was still thinking about hexcodes and hexvalues but was thinking about what they are used for. That led me to think of colors! I used a random hexcolor generator to make the colors (hence why I gave you all perfect color vision) and since I'm terrible with colors, I asked AI to tell me what colors they are in English terms (sorry!) I was initially thinking of only having one color but when I did 108 * 158 * 139, I realized the number was too small, hence the other 2 colors to make the multiplied number bigger. <br>
<br>
Difficulty (out of 100): 60 <br>
Reason: The aloha and freedom XOR was a bit obscure, but the meat and potatoes of the difficulty comes from people who did not use hints to try to solve this. I think it's possible for some people to think of getting the RGB values but the hardest part is what to do with them. Not many people would think to just multiply all 9 of them. i can think of situations where people would only multiply or even add the Rs Gs and Bs before multiplying them all together and then just not getting it right. There are so many ways to get a wrong answer. I even told the answer to another person making challenges alongside me, Alyssa. After I told her the answer, she says and quote "I'd be shocked if anyone gets that".
</details>
