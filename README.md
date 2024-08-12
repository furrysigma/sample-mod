# Sample Mod

> :warning: This does NOT work on the official page! Mods will only work on our archive patcher.

### How do I use this?

On the **archived** version of thisisnotawebsitedotcom, you can use the code "mods" to access the mod list.</br>
From there, just enter in "furrysigma/sample-mod" and it will be loaded.

After loading it, the code provided is "skibidi". It should respond with "dop dop".

### How do I make my own mod?

Fork this repository, name it how you'd like.
In the `mod.json` file, you can define as many codes as you'd like and attach them to files *within the repository*.

> :exclamation: Mods with overlapping codes will not be prioritized, and the original code will be displayed instead.
> Please also ensure that your mime types are correct, as shown below:

File Extension | Mimetype
 - .html => `text/html`
 - .mp4 => `video/mp4`
 - .mp3 => `audio/mpeg`
 - .png => `image/png`
