# git-tutorial

## Passo 1: Instalando o Git
Instalando o Git no Windows:

    Baixe o instalador do Git no site oficial.
    Execute o instalador e siga as instruções.
    Escolha as configurações padrão, a menos que queira fazer alterações específicas.
    Verifique a instalação abrindo o prompt de comando e digitando git --version.

Instalando o Git no Linux:

Abra o terminal.
Atualize os pacotes do sistema com 

    sudo apt update
    sudo apt upgrade
    
Instale o Git com o comando 

    sudo apt install git
    
Verifique a instalação digitando

    git --version 
    
no terminal.

Lembre-se de adaptar as etapas de acordo com a sua versão do Windows ou distribuição Linux específica.

## Passo 2: Inicializando um repositório

Um repositório nada mais e do que uma pasta que contém o seu projeto.
Abra o terminal ou prompt de comando.
Navegue até a pasta (diretório) onde você deseja criar o repositório Git.
Execute o seguinte comando para iniciar o repositório:

    git init

Isso criará um repositório Git na pasta atual.

## Passo 3: Adicionando arquivos ao repositório

Coloque os arquivos que você deseja adicionar ao repositório em uma pasta dentro do diretório do repositório.
Por exemplo, crie uma pasta chamada "meu-projeto" e coloque seus arquivos lá dentro.
Execute o seguinte comando para adicionar todos os arquivos da pasta ao repositório:

    git add .

Isso adicionará todos os arquivos do diretório atual ao repositório Git.

## Passo 4: Criando um commit

Execute o seguinte comando para criar um commit com as alterações adicionadas:

    git commit -m "Mensagem do commit"

Substitua "Mensagem do commit" por uma descrição significativa das alterações realizadas.

## Passo 5: Conectando-se a um repositório remoto

Crie um repositório vazio em um serviço Git (por exemplo, GitHub, GitLab, Bitbucket).
Copie a URL do repositório remoto.
Execute o seguinte comando para adicionar o repositório remoto:

    git remote add origin URL_DO_REPOSITORIO

Substitua "URL_DO_REPOSITORIO" pela URL do repositório remoto que você copiou.

## Passo 6: Enviando alterações para o repositório remoto

Execute o seguinte comando para enviar as alterações para o repositório remoto:

    git push origin branch

Substitua "branch" pelo nome do ramo (branch) que você deseja enviar. Geralmente, o nome padrão é "main" ou "master".

## Passo 7: Obtendo alterações do repositório remoto

Execute o seguinte comando para obter as alterações do repositório remoto:

    git pull origin branch

Substitua "branch" pelo nome do ramo (branch) do qual você deseja obter as alterações.

## Passo 8: Clonando um repositório existente

Copie a URL do repositório que deseja clonar.
Navegue até a pasta onde deseja que o repositório seja clonado.
Execute o seguinte comando para clonar o repositório:

    git clone URL_DO_REPOSITORIO

Substitua "URL_DO_REPOSITORIO" pela URL do repositório que você copiou.
