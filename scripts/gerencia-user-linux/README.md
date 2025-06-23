
#Primeiro projeto Linux

##Criar um script interativo em Bash que permita:

- Criar usuários

- Deletar usuários

- Listar usuários

- Adicionar/remover usuários de grupos


##Comandos utilizados

|    Comando          | O que faz                                |
| --------------------|----------------------------------------- |
| `useradd -m`        | Cria um usuário com diretório home       |
| `userdel -r`        | Remove o usuário e seu diretório home    |
| `cut -d: -f1`       | Lê o nome dos usuários do `/etc/passwd`  |
| `usermod -aG`       | Adiciona o usuário a um grupo secundário |
| `gpasswd -d`        | Remove o usuário de um grupo             |

| `chmod +x` + arquivo| Torne o script executável                |
