#### Preview

![](PoC.png)

Pretty Tmux config

### Install
MacOs
```bash
brew install tmux
```
Linux
```bash
sudo apt-get install tmux
```
Install using tpm 
```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

If you are a tpm user, you can install the theme and keep up to date by adding the following to your .tmux.conf file:
```
set -g @plugin 'tmux-plugins/tpm'
set -g @plugin 'tmux-plugins/tmux-sensible'
set -g @plugin 'kylepeeler/tmux-nightowl'
set -g @nightowl-border-contrast true
set -g @nightowl-cpu-usage true
set -g @nightowl-ram-usage true
set -g @nightowl-show-powerline true

set -g mouse on

run -b '~/.tmux/plugins/tpm/tpm'
```
- Use the tpm install command: prefix + I (default prefix is ctrl+b)
- so : Crtl + b , then I together press it will install the theme


