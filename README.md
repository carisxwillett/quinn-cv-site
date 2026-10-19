# Quinn Willett: the drive

Quinn's CV as a scroll-to-drive trip through Los Angeles, seen from the driver's seat of his 2019 MG ZS EV. His friend Dani rides shotgun and narrates, a winking Range Rover Sport SVR driver makes him jealous, and the drive ends at the Byte Burger drive-thru with his contact details on the menu. The first click or tap turns on the sound: the MG's electric drive, tyre and wind noise, and a bass-boosted track on the radio, all synthesised in the browser.

The page is `index.html` (three.js from cdnjs, no build step), plus photo textures in `tex/` and two rigged characters in `models/`. Quinn's details live in the `CV` object near the top of the script; edit that to update the site. "Read the full CV" gives a plain, printable version for anyone in a hurry.

To run it locally, serve the folder with any static server (for example `python3 -m http.server`) and open it in a browser. Opening `index.html` straight from disk won't load the textures or characters.

## Credits

- Photo textures (road, pavement, grass, sand and building facades): Adobe Stock, free collection, licensed for this project.
- Dani: the "Michelle" character from Mixamo, via the three.js examples.
- The Range Rover driver: the Ready Player Me sample avatar from the three.js examples.
