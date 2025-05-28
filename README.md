## Descrição
Este é um script batch para Windows que oferece um menu interativo com várias opções de manutenção do sistema, incluindo esvaziar a lixeira, fazer backup de arquivos, escanear disco local e acessar o painel de controle.

## Funcionalidades
* Esvaziar a Lixeira - Remove todos os arquivos da lixeira do sistema
* Fazer Backup - Copia arquivos da pasta Documents para a Desktop (ajuste os caminhos conforme necessário)
* Escanear Disco Local - Executa o utilitário CHKDSK na unidade C:
* Painel de Controle - Abre o Painel de Controle do Windows
* Sair - Encerra o programa

## Como Usar
1. Clone o repositório ou baixe o arquivo .bat
2. Execute o arquivo em um ambiente Windows (clique duas vezes ou execute via cmd)
3. Selecione uma opção digitando o número correspondente e pressionando Enter

## Personalização
* Para alterar o caminho do backup, modifique a linha:
```
xcopy /T /C C:\Users\usuario\Documents\*.* C:\Users\usuario\Desktop
```
Substitua pelos caminhos desejados
* Você pode adicionar mais opções ao menu seguindo o padrão existente

## Requisitos
* Sistema operacional Windows
* Permissões de administrador para algumas funções (como CHKDSK)

## Limitações
* O script está em português e com caminhos específicos (ajuste conforme necessário)
* Algumas operações podem requerer elevação de privilégios

## Contribuição
Sinta-se à vontade para fazer fork e melhorar este script!
