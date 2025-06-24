# Alterações realizadas para melhor desempenho do bash

Alterado o comportamento do case 3 (Listar Usuários). O comando anterior listava todos os usuários do sistema, incluindo contas padrão e de sistema. A lógica foi ajustada para filtrar e exibir apenas os usuários criados pelo administrador, proporcionando maior precisão na identificação e reduzindo a quantidade de entradas exibidas.

### Código inicial
``` 3)
            echo "Lista de usuários:"
            cut -d: -f1 /etc/passwd
            ;;
```

### Código atual
```
 3)
                echo "Lista de usuários:"
                 awk -F: '$3 >= 1000 && $3 < 65534 { print $1 }' /etc/passwd
                ;;
```