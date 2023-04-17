### My Dev Setup

## Programming

1. Xcode (https://developer.apple.com/xcode/)

2. Java Oracle JDK (https://www.oracle.com/sg/java/technologies/downloads/)

3. Visual Studio Code (https://code.visualstudio.com/download)

4. Homebrew : 

   `bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
   
   `echo "export PATH=/opt/homebrew/bin:$PATH" >> ~/.zshrc`
   
   `echo "export PATH=/opt/homebrew/sbin:$PATH" >> ~/.zshrc`

5. Powerlevel10k :
   
   `git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k`
   
   `echo 'source ~/powerlevel10k/powerlevel10k.zsh-theme' >> ~/.zshrc` 

6. syntax highlight :
   
   `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git`
   
   `cp zsh-syntax-highlighting $HOME`
   
   `echo "source ${(q-)PWD}/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc`
   
   `source $HOME/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh`



## DevOps

1. Ansible (use python env) :

   `python3 -m venv env`
   
   `source env/bin/activate`
   
   `pip install -U boto3 botocore ansible`

2. Terraform :

   `brew install terraform`
   
   
   
