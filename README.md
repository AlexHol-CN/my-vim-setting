# my-vim-setting
  ## Install neovim
  ```bash
  sudo add-apt-repository ppa:neovim-ppa/stable
  sudo apt-get install -y neovim
  ```
  ## Install curl
  ```bash
  sudo apt-get Install curl
  ```
  ## Install Plugh
  ```bash
  sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
  ```
  ## Install init.vim
  ```bash
  # 创建目录（不存在就新建）
  mkdir -p ~/.config/nvim

  # 下载覆盖init.vim
  curl https://raw.githubusercontent.com/AlexHol-CN/my-vim-setting/refs/heads/main/init.vim -o ~/.config/nvim/init.vim
  ```
  ## PlugInstall
  ```bash
  :PlugInstall
  ```
