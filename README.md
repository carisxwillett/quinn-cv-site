# Quinn Willett: the drive

Quinn's CV as a scroll-to-drive trip through Los Angeles, seen from the driver's seat of his 2019 MG ZS EV. His friend Dani rides shotgun and narrates, a winking Range Rover Sport SVR driver makes him jealous, and the drive ends at the Byte Burger drive-thru, where Quinn orders, the worker hands over his CV and it opens full screen. The first click or tap turns on the sound: the engine and road noise, synthesised in the browser, and "Flower In A Hurricane" from GTA VI on the radio, played through YouTube's own player. If the song can't load, or on a phone until you tap Play song, the car plays its own bass-boosted beat instead.

The page is `index.html` (three.js from cdnjs, no build step), plus photo textures in `tex/` and rigged characters in `models/`. Quinn's details live in the `CV` object near the top of the script; edit that to update the site. "Read the full CV" gives a plain, printable version for anyone in a hurry.

To run it locally, serve the folder with any static server (for example `python3 -m http.server`) and open it in a browser. Opening `index.html` straight from disk won't load the textures or characters.

## Credits

- Photo textures (road, pavement, grass, sand and building facades): Adobe Stock, free collection, licensed for this project.
- Dani: Microsoft Rocketbox avatar Female_Adult_17 (MIT licence, see models/dani5_LICENSE.txt), hair lightened and sunglasses added.
- The Range Rover driver and the Byte Burger worker: the Ready Player Me sample avatar from the three.js examples.
- Music: "Flower In A Hurricane" by Justice featuring Tame Impala, SZA and King Gizzard & The Lizard Wizard, from the GTA VI soundtrack. The track is not included in this repository; the page embeds the official YouTube upload (provided by Because Music) in YouTube's player.
