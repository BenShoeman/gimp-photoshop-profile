# GIMP 2.10 Photoshop Profile

This is a GIMP profile I made to make GIMP emulate Photoshop as best as I could, in terms of UI layout, tool behavior, and shortcuts. To use in Windows, replace the `2.10` directory inside `%AppData%\GIMP` (for Windows) or `~/.config/GIMP` (for Linux)  with the `2.10` directory in this repo. This will likely work fine in MacOS and Linux, but I haven't tested.

I added a few things in this repo to make my GIMP experience on first run simpler too, so I don't have to do a bunch of configuring. Specifically, I included a bunch of free fonts so GIMP can use them, I modified the default themes to use Segoe UI rather than the ugly GTK Sans font, and I added custom minimal splashes.

To use the themes with the Segoe UI font, after you've replaced the GIMP profile, just go to Edit > Preferences > Theme and choose the variant of the theme you'd like with "SegoeUI" at the end.

The splashes aren't used by default in the profile, but just place whichever .png splash file you'd like into the `2.10\splashes` folder and GIMP will use it. I included the .xcf that I made for the splash if anyone wanted to make their own splash based on it.
