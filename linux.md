#  Documentação de Linux no VirtualBox

Este documento detalha o processo de instalação e configuração básica do sistema operacional Linux (Ubuntu) dentro do ambiente de virtualização do VirtualBox.

## 1. Instalação do Ubuntu

### 1.1. Download da Imagem ISO
Para começar, é necessário baixar a imagem oficial do Ubuntu.
- [Baixar Ubuntu Desktop](https://ubuntu.com/download/desktop)

### 1.2. Criação da Máquina Virtual
- Abra o VirtualBox e clique em "Novo".
- **Nome:** Ubuntu
- **Tipo:** Linux
- **Versão:** Ubuntu (64-bit)
- **Memória RAM:** 5GB
- **Disco Rígido:** 50GB 

### 1.3. Processo de Instalação
- Inicie a máquina virtual.
- No menu de boot, selecione "Try or Install Ubuntu".
- Quando o sistema carregar, clique no ícone "Install Ubuntu Desktop".
- Siga os passos do instalador, escolhendo o idioma, o layout do teclado e outras configurações.

## 2. Primeiros Passos e Comandos Essenciais

Após a instalação, é importante se familiarizar com o Terminal, a ferramenta mais poderosa do Linux.

### 2.1. Navegação no Terminal
- **Abrir o Terminal:** Use o atalho `Ctrl + Alt + T` ou procure por "Terminal" no menu de aplicativos.
- `ls`: Lista os arquivos e pastas no diretório atual.
- `cd [pasta]`: Entra em uma pasta. Ex: `cd Documentos`.
- `pwd`: Mostra em qual diretório você está.

### 2.2. Gerenciador de Pacotes (`apt`)
O `apt` é usado para instalar e gerenciar programas.
- `sudo apt update`: Atualiza a lista de pacotes disponíveis.
- `sudo apt install [nome_do_programa]`: Instala um programa. Ex: `sudo apt install gimp`.
  
### 3. Primeiras Impressões: 
Nossas primeiras impressões sobre a aparência do Linux (Ubuntu) foram muito positivas. Achamos a interface **bem bonita** e **agradável**, 
com um design limpo e moderno. O sistema pareceu **muito leve e fluido**, o que nos passa a impressão de que pode ser até mais eficiente que o Windows para certas tarefas.
