---
layout: default
title: Wine Manager
permalink: /
---

# Wine Manager

Um simples script Bash para ajudar a gerenciar prefixos Wine e facilitar a execução de aplicativos e jogos Windows no Linux.

## Dependências

- `wine`
- `winetricks`

## Instalação

### 1. No Arch Linux (AUR)

Instale usando um AUR helper (recomendado, ex: `yay`):

```bash
yay -S wine-manager
````

Ou manualmente via git e makepkg:

```bash
git clone https://aur.archlinux.org/wine-manager.git
cd wine-manager
makepkg -si
```

### 2. Em Debian/Ubuntu

```bash
wget -c https://github.com/pedrodev2025/wine-manager/releases/download/1.2/wine-manager_1.2.deb
sudo apt install ./wine-manager_1.2.deb
```

### 3. Em Outros Sistemas Linux (Instalação Manual)

```bash
sudo wget -O /usr/local/bin/wine-manager https://raw.githubusercontent.com/pedrodev2025/wine-manager/refs/heads/main/wine-manager
sudo chmod +x /usr/local/bin/wine-manager
```

> É recomendado usar `/usr/local/bin/` para scripts instalados manualmente, pois geralmente está no seu `$PATH` e não interfere com pacotes do sistema.

## Sobre

Wine Manager facilita o gerenciamento de múltiplos prefixos e a execução de aplicativos Windows no Linux de forma prática e organizada.

## Licença

BSD-3-Clause

## Contribua

Sinta-se a vontade para fazer um pull request ou uma issue!
