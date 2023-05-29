# Git e Versionamento

## Table of Contents
- [Git e Versionamento](#git-e-versionamento)
  - [Table of Contents](#table-of-contents)
  - [Versionamento](#versionamento)
  - [Git](#git)
    - [Instalação](#instalação)
    - [Iniciando um repositório](#iniciando-um-repositório)
    - [Estados de um arquivo git](#estados-de-um-arquivo-git)
    - [Restaurando mudanças](#restaurando-mudanças)
    - [Gravando mudanças no repositório](#gravando-mudanças-no-repositório)
    - [Interagindo com o repositório remoto](#interagindo-com-o-repositório-remoto)
    - [Interagindo com branches](#interagindo-com-branches)

## Versionamento

O versionamento refere-se ao controle e gerenciamento de versões de um determinado conjunto de arquivos ou software. É uma prática comum em desenvolvimento de software, design, redação colaborativa e outros campos em que múltiplas versões de um trabalho estão envolvidas.

O versionamento é importante porque permite acompanhar as alterações feitas em um arquivo ou conjunto de arquivos ao longo do tempo. Cada versão é identificada com um número ou rótulo exclusivo, geralmente chamado de "versão". As versões podem ser criadas para marcar marcos importantes no desenvolvimento, correções de bugs, melhorias ou qualquer outro tipo de alteração significativa.

Existem diferentes sistemas de versionamento disponíveis, como o Git, Subversion (SVN) e Mercurial. Essas ferramentas facilitam o controle e a colaboração em projetos, permitindo que várias pessoas trabalhem nos mesmos arquivos sem conflitos. Elas mantêm um registro detalhado de todas as alterações feitas, permitindo que as versões anteriores sejam restauradas ou comparadas com as versões mais recentes.

Além disso, o versionamento também é útil para rastrear problemas e facilitar a colaboração entre equipes, especialmente em projetos complexos. Ele permite que diferentes membros da equipe trabalhem em diferentes versões do mesmo arquivo e integrem suas alterações posteriormente.

## Git

Git é um sistema de controle de versão distribuído amplamente utilizado no desenvolvimento de software. Ele permite que os desenvolvedores acompanhem as alterações feitas em seu código-fonte ao longo do tempo, facilitando o trabalho colaborativo e a organização de projetos. 

Com o Git, os desenvolvedores podem criar ramificações (branches) para trabalhar em recursos ou correções de bugs separadamente, sem interferir no código principal. Essas ramificações podem ser mescladas (merged) de volta ao código principal quando estiverem prontas. 

Além disso, o Git mantém um histórico detalhado de todas as alterações feitas no código, o que permite que os desenvolvedores revertam para versões anteriores, comparem diferenças entre versões e resolvam conflitos de mesclagem de forma eficiente. Com sua natureza distribuída, o Git também permite que os desenvolvedores trabalhem offline e sincronizem suas alterações com outros repositórios posteriormente.

### Instalação

- Realize o [Download do Git](https://git-scm.com/downloads)
- Cheque a versão intalada do git digitando o seguinte comando no terminal:
  
    ```bash
    git --version
    ``` 
- Configure o git com sua conta do GitHub

    ```bash
    git config --global user.name "User name"
    git config --global user.email "useremail@email.com"
    ``` 

### Iniciando um repositório

1. Crie um repositório 
2. Copie o endereço do repositório (Endereço terminado em **".git"**)
3. Navegue para a pasta que você deseja salvar o repositório localmente usando o comando `cd`
4. Clone o repositório

    ```bash
    git clone https://github.com/User-Name/Project-Name.git
    ```

### Estados de um arquivo git

![git status](imgs/git%20status.png)

- Checar o status do repositório local em relação ao repositório remoto

    ```bash
    git status
    ```

- Verificar o histórico de alterações (commits)

    ```bash
    git log
    ```

- Verificar mudanças nos arquivos modificados

    ```bash
    git diff
    ```


- Verificar mudanças nos arquivos staged

    ```bash
    git diff --staged
    ```

### Restaurando mudanças

- Voltar arquivos do status modificado para não modificado

    ```bash
    git restore <file-name>
    ```


- Voltar arquivos do status staged para modificado

    ```bash
    git restore --staged <file-name>
    ```

### Gravando mudanças no repositório

- Passar um arquivo do status `Modified` para `Staged`
  
    ```bash
    git add <file/folder name>
    ```

- Salvar as alterações (Arquivos no status `Staged`) para que sejam versionadas no repositório

    ```bash
    git commit -m "Um nome para a alteração"
    ```

### Interagindo com o repositório remoto

- Verificar qual o repositório remote (Geralmente é origin)

    ```bash
    git remote
    ```

- Enviar as alterações salvas(Commitadas) para o repositório remoto

    ```bash
    git push origin <nome-da-branch>
    ```


- Verifica alterações no repositório remoto antes de puxa-las para o repositório local

    ```bash
    git diff origin/<branch>
    ```

- Baixa referências do repositório remoto (Geralmente usado pra trazer novas branchs pro repositório local)

    ```bash
    git fetch
    ```

- Puxa alterações do repositório remoto para o repositório local

    ```bash
    git pull
    ```


### Interagindo com branches

- Listar branches disponiveis
    
    ```bash
    git branch
    ```

- Criar branch

    ```bash
    git branch <branch-name>
    ```

- Trocar de branch

    ```
    git checkout <branch-name>
    ```


- Mesclar branches

    ```
    git merge <not-selected-branch>
    ```