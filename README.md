# Coal

A script that takes an array of colors and outputs them in various<br \>
formats for use in other programs.


# Usage

```sh
# Convert the list of colors to the given format
coal --colors "#000000 #000000 #000000 #000000 #000000 #000000 #000000 #000000" --xresources
coal --colors "#000000 #000000 #000000 #000000 #000000 #000000 #000000 #000000" --gtk2

# Output in both firefox and xresources formats
coal --colors "#000000 #000000 #000000 #000000 #000000 #000000 #000000 #000000" --firefox --xresources

# Send the output to a file
coal --colors "#000000 #000000 #000000 #000000 #000000 #000000 #000000 #000000" --gtk2 > gtk_colors

```

