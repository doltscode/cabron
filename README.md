## Cabron Arch Linux Helper

### Índice

* [O que é?](#oque)
* [Instalação](#instalacao)
* [Suporte e Contato](#suporte)
* [Motivação](#motivacao)
* [Licença](#licenca)

<a name="oque"></a>

```
           _                     
  ___ __ _| |__  _ __ ___  _ __  
 / __/ _` | '_ \| '__/ _ \| '_ \ 
| (_| (_| | |_) | | | (_) | | | |
 \___\__,_|_.__/|_|  \___/|_| |_|
                                 
               
```

O **Cabron** é um instalador automático simples e fácil de usar para o Arch Linux.

<a name="instalacao"></a>
### Instalação

[Baixe](https://www.archlinux.org/download/) o [Arch Linux](https://www.archlinux.org) normalmente, grave a imagem em um CD, DVD ou Pen-Drive, utilizando o [Etcher](https://etcher.io)(Windows, Linux, MacOS) ou manualmente(Linux): 

```bash
sudo dd if=/home/usuario/Downloads/archlinux-2017.10.01.iso of=/dev/sdX bs=4M status=progress && sync
```

* Altere `/dev/sdX` pela letra da sua unidade(*com cuidado!* Todos seus dados serão apagados nesta unidade!).
* Altere `/home/usuario/Downloads/` para a pasta que salvou a ISO. 
* Altere: `archlinux-2017.10.01.iso` pelo nome correto da ISO.

Após o boot rode o seguinte comando: 

```bash
bash <(curl -s -L http://bit.ly/cabron-arch)
```  

A partir deste momento o Cabron deve lhe guiar por todos os passos, desde a configuração do layout do teclado, passando pelo particionamento e terminando na instalação do GRUB(ou systemd-boot) e opcionalmente instalando gerenciadores de login(LightDM, SLiM, nodm, etc...) e gerenciadores de janelas ou ambientes de trabalho(i3wm, OpenBox, Mate, Cinnamon, Gnome, XFCE, etc...).

<a name="suporte"></a>
### Suporte e Contato

[Telegram](https://t.me/archbrdev)  
[Lista de Discussão](mailto:cabron@googlegroups.com)

<a name="motivacao"></a>
### Motivação

Notando que muitos usuários nos fóruns de discussão, IRC, Telegram, listas de discussão e outros meios de comunicação sentiam alguma dificuldade em instalar o Arch Linux sem nenhum tipo de script ou helper, nós nos empenhamos em construir um script simples, fácil e limpo para guiar estes usuários atráves da instalação do Arch Linux, este maravilhoso sistema operacional.

<a name="licenca"></a>
### Licença

[GPL-3.0](LICENSE)

![Cabron](img/cabron.svg "Vacron")