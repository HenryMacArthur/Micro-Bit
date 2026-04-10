# Micro-Bit
This is a web-based Micro:Bit code editor I made for my little brother because his school blocked the normal one and signing in every time from a guest account was getting tiring. You can run the index.html, or go to the website at https://micro-bit--henryemacarthur.replit.app. I have not yet had the chance to actually test it on a Micro:Bit, so I have no idea if it works, but Google Gemini says it will.

# Problems

* Editing the block code changes the python code, but editing the python code doesn't change the block code. 
* This currently uses WebUSB to put the code on the Micro:Bit. This will work on most Chromium browsers, but not Safari, Firefox, or anything on iOS (because its Apple). Also, you can't put it in Iframes.
* You can't yet add to existing hex files, only write and overwrite them. Support for this will be added later, though.

# Usage

Download it, then open the HTML file, or go to https://micro-bit--henryemacarthur.replit.app. It is very similar to the normal Micro:Bit editor and Scratch, and even if you're not familiar with those, it's still pretty self-explanatory.