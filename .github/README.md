i<h1 align="center">AstroNvim User Configuration</h1>

<div align="center">
<img src="https://img.shields.io/github/last-commit/nocsi/astronvim_user?style=for-the-badge&logo=github&color=a6da95&logoColor=D9E0EE&labelColor=302D41"/>
<img src="https://img.shields.io/github/repo-size/nocsi/astronvim_user?style=for-the-badge&logo=dropbox&color=7dc4e4&logoColor=D9E0EE&labelColor=302D41"/>
<img src="https://img.shields.io/github/license/nocsi/astronvim_user?style=for-the-badge&logo=powerpages&color=cba6f7&logoColor=D9E0EE&labelColor=302D41"/>
</div>

## 🌟 Preview

![Preview1](https://github.com/nocsi/astronvim_user/blob/master/.github/assets/overview.png)
![Preview2](https://github.com/nocsi/astronvim_user/blob/master/.github/assets/vertsplit.png)

## 🛠 Installation

- Install AstroNvim

```sh
git clone https://github.com/AstroNvim/AstroNvim.git ~/.config/nvim
```

- Install User Settings

```sh
git clone https://github.com/nocsi/astronvim_user ~/.config/nvim/lua/user
```

- Initialize AstroNvim

```sh
nvim --headless -c 'autocmd User PackerComplete quitall' -c 'PackerSync'
```
