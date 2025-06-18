# Filesystem Hierarchy Standard - Hierarquia do Sistema de Arquivos

   Abaixo está a lista de hierarquia dentro do sistema Linux
	
## 📁 Diretórios Essenciais para Funcionamento do Sistema

 - `/bin`
    Contém binários essenciais para o sistema e comandos usados por todos os usuários. Exemplo: ls, cp, mv.

 - `/sbin`
    Contém binários essenciais, mas voltados para administração do sistema. Exemplo: reboot, ifconfig.
 - `/lib`
    Armazena bibliotecas compartilhadas necessárias para rodar os binários de /bin e /sbin.

- `/boot`
    Contém arquivos necessários para a inicialização do sistema, como o kernel (vmlinuz) e o carregador de boot (grub).

## 📁 Diretórios de Configuração, Administração e Estado

- `/etc`
    Contém todos os arquivos de configuração do sistema e serviços. Exemplo: passwd, hosts, hostname.

- `/run`
    Armazena dados voláteis (temporários) da sessão atual do sistema, como arquivos de PID e sockets.

- `/proc`
    Sistema de arquivos virtual que fornece informações sobre os processos ativos e o kernel.

- `/sys`
    Outro sistema virtual, fornece informações e interfaces com o kernel, especialmente relacionadas a hardware.

## 📁 Diretórios de Usuário e Dados Pessoais

- `/home`
    Diretórios pessoais de cada usuário comum do sistema. Ex: /home/jhulia, /home/gustavo.

- `/root`
    Diretório pessoal do usuário root (superusuário). **Não confundir com /.**

## 📁 Diretórios de Programas e Aplicativos

- `/usr`
    Armazena dados e aplicativos do sistema usados por usuários. Inclui subdiretórios como /usr/bin, /usr/lib, /usr/share.

- `/opt`
    Local para instalação de softwares adicionais ou de terceiros *(como Google Chrome, por exemplo).*

- `/srv`
    Guarda dados usados por serviços do sistema (como FTP, HTTP, etc.).

## 📁 Diretórios Temporários e Montagens

- `/tmp`
    Armazena arquivos temporários usados por processos e aplicativos. Pode ser limpo automaticamente no reboot.

- `/mnt`
    Usado para montar temporariamente outros sistemas de arquivos durante manutenção ou uso pontual.

- `/media`
    Ponto automático de montagem para mídias removíveis como pendrives, HDs externos, CDs, etc.

## 📁 Diretórios de Dispositivos

- `/dev`
    Contém arquivos especiais que representam dispositivos do sistema, como discos (/dev/sda), terminais (/dev/tty) e muito mais.