# super-cool-stuff

NOTE: Make sure to update bash, and have vim and tmux installed (especially if you are using a raspberry pi!)
```
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install tmux
sudo apt-get install vim
sudo reboot
```


Make a Github folder in ~ if you haven't already (why not???)
```
cd
mkdir ~/Github
```

Clone it
```
git clone https://github.com/viabard/super-cool-stuff.git Github/super-cool-stuff
```

Make a backup folder and put current .bashrc in there
```
mkdir .bashrc_backups
mv .bashrc .bashrc_backups/.bashrc
```

Make some symbolic links to things
```
ln -s Github/super-cool-stuff/vim_runtime .vim_runtime
ln -s Github/super-cool-stuff/oh-my-bash .oh-my-bash
ln -s Github/super-cool-stuff/tmux/tmux.conf .tmux.conf
ln -s Github/super-cool-stuff/oh-my-bash/bashrc .bashrc
```

Install awesome vimrc
```
sh .vim_runtime/install_awesome_vimrc.sh
```


You should be good!
