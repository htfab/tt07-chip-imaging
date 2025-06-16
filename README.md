## tt07-chip-top

➡️ [View TT07 Microscope Image](https://tinytapeout.github.io/tt07-chip-imaging/#url=data/tt07.json)  

GDS and local interconnect (LI) were rendered using [tinytapeout-chip-renders](https://github.com/TinyTapeout/tinytapeout-chip-renders/) at a scale of 5:

```
$ cd tinytapeout-chip-renders/scripts
$ python render.py tt07 --scale 5
```

They were then sliced using the [GroupXIV slicer](https://github.com/whitequark/groupXIV).
