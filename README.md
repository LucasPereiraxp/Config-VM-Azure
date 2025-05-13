# Config-VM-Azure
Pratica criação e config de uma VM no Azure
## Etapas Realizadas

1. **Criação da Conta no Azure**: 
2. **Criação da Máquina Virtual**:
   - Sistema Operacional: xxx
   - Região: xxx
   - Tamanho: xxx
   - Autenticação: Chave SSH
3. **Acesso à VM**:
   - Comando utilizado: `ssh azureuser@<IP-da-VM>`
4. **Instalação de Pacotes**:
   - Atualização do sistema: `sudo apt update && sudo apt upgrade`
   - Instalação do Nginx: `sudo apt install nginx`
5. **Configuração de Segurança**:
   - Abertura da porta 80 no grupo de segurança de rede.

## Dicas e Observações

- Utilizar o Azure Cloud Shell para executar comandos sem precisar configurar o SSH localmente.
- Lembrar de encerrar a VM após o uso para evitar cobranças adicionais.
