Pwnagotchi: Love Machine mode.

Named after the fictitional program from the 2009 anime movie "Summer Wars". Love Machine was an AI program written by the fictional character Wabisuke Jinnouchi (in the same movie) with the desire to learn. While not an actual villain and wasn't programmed to harm people, Love Machine became a strong adversary when it was unintentially released in the virtual world environment "Oz", and saw everything as a game.

In this mode, the pwnagotchi begins by attempting to connect to the internet using any available wifi access points, using either:

- wifi hotspots it has been given the password to,
- wifi hotspots it has discovered the password to (disabled by default for obvious reasons),
- or any free public wifi hotspots [1].

Once it does, it connects to its home base to do two things:

1. it downloads any new unhashed passwords, and adds them to its knows passwords list.
2. it uploads saved handshakes to its home base, where passwords can be later unhashed from them.

Then, the process returns to sniffing wifi handshakes before attempting to connect to the interet later.

When connecting to a hotspot, it will attempt to reduce usage. Other transfers such as pwnmail and software updates can also be optionally set to download when connected on selected wifi hotspots (or any, if in a trusted environment).

[1] If free public wifi needs a form to be completed before accessing the internet, such as entering an email or agreeing to the terms of use, the pwnagotchi will have the ability to complete it.