# Atom Launcher

[Atom](https://www.atom.io), GitHub's open source text editor, is a fantastic tool, but there's no way to set it as your default text editor, especially if you want to use a nice icon. This project fixes that, by aliasing atom.cmd in to a batch file and compiling that with [Bat to Exe Converter](http://www.f2ko.de/en/b2e.php), using `atom.ico` as the icon.

## Installation

1. Download `atom.exe` from the [Releases page](https://github.com/revxx14/atom-launcher/releases)
2. Place it in `C:\Windows\`
3. Find a file using the file type you want to set Atom as the default editor for
4. Right click on it, and select Open with... > Choose Another App > More Apps > Look for another app on this PC
5. Browse to `C:\Windows\`, select `atom.exe`, and click Open
6. Repeat for each file type you wish to associate with Atom
