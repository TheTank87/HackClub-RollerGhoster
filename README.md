<img width="1280" height="720" alt="rollerghosternew" src="https://github.com/user-attachments/assets/bc16a441-1994-44ef-98bd-08f99fd97aa4" />


# HackClub Project-RollerGhoster

This is week 2 of my mechanical design for Hackclub Halflife. This week I will be building a Merble Marble slide thingy.

# What is it

Roller Ghoster 2000 is my custom marble race made on Onshape. This is my first time dealing with more complex shapes on Onshape so don't expect something from another dimension, but do expect something that works. I made this project for the week2 of the half life event. It is has a base of 100mm x 100mm and is about 80mm tall. The track radius is about 7.5 mm so the standard marble ball should fit.

# Onshape Access
[Link](https://cad.onshape.com/documents/4e46ab6feff5e5184c36e316/w/cd92163df1963c3dffb88ec4/e/4b9af14a7a3ad350c7ffd1de?renderMode=0&uiState=6b075260870c4ef04fad60e1)

# Features

* Support beams
* Tracks
* A finishing marble catcher

# BOM
|Item|Qty|Vendor|Unit Price|Total Cost|Links|
|-----------------|---|------|----------|----------|-----|
|The Roller Ghoster 2000 self printed piece|1|Myself|$0|$0|no link|
|14 mm marbles|1|Amazon|$6.00|$6.00|[Link](https://www.amazon.com/Sukh-100PCS-Glass-Marbles-Collection/dp/B0C8JB1KTP/ref=sr_1_5?crid=33MMXZAZN6WKQ&dib=eyJ2IjoiMSJ9.hIE9iHa4J5iSzYQhLfZGgMwl6YAo3CkTa61ftkoQCY2Ec8oxNLYUIQ9hdQje0PUH74XaJCP5w57HYH1qbRFaD03TznwMikgmnACYjwmjLUNTKF0qzpumVpQ9yHg2ZVsU9ozucGraaS4VBVknQOX9S8AKvwOFrFULjmSGaHmAm6Bp8hqNanjkxmPIecT35PEzddDI2meTQ1491-FxxRXI8W8hqTcuHPVeW9OwKMtPDAGg0wqVvxRRjl2kCjTvTMay6jQQRYJuRUmKbjnV17IFpozA3G3V2TT6dr6fEsAWudA._PuR-9JRHPKGQex_BaN_KIcjuLMwkiPcCKT2olr7pws&dib_tag=se&keywords=14%2Bmm%2Bmarble&qid=1795543577&sprefix=14%2Bmm%2Bmarbl%2Caps%2C177&sr=8-5&th=1)|
|PLA filament|1|myself|$0|$0|no link|
|Print-legion quote|1|$8.75|$8.75|no link|

# The model
This is the first version that I have created, as you can see it doesn't look very complicated, but the steps needed here were crucial. The guide never said anythign about tracks suddenly rotating upside down when sweeping a composite curve, so I devised a method that required multiple track sketches at correct angles and different composite curves so that tracks stay upright. 

<img width="549" height="538" alt="Screenshot 2026-10-19 at 9 16 41 AM" src="https://github.com/user-attachments/assets/b6faec76-68e5-4612-8fb3-3a924f014010" />

I started by learning how to sweep sketches I made and then learned to how to angle them. Turns out, angling planes were crucial to building correct oriented runways, because sometimes sweeping a whole composite curve will result in 180 degrees rotation. This was undesirable for open topped runways. So I had to meticulously angle and construct planes that I can then use to create sketch lines to sweep my runway sketch over. 

## Finished version

However, during project review, I realized that my original design did not take prices or practicality in mind. It turns out that I didn't use good practices of using hollow structures and a thin base to save on filament, so I had to redesign the whole thing. I created a new design which had a base that was 200mm by 200mm and was about 2 mm thick. Instead of using composite curves, I decided to use slanted runways and implemented a new feature. Extrude removed pieces that created smooth entry ways for the marble to go through. I also designed the new tracks to have a radius of 7.5 mm so that marbles would fit. This time too, I used hollow cylinders as the support beams to reduce filament requirements. I also added a ramp and curved walls to guide the ball through the bottom.


<img width="997" height="573" alt="Screenshot 2026-11-25 at 12 49 36 PM" src="https://github.com/user-attachments/assets/32ed0a5c-1783-4fbb-ad6b-328cce2660ad" />


