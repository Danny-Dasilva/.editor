# .editor

nvim dotfiles for simple editor


### cloning files / Setup

`git clone --bare https://github.com/Danny-Dasilva/.editor.git` (or your fork)

`echo 'alias dotfiles="/usr/bin/git --git-dir=$HOME/.editor.git/ --work-tree=$HOME"' >> $HOME/.dotfiles`

`source ~/.dotfiles `

`dotfiles checkout --force`


### How to commit or add changes

`dotfiles add $your_file `

`dotfiles commit -m "My message"`


`dotfiles push origin main`


### in case of no origin error

`dotfiles remote add origin https://github.com/Danny-Dasilva/.editor.git`


### How to update from repo
`dotfiles pull`
