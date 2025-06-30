# Segundo Projeto Linux

## Criar um script interativo em Bash que permita:

- Monitorar desempenho da CPU

- Monitorar desempenho da Memória

- Monitorar desempenho do Disco 

- Monitorar desempenho de Rede


## Comandos utilizados

| Comando         | Função                                                                            |
| --------------- | --------------------------------------------------------------------------------- |
| `top -bn1`      | Executa o `top` uma vez em modo batch (sem interface interativa)                  |
| `grep "Cpu(s)"` | Filtra apenas a linha de CPU do `top`                                             |
| `awk`           | Processa texto e extrai campos específicos de saída (como CPU, RAM, rede)         |
| `free -m`       | Exibe o uso de memória em megabytes                                               |
| `df -h /`       | Mostra uso de disco da partição raiz `/` com tamanhos "humanos"                   |
| `date`          | Mostra data/hora atual (usado para mostrar horário de atualização)                |
| `sleep 15`      | Aguarda 15 segundos antes de atualizar novamente                                  |
| `printf`        | Exibe texto formatado (usado na parte da rede para limitar casas decimais)        |
| `/proc/net/dev` | Arquivo do sistema que mostra estatísticas de rede                                |
| `exit`          | Encerra o processamento do `awk` após pegar a primeira interface válida           |
| `gsub()`        | Função do `awk` para substituir texto (usada para tirar `:` do nome da interface) |
