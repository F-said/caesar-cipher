# caesar-cipher-project

## Table of Contents
1. [Background](#background)
2. [Caesar Cipher](#caesar-cipher)
3. [ASCII](#ascii)
4. [Instructions](#instructions)
5. [Submission](#submission)

## Background
 
Ciphers existed well before computers were formally conceptualized. However, they play a big part in the foundations of computer science. Check out the cracking of the [enigma machine](https://en.wikipedia.org/wiki/Enigma_machine) to find out more. 

The concept of a cipher is quite simple yet powerful. We take a message that we would like to keep secret, apply some transformations to it, and send it to some second party that has the means to decipher it. This way, any third party that intercepts our messages is left clueless as to how to read this message.

An example would be [pig latin](https://en.wikipedia.org/wiki/Pig_Latin). We first take our message: "hello world!", encrypt it using the algorithm below, and send it out to our friend over in the other town via carrier pigeon. 

1. Remove the first letter of each word.
2. Concatenate that letter to the end of each respective word.
2. Add `ay` to the end of each word.

From this, we transform "hello world" into "ellohay orldway." 

Say that our message is intercepted by a malicious third party that lures our carrier pigeon via a delicious bowl of seeds. Without the algorithm we listed above, "ellohay orldway" is simply nonsense jibberish.

## Caesar Cipher

Ciphers were even present in 50 BC when Julius Caesar was fighting the Gauls in the forests of modern-day France. 

To communicate plans with his generals, Caesar sent some poor soul out into the wilderness with nothing but his sandals, sword, and blessings from Jupiter or whichever Pantheon was preferred during that day.

The risk of this courier being caught was high. Therefore, to ensure that any message in Latin was indecipherable to the Gauls, Caesar's armies encrypted their message using a method we know as [Caeser Cipher](https://en.wikipedia.org/wiki/Caesar_cipher).

The algorithm for this cipher is as follows:

1. Select some numeric key value to encode your message. Label this value as `k`.
2. Shift each letter in your message `k` letters forward.
    1. If we go past the last letter in our alphabet (`z`), simply continue counting from the first letter (`a`).
3. You now have an encrypted message!

For example, let's say 

## ASCII

You 

## Instructions



## Submission

