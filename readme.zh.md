# Wxh16144's Dotfiles

- [.zshrc](./backup/.zshrc)
- [my alias](./backup/.oh-my-zsh/custom/custom_alias.zsh)

[English](./readme.md) | 简体中文]

## 使用方式(不推荐的)

> **Warning**
> 正常来说，你不需要全部采用我的配置，这很危险！！！它会覆盖你原有的配置，建议你阅读 `backup` 这个目录，摘选可能适合你的配置。

### [安装 `mackup` (必须)](https://github.com/lra/mackup/blob/master/INSTALL.md)

### 克隆仓库

```bash
git clone git@github.com:Wxh16144/dotfiles.git && cd dotfiles
```

### 建立软连接

```bash
ln -s $PWD/.mackup ~/.mackup \
ln -s $PWD/.mackup_public.cfg ~/.mackup.cfg
```

### 应用

```bash
mackup restore
```