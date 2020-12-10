# WARNING: Discontinued folder

Now the files are in the `xcores` folder. You should update your theme in case it still use this folder. Why? It will be deleted soon and your files will no longer be supported after the deletion of this folder.

## How to update the import link without redownloading the file and losing my config?

If you are using a customized theme from this repo, you'll just have to update a line that you normally don't have to change. This is an exception this time.

1. Open the theme file in any text editor and find the line starting with `@import` (should be just after the meta - if you *really* can't find it, do Ctrl + F). If you are on browser (Stylus), just click Manage and edit the style.
2. Open the theme's "Source" link that you can find in BetterDiscord or directly in the theme meta. (if you have a 404 error, browse the files in this repo)
3. In the original file, search again the line starting with `@import` and copy the full line.
4. Replace the full line in your file by the one that you have copied and save.
5. If you did this correctly, the import link should be updated!
