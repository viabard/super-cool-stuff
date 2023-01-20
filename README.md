# super-cool-stuff

NOTE:
Make sure to update bash (especially if you are using a raspberry pi!)
`sudo apt-get update
sudo apt-get upgrade
sudo reboot` 


Go home
`cd`

Make a Github folder in ~ if you haven't already (why not???)
`mkdir ~/Github`
`cd Github`

Clone it
`git clone https://github.com/viabard/super-cool-stuff.git Github/super-cool-stuff`

Make some symbolic links to things
`ln -s Github/super-cool-stuff/vim_runtime .vim_runtime`
`ln -s Github/super-cool-stuff/oh-my-bash .oh-my-bash`

Make a backup folder and put current .bashrc in there
`mkdir .bashrc_backups`
`mv .bashrc .bashrc_backups/.bashrc`

Make another symbolic link
`ln -s Github/super-cool-stuff/oh-my-bash/bashrc .bashrc`

Install vim if you don't have it already
`sudo apt-get install vim`

Install awesome vimrc
`sh .vim_runtime/install_awesome_vimrc.sh`
