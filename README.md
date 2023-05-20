# uwu-neofetch-art

<img src="https://github.com/blyxyas/uwu-neofetch-art/blob/main/screenshot-term.png?raw=true" alt="terminal preview" align="right" height="240">

This repo contains some uwu cute anime ASCII art for neofetch.
Use it if you want!

---

## Usage

I made this for [neofetch](https://github.com/dylanaraps/neofetch). But you can probably make this work with other similar tools.

**1. Open the Neofetch binary**
This is probably in `/usr/bin/neofetch`, but you can do `where neofetch` to find it.

Now, open it in your favourite code editor.

The binary contains a lot of logos, just do a <kbd>Ctrl / ⌘</kbd> *+* <kbd>F</kbd> and find your OS, in my case Pop!_OS, so I'll search for `pop_os`.

In my case, I arrive at:

```bash
"Pop!_OS"* | "popos"* | "pop_os"*)
            set_colors 6 7
            read -rd '' ascii_data <<'EOF'
${c1}             /////////////
         /////////////////////
      ///////${c2}*767${c1}////////////////
    //////${c2}7676767676*${c1}//////////////
   /////${c2}76767${c1}//${c2}7676767${c1}//////////////
  /////${c2}767676${c1}///${c2}*76767${c1}///////////////
 ///////${c2}767676${c1}///${c2}76767${c1}.///${c2}7676*${c1}///////
/////////${c2}767676${c1}//${c2}76767${c1}///${c2}767676${c1}////////
//////////${c2}76767676767${c1}////${c2}76767${c1}/////////
///////////${c2}76767676${c1}//////${c2}7676${c1}//////////
////////////,${c2}7676${c1},///////${c2}767${c1}///////////
/////////////*${c2}7676${c1}///////${c2}76${c1}////////////
///////////////${c2}7676${c1}////////////////////
 ///////////////${c2}7676${c1}///${c2}767${c1}////////////
  //////////////////////${c2}'${c1}////////////
   //////${c2}.7676767676767676767,${c1}//////
    /////${c2}767676767676767676767${c1}/////
      ///////////////////////////
         /////////////////////
             /////////////
EOF
        ;;
```

This produces the logo, the first line is about recognizing your OS, the `set_colors` function chooses your color palette.

**2. Choosing a cute ASCII art**

If you want one with color, go to the `colored` directory, the same thing goes for `black-white`.

Explore the different ASCII arts that are available, and choose the one you like the most. Note that all colored also have a black and white counterpart, so you can "preview" it (color information distorts images)

**3. Actually making the change**

*(In your OS's logo section)*

* Change the `set_colors` function to the one specified in the file you choose (first line)
* Change the logo of your OS to the character art that follows it.

Now, every time you run `neofetch`, your terminal will be very uwu animu, just like God intended. (Screenshot above)

Made under [CC0](https://creativecommons.org/share-your-work/public-domain/cc0/).
