# New_Installation


## sudo apt install git 
## sudo apt install vim 
   - git clone --depth=1 git://github.com/amix/vimrc.git ~/.vim_runtime
     sh ~/.vim_runtime/install_basic_vimrc.sh
## set github
   generate rsa
   '''
   ssh-keygen -t rsa -b 4096 -C "wang_yancy@outlook.com"

   '''
	add ssh-agent in the background
	'''
	eval "$(ssh-agent -s)"
	'''
    copy ssh key to clipboard
	'''
	sudo apt install xclip
	xclip -sel clip < ~/.ssh/id_rsa.pub
	'''
## sudo apt install zsh
   - sudo chsh -s $(which zsh)
   - logout 
   - sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"


## sudo apt install libboost-dev
## madgraph5
## yaml-cpp
## delphes
 

