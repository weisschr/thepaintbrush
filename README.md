Copy this to the correct QMK directory:

See intructions here:

https://github.com/artseyio/qmk-artsey/

QMK does not have the paintbrush directory set up by default in the repo.  You will have to create one
and address the errors that come with the old config data.

I have added OLED support since I put a dsiplay to determine what layer I am.  With this the Artsey
layout on the paintbrush, the OLED is extremely helpful if you lose track of where you are.

For the macro config, I simply copy the keymap into the right folder and recompile.

 qmk compile -kb artsey/thepaintbrush -km right

 Director structure:

 qmk_firmware/artsey/thepaintbrush/keymaps

 When I can sort the other files and compile without warnings or errors, I will modify the repo for the entire subdirectory.
