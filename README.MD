# rEFInd Gruvbox theme

This is a clean and minimal theme for rEFInd based on Gruvbox palette 

rEFInd is an easy boot manager for computers based on the EFI and UEFI by Roderick W. Smith.

### More information in the official website

[https://www.rodsbooks.com/refind/]


## Screenshots


## How to install

1. Locate your rEFInd directory. For most system is commonly <code>/boot/efi/EFI/refind</code>
    1.2. Create a folder called <code>themes</code> inside it, if it doesn't already exist 
2. Clone this repository and copy into the <code>themes</code> directory
3. Add <code>include themes/rEFInd-gruvbox/theme.conf</code> at the end of <code>refind.conf</code> on rEFInd directory.

## How to edit
If you change the background or font, you can search lines and edit this on <code>theme.conf</code>

1. Background
<code>banner themes/refind-gruvbox/img/background.png</code>
2. Font
<code>font themes/refind-gruvbox/fonts/.png</code>

Note: The font file is a simple image of the font's characters, which limits rEFInd's font capabilities. The PNG format works best for a font.

You can convert an installed monospace font using <code>mkfont.sh</code> script [https://github.com/agners/rEFInd/blob/master/fonts/mkfont.sh] like this:

´´
$ ./mkfont.sh Ubuntu-Mono 16 -1 ubuntu-mono-italic-16.png

´´

That you can copy to directory <code>themes/refind-gruvbox/fonts/</code> and edit line on <code>theme.conf</code>

## How to contribute

1. Fork this repository and clone your fork in your system
2. Copy the png icons into the appropriate icons subfolders
3. Commit, upload your fork and them open a PR

### Icons

1. The icons must be in scheme color Gruvbox palette 
2. OS - 128px x 128px 
3. Tools - 48px x 48px
4. Respect nomeclature like <code>os_arch</code> for system and <code>func_about</code> for tools. You can see all names on directory <code>boot/efi/EFI/refind/icons</code>

## Issues

If you are issues with theme, let me know =)

## Credits

Scheme Collor - Gruvbox [https://github.com/morhetz/gruvbox]
OS icons (Arch, Debian, Ubuntu, Manjaro, Fedora, Gentoo, MX, Mint, Linux) - Wikimedia [https://commons.wikimedia.org/wiki/Main_Page]
Tools icons - Flaticon [https://www.flaticon.com/] 
Font - Google fonts [https://fonts.google.com/] 

## Licence