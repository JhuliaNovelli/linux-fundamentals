# Comandos Básicos do Linux

Abaixo estão alguns dos comandos mais utilizados no terminal Linux, úteis para navegação, manipulação de arquivos e gerenciamento do sistema.

## 📁 Navegação e Diretórios

- `pwd` (Print Working Directory): Exibe o caminho completo do diretório atual.
- `ls`: Lista os arquivos e diretórios no diretório atual.
  - `ls -a`: Inclui arquivos ocultos na listagem.
- `cd` (Change Directory): Altera o diretório atual.
  - Exemplo: `cd /projeto`

## 🔒 Permissões e Acesso

- `sudo` (SuperUser Do): Executa comandos com privilégios de superusuário.
  - Exemplo: `sudo ls /root`
- `sudo su`: Abre uma sessão como root mantendo o ambiente do usuário atual.

## 📄 Manipulação de Arquivos e Diretórios

- `cat`: Exibe o conteúdo de arquivos. Pode concatenar arquivos.
- `mkdir`: Cria diretórios.
- `nano`: Editor de texto no terminal.
- `mv`: Move ou renomeia arquivos/diretórios.
- `cp`: Copia arquivos/diretórios.
- `rm`: Remove arquivos especificados.
- `clear`: Limpa a tela do terminal.

## 🧠 Processos

- `ps`: Exibe processos em execução.
  - `ps aux`: Lista todos os processos com detalhes (%CPU, %MEM, PID etc.)
- `kill`: Envia sinais a processos.
  - `kill [PID]`: Interrupção suave (SIGTERM).
  - `kill -9 [PID]`: Interrupção forçada (SIGKILL).
- `killall`: Envia sinais a todos os processos com o mesmo nome.

## 🌐 Rede e Acesso Remoto

- `ssh`: Estabelece uma conexão segura com um servidor remoto.

## 🔧 Permissões

- `chmod`: Modifica as permissões de arquivos/diretórios.

## 📜 Histórico

- `history`: Exibe o histórico de comandos do terminal.

---

Esses comandos são essenciais para trabalhar de forma eficiente com o terminal Linux.
