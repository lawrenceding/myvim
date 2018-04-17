## vimrc used across windows and linux
### Step 1: Clone
```
git clone https://github.com/ghostylee/dotVim.git ~/.myvim
```

### Step 2: Link
#### linux:
```
ln -sfn ~/.myvim/vimrc .vimrc
```
#### windows:
```
(ECHO 'source ~/.vim/vimrc')>>~/_vimrc
```
### Step 3: Install [vim-plug](https://github.com/junegunn/vim-plug) 
### Step 4: Launch `vim`, run `:PlugInstall`
