# EZ-CTF 2022 - x_da_ladra

### Quick Intro
Any tool is worthless without the knowledge of how to use it.

So I was the creator behind all Crypto / OSINT / Steg / Misc (The Discord Bot was Raxo).

Now that the competition is over I feel like I should give a brief explanation on some of the challenges and why they were designed this way.

The reality is that I see patterns everywhere, and because of this I make silly connections with disconnected things, and that's a part of my brain that never goes off, and that's fine.

I am only in the beginning of my Cybersecurity journey so while I'm limited by my technical knowledge I can unleash my creativity without any problems :)

In a lot of the challenges I designed I hid clues in plain sight, specially in the name of the challenges. Examples of this are the **More Sense**, **Share a Key**, **Qweauty and the Beast**, **Hue is This**, **Chat  Gram**.

## More Sense

To my surprise a lot of participants were going crazy on why the Bacon Cipher wasn't the solution, in my perspective there are so many codes with 2 symbols, letters that they could still try, made me feel like I had built an Enigma machine out of paper...lol

The reality is that we cannot predict how people will understand our challenges, so this was an awesome learning opportunity for me.

## McFly

So what is going on here? I am a retard...hear me out, I grabbed a photo of the movie character **Biff Tannen** and just patched it with his **ID** in the hopes people would make the connection **Biff** + **ID** = **Bif_id Cipher** ....la la la... I know I know... too much of a stretch there, in my mind this worked...the issue is that most people were super confused and dismissed the image.


## Skyline

I just hid the flag in plain sight in the image, it was just a simple game of hide & seek, but because Steganography is so associated with burying the message in the image code most participants assumed that's where it was. I'm still surprised how well it worked. Only 58 solves for Skyline. This was in reality the easiest of all the Stego challenges.

## The System

Well, this challenge was different for me, because I had to employ a simple psychology trick to try and fool everyone, it had to be easy to crack but at the same time not obvious. 

The psychology trick used is simple: If I give you a task and I tell you it's the hardest task ever then you will assume I am telling you the truth, and therefore the chances that you struggle to complete it are bigger. By giving it a Ninja difficulty I was doing just that.

The second thing I thought was that the message had to be short and that the same letter needed to have more than 1 encoded possibility.

When I found the Music Staff Notation cipher I knew I had struck gold because I saw it could be used with numbers, and most people don't associate musical notes with numbers but the reality is that music is all math.

Now all I had to do was draft a simple message...I looked for words that could fit the english notes (A, B, C, D, E, F, G) and was happy with the final message being **CAGED CAFE BADGE** ...so because **CAGED** is a system used by some guitar teachers I decided to call the challenge **The System**. 

Now the icing on the cake would be the hint...here comes cringe fest movie **The Sound of Music** to the rescue...but because I make silly connections I remembered also **The Hills Have Eyes**. By coincidence, and it was just that, a happy (happy for me) coincidence that confused the participants who rushed to try the **Hill Cipher**

So **"The Hills don't have eyes, but they are alive"** managed to confuse people so much only because they rushed at the 1st keyword they read, not my fault here :)

The next day we published a second hint and in 30 minutes several teams had cracked it. Here I bent the english language to my will and used the double meaning of the word **Notes**, meant to be **Musical Notes**. 

Raxo actually told me to reconsider this hint (because it sounded too vague) but I thought some people would get it...and they did :)

>Morning, due to popular demand here is a hint for "THE SYSTEM" challenge:
>first I would like  to re-inforce the original hint: "The Hills Are Alive..."
>and then the other hint is: I hope you're thinking about taking notes because this is the hint

In the end only 17 people broke this very simple cipher so it's mission was accomplished, a cipher aimed at beginners survived being massively decoded.

I saw a complaint on Discord saying this easy cipher that can be decoded on a website should not be worth 500 points but I have to disagree. In my mind any easy cipher can become unbreakable if you bend it's logic to your own will.

x_da_ladra