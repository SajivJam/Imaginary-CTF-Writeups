# Imaginary-CTF-Writeups

Here is where the secrets to solving Imaginary CTF's challenges are stored!

Take a look around at what I solved!



----------



====round 13====





----------




1. Sanity Check
   
   
   In this challenge, the flag is basically given to us as the start of round 13
   
   ![Screenshot (48)](https://user-images.githubusercontent.com/68140663/129470340-ba786efc-fada-47e6-bc15-e941445186a7.png)
   
   
   If we input the flag into ImaginaryCTF bot, we solve the challenge
   
   ![Screenshot (54)](https://user-images.githubusercontent.com/68140663/129470408-29da3cea-2c11-435f-a17e-29cf1e0ee998.png)
   
----  
   
2. The Muppets


   In this challenge, we are given a .png file called kermit
   
   ![Screenshot (56)](https://user-images.githubusercontent.com/68140663/129470693-a1c536a3-6930-4c57-a02a-053656157426.png)
   
   Click it, Download it, and voila! The image opens up as so:
   
   ![Screenshot (58)](https://user-images.githubusercontent.com/68140663/129488687-17573a09-0471-4c54-8373-9e7f22f2c6c4.png)
   
   Since this is a steganography challenge, I decided to get lazy and use the StegOnline tool: https://stegonline.georgeom.net/upload
   I then uploaded the picture and observed the bit planes. The below is what showed up
   
   ![Screenshot (60)](https://user-images.githubusercontent.com/68140663/129488794-d8b16dd5-37e3-4b9f-bb11-0059356ccf87.png)
   
   Special characters are transcribed in this image. But of what type, we do not know yet. So, with my OSINT skills, I decided to look up anything with "Ding" and "bat",
   as is what is shown in the image. Lucky enough, there are results for something called Dingbat, or sometimes referred to as Wingdings.
   
   ![Screenshot (62)](https://user-images.githubusercontent.com/68140663/129488859-23b1e7da-54d7-456f-a71f-172557ce3f1d.png)
   
   The link, if anyone is curious, is this: https://www.dcode.fr/wingdings-font. If you notice, the characters in the image are a part of this font type! Eureka!
   So, without further ado, I transferred the characters from the image and huzzah! we get the flag!
   
   ![Screenshot (64)](https://user-images.githubusercontent.com/68140663/129488945-ff650f96-2ec5-4900-b2d6-7788599419a5.png)
   
   And if we input that into ImaginaryCTF bot, we successfully solve the challenge!
   
   ![Screenshot (66)](https://user-images.githubusercontent.com/68140663/129488989-53203bb0-4e22-4b9a-b96a-c23d4eee0752.png)

   (Shoutout to StealthyDev and ICTF board)
   
   ----
   
   
   
   




