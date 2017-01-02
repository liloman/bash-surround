# bash-surround

If you are used to work with vim-surround and you missed it while you where on your shell you don't have 
wait to use it. :)



#Install

```bash
cd ~/yourDir
git clone https://github.com/liloman/bash-surround
echo "bind -f ~/yourDir/bash-surround/inputrc-surround" >> ~/.bashrc
```
You need to be using the vi-mode (no luck emacs users ... :S)

In your ~/.inputrc:

```bash
#Set to vi mode by default
set editing-mode vi
#and insert mode
set keymap vi-insert
#Set vi Mode 
set -o vi
```


#Use

It cames with almost the same keybinds as vim-surround. ;)

[vim-surround](https://github.com/tpope/vim-surround)


![Example](images/example.gif "Example")

#HOW

While I was hacking for [asyncBash](https://github.com/liloman/asyncBash) I learned a lot about readline and I was able to hack this tool as a clone of the amazing [vim-surround](https://github.com/tpope/vim-surround).

#FAQ

Q. Can you port it to the emacs mode?
A. Sorry I don't use that mode but you can port it by yourself cause it's written incrementally so you just need to change the vim objects i/a selection and perhaps de mark keybindings. 


