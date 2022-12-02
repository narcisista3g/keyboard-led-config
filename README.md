# keyboard-led-config

Aqui fica os arquivos de configurações do meu teclado led para todas bases linux, use esses arquivos quando o seu teclado de alguma forma não estar ascendendo o seu led.

### Pré Requisitos

Esteja ciente que esses arquivos irão substituir os arquivos atuais de configuração do seu teclado que vem padrão no pós instalação.

* Clonar repositório.
* Fazer backup dos arquivos atuais.
* Copiar os arquivos para a pasta determinada.
* Reiniciar ou Fazer Logout.

### Instalação

A step by step guide that will tell you how to get the development environment up and running.

```sh
git clone https://github.com/narcisista3g/keyboard-led-config.git ~/Downloads/keyboard

cd ~/Downloads/keyboard/

mkdir -p ~/Backups/Keyboard

cp -r /usr/share/X11/xkb/symbols/* ~/Backups/Keyboard/

sudo cp files/{us,br} /usr/share/X11/xkb/symbols/
```

![Makima](./images/background.jpg)
