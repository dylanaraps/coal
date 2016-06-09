# Coal

A script that takes an array of colors and outputs them in various<br \>
formats for use in other programs.


# How it works

**1.** Edit the array at the top of the script with your colors.

```sh
# Example array.
c=(
    '#232c33'
    '#99736e'
    '#78a090'
    '#bfb7a1'
    '#7c9fa6'
    '#BF9C86'
    '#99BFBA'
    '#f0f0f0'
    '#70838c'
    '#99736e'
    '#78a090'
    '#bfb7a1'
    '#7c9fa6'
    '#BF9C86'
    '#99BFBA'
    '#f0f0f0'
)
```

**2.** Run `coal` to output your colors in various formats for use<br \>
with other programs.

```sh
# Example usage

# Xresources
# output: *.color00:  #000000
coal --xresources

# Shell
# output: export color00="#000000"
coal --shell

# GTK2
# output: gtk_color_scheme = "color_00:#000000"
coal --gtk2

# Firefox css
# output: --color00: #000000;
coal --firefox
```

**3.** Add `> filename` to the end of the command to save the output to a file.
