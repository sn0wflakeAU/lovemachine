Pwnagotchi: Love Machine mode.

![Love Machine from Summer Wars](lovemachine-summerwars.jpeg)

**Currently in the planning/experimental stage**

Named after the fictitional program from the 2009 anime movie "Summer Wars". Love Machine was an AI program written by the fictional character Wabisuke Jinnouchi (in the same movie) with the desire to learn. While not an actual villain and wasn't programmed to harm people, Love Machine became a strong adversary when it was unintentially released in the virtual world environment "Oz", and saw everything it could do as a game.

In this mode, the pwnagotchi begins by attempting to connect to the internet using any available wifi access points, using either:

- wifi hotspots it has been given the password to,
- wifi hotspots it has discovered the password to (disabled by default for obvious reasons),
- or any free public wifi hotspots [1].

Once it does, it connects to its home base to do two things:

1. it downloads any new unhashed passwords, and adds them to its known passwords list.
2. it uploads saved handshakes to its home base, where passwords can be later unhashed from them.

Then, the process returns to sniffing wifi handshakes before attempting to connect to the internet later.

When connecting to a hotspot, it will attempt to reduce usage. Other transfers such as pwnmail and software updates can also be optionally set to download when connected on selected wifi hotspots (or any, if in a trusted environment).

*[1] If free public wifi needs a form to be completed before accessing the internet, such as entering an email or agreeing to the terms of use, the pwnagotchi will have the ability to complete it.*

## License

This plugin is released under the GPLv3 License

```
pwnagotchi:lovemachine - A pwnagotchi exploring the internet on its own.
Copyright (C) 2024  Sam "sn0wflake" Allen

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
