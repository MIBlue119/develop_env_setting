## Ohmyzsh is a commandline highlight tool
https://github.com/ohmyzsh/ohmyzsh

### Install at Ubuntu

1. Install zsh first
    ``` bash
    $ apt-get install zsh 
    ```
2. Clone `Ohmyzsh` 
    ``` bash
    $ git clone https://github.com/ohmyzsh/ohmyzsh.git
    ```
3. Install `Ohmyzsh`
    ``` bash
    $ cd /ohmyzsh/tools/
    $ ./install.sh
    ```
4. Change the setting
    ``` bash
    $ nano ~/.zshrc
    ZSH_THEME="agnoster"
    ```
    - Resolve the encode error
        -  Mac
            - https://nicksheng.github.io/2017/06/30/mac-zsh/
            - https://github.com/ccyongzhi/the-Learned/issues/33
        - Ubuntu
            - https://blog.csdn.net/CoderMannul/article/details/90https://blog.csdn.net/CoderMannul/article/details/90724645724645

5. Let the zsh opened when terminal is opened
    a. Add the `zsh` to bash
    ``` bash
    $ sudo vim ~/.bashrc
    ``` 
    b. Add this line
    ``` bash
    exec zsh
    ```
