# Guide to Resource Modding

This is a TODO in the Modloader, so for now, this Document.



## Tools

We will use a Tool unspecific to KOTH. It is simply capable of loading a Resource File, and Importing/Exporting things from there.

Download it [HERE](./UnityExtractor.zip), extract it to some folder, and you should be ready to go!



## Editing a Texture

Simply Start "AssetBundleExtractor.exe"

then select File > Open > Select for "resources.assets" in `KOTH PATH\KingOfTheHat_Data\` this will trigger the loading

### Exporting & Editing

Next, you want to find any *Texture2D* (not Sprite) you want to edit. (You might want to Sort by Type by clicking on it)

Select that Texture, click "Plugins" and then "Export to .png/.tga" (select whichever you prefer, i'm using .png)

After saving that Texture to somewhere, you can edit it in any Program. I suggest [Asperite](https://www.aseprite.org/), it is made for Pixel art and also supports importing/exporting Animation Sheets, like KOTH is using. (you can also get it for free [here](https://github.com/aseprite/aseprite/releases) by using the Open-Source Builds)

### Importing

To then Import that Texture into the Game, click "Plugins" again (after selecting the Texture, see above), click "Edit" and then "Load" in the new window.

Select the Edited Texture, loading it.



### Saving

You can repeat the above two Steps for as many Textures as you want, then click File > Save in the Top Right Corner.

Save to *another* file next to the `resources.assets` folder. Close the Program (at least the "Assets Info" Window, which popped up after loading `resources.assets`).

Then, rename `resources.assets` to something else, for example `resources.assets.backup` this will contain the original data, for the case you want to restore it (or you can re-download the game anytime)

Rename the file you saved to in the program to `resources.assets`.

Thats all! Have fun.



## Notes:

When editing Textures, make sure to always keep the bounds the same, else weird bugs can occur
