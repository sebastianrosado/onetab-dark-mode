# Dark Mode for OneTab

To get dark mode, you will to need to replace a few of the OneTab source files with the modified versions in this repo and then load the folder with the modified files into your browser as an **unpacked** extension. To do so, start by uninstalling OneTab (and don't forget to export your bookmarks before you do so).

Then, find where the OneTab extension lives on your machine. This will vary based on your OS and browser, but some Googling for "X browser extension location on Y operating system" should lead you there. Once you've found it, replace the extension's original js, html and css files with the ones above. **Note:** As of the date of this writing, some of the files above haven't been modified. I uploaded the original versions of each file to the repo to start it off, so anyone can check the commit messages/diffs to see which files have changed. Otherwise just replace every file if you don't feel like checking.

Once that's done, upload the parent folder as an unpacked extension into your browser and just like that you will stop losing your eyesight. Dark mode should be working.

# Summary of Changes

## Text Color

### Non-clickable

#AFB4BB replaces #888 and #777

### Clickable

#4EA6FF replaces #234da7

## Background Color

### Main

#0D1117 replaces #light-at-the-end-of-the-tunnel-white

### Settings Box

#30363d replaces #am-i-in-heaven-white
