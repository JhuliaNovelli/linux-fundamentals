# Configurando WSL Linux no Windows


# 🔧 1. Ativar o WSL e a Plataforma Virtual
    Abra o PowerShell como administrador e execute:

`dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart`
`dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart`

Depois disso, reinicie o PC.

# 🌐 2. Instalar o Ubuntu via terminal (método alternativo)
    No PowerShell, digite:

`wsl --install -d Ubuntu`

    Se já tiver o WSL instalado, use:

`wsl --list --online`

    E depois:
`wsl --install -d <nome-da-distribuição>`

    Pronto seu terminal Linux está pronto para uso dentro do seu Windows

### Rquisitos
    Sistema Operacional:
        Windows 10 versão 2004 ou superior (Build 19041 e superior). 
        Windows 11 (qualquer versão). 
        Para versões mais antigas do Windows 10, pode ser necessário habilitar manualmente o WSL e/ou atualizar para uma versão compatível com o WSL 2. 