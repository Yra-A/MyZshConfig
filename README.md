# MyZshConfig

sudo apt update

sudo apt install zsh

// 添加 github 上的 ssh 秘钥

git config --global user.name "Yra-A"
git config --global user.email "1325083019@qq.com"
ssh-keygen -t rsa -C "1325083019@qq.com"
~/.ssh/id_rsa.pub 内容添加到 github ssh

sudo git clone https://gitee.com/Annihilater/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

sudo git clone --depth=1 https://gitee.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k

sudo git clone https://gitee.com/phpxxo/zsh-autosuggestions.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

sudo git clone https://github.com/Yra-A/MyZshConfig.git

cd MyZshConfig && cp .p10k.zsh .tmux.conf .zshrc ..

source .zshrc 


