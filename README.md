## 💾 Want to Save Your Current Config?

Before installing, back up your current Neovim config:

```bash
mv ~/.config/nvim ~/.config/nvim_backup
mv ~/.local/share/nvim ~/.local/share/nvim_backup
mv ~/.local/state/nvim ~/.local/state/nvim_backup
mv ~/.cache/nvim ~/.cache/nvim_backup
```

### 1. Install NvChad

```bash
  git clone https://github.com/NvChad/NvChad ~/.config/nvim --depth 1
```

```bash
  cd ~/.config/nvim/lua
  git clone https://github.com/AKL001/nvchad_conf.git custom
```
```bash
  nvim
```
```bash
  :Lazy sync – install/update plugins

  :Mason – install language servers
```
# Later, if you want to restore it:
```bash
rm -rf ~/.config/nvim
mv ~/.config/nvim_backup ~/.config/nvim

rm -rf ~/.local/share/nvim
mv ~/.local/share/nvim_backup ~/.local/share/nvim

rm -rf ~/.local/state/nvim
mv ~/.local/state/nvim_backup ~/.local/state/nvim

rm -rf ~/.cache/nvim
```
mv ~/.cache/nvim_backup ~/.cache/nvim
```
