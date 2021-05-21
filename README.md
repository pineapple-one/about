# Pineapple ONE

![Pineapple ONE logo](./img/Ananas.png "Pineapple ONE logo")

---
## Introduction

Pineapple ONE is a 32 bit RISC-V CPU made only out of basic logic components and 
memories - no FPGAs or any microcontrollers used. 

Nowadays more and more people are building homemade computers using just basic logic componens. For example:

- [Ben Eater's CPU](https://eater.net/8bit)
- [James Sharman's pipelined CPU](https://www.youtube.com/watch?v=3iHag4k4yEg&list=PLFhc0MFC8MiCDOh3cGFji3qQfXziB9yOw)
- [James Bates's CPU](https://www.youtube.com/watch?v=gqYFT6iecHw&list=PL_i7PfWMNYobSPpg1_voiDe6qBcjvuVui)
- [Paula Maddox's CPU](https://www.youtube.com/watch?v=FRCaurFMvjU&list=PLqTn11YkMSMxu0p4yKBcYW34_R2fK80yI)
- [Filip Szkandera's CPU](https://twitter.com/ten_filip/status/1340400266047332354?s=20)

... and more.

Those are typically 8-bit CPUs and though we absolutely love them, the 8-bit architecture has some limitations - I should know, I built one myself. For example connecting some kind of I/O can be a problem, like keyboard or an external monitor. The much needed CPU resources are just not there (this is just an general point of view, there are surely many people that overcame this). 

I wanted to make something open source, and push the boundries of homemade CPUs a little further. I was inspired by [Robert Baruch's 32-bit RISC-V CPU](https://www.youtube.com/watch?v=yLs_NRwu1Y4&list=PLEeZWGE3PwbansoxKjjMKHQqS_2cm8i60) he was making at that time and I wanted to make something similar. 

So I have spent last two years designing and building a 32 bit CPU RISC-V CPU as well, and I am proud to announce that I have built one - sort of. It runs on 500 kHz, it has 4 I/O ports, 200x150 px VGA output and you can even connect a PS/2 keyboard using one of the I/O ports. I wrote some example programs - demo video [here](https://youtu.be/NUAVKNVrPh0) and it works fine, but more complex programs are not 100% reliable - now.

My goal is to improve upon what I have already done and make it accesible for everyone interested in builing their own "Pineapple ONE" (* name could be changed due to legal reasons).

We welcome anybody who wants to contribute in any way - please drop me an email (filip.szkandera@gmail.com) or message me on twitter (@ten_filip).

---
## Progress

🔵🔵🔵🔵🔵🔵⚪️⚪️⚪️⚪️ 60% done (Approximation)
### Already done:
* Basic simulation 
* Functional prototype 

### What has to be done:
* Check out TODO list

---
## TODO list
### Necessary

- [ ] Make the current version more reliable
- [ ] Improve VGA card (get rid of visual glitches)
- [ ] Be able to read data from instruction memory

### Nice to have (in no particular order)
- [ ] Better programmer
- [ ] Simple sound card
- [ ] Native PS/2 keyboard (and maybe mouse) support
- [ ] Better I/O
- [ ] Make it faster?
