# uwu-neofetch-art

<img src="https://github.com/blyxyas/uwu-neofetch-art/blob/main/screenshot-term.png?raw=true" alt="terminal preview" align="right" height="240">

I colorized this uwu animu girl
if you want you can use it. 

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

## Actually making the change

*(In your OS's logo section)*

* Change the `set_colors` function to `set_colors 3 5 1`
* Change the logo of your OS to the following character-art:

```
${c2}⡆⣐⢕⢕⢕⢕⢕⢕⢕⢕⠅⢗⢕⢕⢕⢕⢕⢕⢕⠕⠕⢕⢕⢕⢕⢕⢕⢕⢕⢕
⢐⢕⢕⢕⢕⢕⣕⢕⢕⠕⠁⢕⢕⢕⢕⢕⢕⢕⢕⠅${c1}⡄${c2}⢕⢕⢕⢕⢕⢕⢕⢕⢕
⢕⢕⢕⢕⢕⠅⢗⢕⠕${c1}⣠⠄${c2}⣗⢕⢕⠕⢕⢕⢕⠕${c1}⢠⣿${c2}⠐⢕⢕⢕⠑⢕⢕⠵⢕
⢕⢕⢕⢕⠁⢜⠕${c1}⢁⣴⣿⡇${c2}⢓⢕⢵⢐⢕⢕⠕${c1}⢁⣾⢿⣧${c2}⠑⢕⢕⠄⢑⢕⠅⢕
⢕⢕⠵⢁⠔${c1}⢁⣤⣤⣶⣶⣶${c2}⡐⣕⢽⠐⢕⠕${c1}⣡⣾⣶⣶⣶⣤${c2}⡁⢓⢕⠄⢑⢅⢑
⠍⣧⠄${c1}⣶⣾⣿⣿⣿⣿⣿⣿⣷${c2}⣔⢕⢄${c1}⢡⣾⣿⣿⣿⣿⣿⣿⣿⣦${c2}⡑⢕⢤⠱⢐
⢠⢕⠅${c1}⣾⣿⠋⢿⣿⣿⣿⠉⣿⣿⣷⣦⣶⣽⣿⣿⠈⣿⣿⣿⣿⠏⢹⣷⣷⡅${c2}⢐
⣔⢕⢥${c1}⢻⣿⡀⠈⠛⠛⠁⢠⣿⣿⣿⣿⣿⣿⣿⣿⡀⠈⠛⠛⠁⠄⣼⣿⣿⡇${c2}⢔
⢕⢕⢽⢸${c1}⢟${c3}⢟⢖⢖⢤${c1}⣶⡟⢻⣿⡿⠻⣿⣿⡟⢀⣿${c3}⣦⢤⢤⢔⢞⢿${c1}⢿⣿⠁${c2}⢕
⢕⢕⠅${c3}⣐⢕⢕⢕⢕⢕${c1}⣿⣿⡄⠛⢀⣦⠈⠛⢁⣼⣿${c3}⢗⢕⢕⢕⢕⢕⢕${c2}⡏⣘⢕
⢕⢕⠅${c3}⢓⣕⣕⣕⣕${c1}⣵⣿⣿⣿⣾⣿⣿⣿⣿⣿⣿⣿⣷${c3}⣕⢕⢕⢕⢕⡵${c2}⢀⢕⢕
⢑⢕⠃⡈${c1}⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿${c2}⢃⢕⢕⢕
⣆⢕⠄⢱⣄${c1}⠛⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿${c2}⢁⢕⢕⠕⢁
⣿⣦⡀⣿⣿⣷⣶⣬⣍${c1}⣛⣛⣛⡛⠿⠿⠿⠛⠛⢛⣛${c2}⣉⣭⣤⣂⢜⠕⢑⣡⣴⣿
```

Now, everytime you run `neofetch`, your terminal will be very uwu animu, just like God intended. (Screenshot above)

Made under [CC0](https://creativecommons.org/share-your-work/public-domain/cc0/).
